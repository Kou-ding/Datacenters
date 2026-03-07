# Data-Centers

The presentation of the university subject "Distributed Generation" regarding data centers. 

## Structure

```mermaid
graph TD;
    subgraph "Internet / Users"
        INTERNET[🌐 Internet Traffic]
        CDN[📦 CDN Edge]
    end

    subgraph "Data Center Perimeter"
        FW1[🔥 Firewall]
        LB1[⚖️ Load Balancer]
        WAF[🛡️ WAF]
    end

    subgraph "Compute Layer"
        WEB[🖥️ Web Servers]
        APP[⚙️ Application Servers]
        MICRO[📦 Microservices]
        K8S[☸️ Kubernetes Cluster]
    end

    subgraph "Storage & Database"
        DB1[(🗄️ Primary DB)]
        DB2[(🗄️ Replica DB)]
        CACHE[(⚡ Redis Cache)]
        NAS[💾 NAS Storage]
        SAN[📀 SAN Storage]
    end

    subgraph "Infrastructure"
        COOL[❄️ Cooling/HVAC]
        POWER[⚡ UPS/Generators]
        RACK[🔧 Server Racks]
        NET[🔌 Network Fabric]
    end

    INTERNET --> CDN
    CDN --> FW1
    FW1 --> WAF
    WAF --> LB1
    LB1 --> WEB
    WEB --> APP
    APP --> MICRO
    MICRO --> K8S
    
    APP --> CACHE
    CACHE --> DB1
    DB1 --> DB2
    DB1 --> NAS
    NAS --> SAN
    
    RACK --> COOL
    RACK --> POWER
    RACK --> NET
    NET --> WEB
    NET --> DB1
```

## Cooling
```mermaid
graph LR
    A[⚡ Utility Grid] --> B[🔋 UPS Battery]
    B --> C[⚡ Power Distribution Unit]
    C --> D[🔌 Server Racks]
    
    E[🌡️ Hot Air] --> F[❄️ CRAC/CRAH Units]
    F --> G[💧 Chilled Water]
    G --> H[🌀 Cooling Towers]
    H --> I[🌊 Condenser Water]
    I --> F
    D --> E
    
```
Sources
- [Marp Customization][1]

[1]: https://chris-ayers.com/posts/customizing-marp/ "Unleash Your Creativity with Marp Presentation Customization - By Chris Ayers"
