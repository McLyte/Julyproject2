```mermaid
graph TD
    A[User Device: Web or Mobile App] --> B[Frontend UI: React.js / React Native]
    B --> C[API Layer: Node.js / Python FastAPI]

    C --> D[Database: Supabase / Firebase]
    C --> E[OpenAI GPT API]

    C --> F[Returns guidance, courses, career maps]
    F --> G[Frontend displays chat, dashboards, resources]

    
    style A fill:#D2E2FB,stroke:#3366CC,stroke-width:2px,color:#333
    style B fill:#F9E79F,stroke:#D68910,stroke-width:2px,color:#333
    style C fill:#E2F0D9,stroke:#5CB85C,stroke-width:2px,color:#333
    style D fill:#F4CCCC,stroke:#CC0000,stroke-width:2px,color:#333
    style E fill:#F8C4B4,stroke:#E67E22,stroke-width:2px,color:#333
    style F fill:#D9EDF7,stroke:#31708F,stroke-width:2px,color:#333
    style G fill:#F9E79F,stroke:#D68910,stroke-width:2px,color:#333
