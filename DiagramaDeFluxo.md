Este diagrama representa o fluxo do aplicativo de fretado, incluindo as principais funcionalidades tanto para os funcionários quanto para os motoristas.

1. Fluxo principal do usuário:

```mermaid
flowchart TD
    A[Login/Registro] -->|Autenticação| B[Dashboard do Funcionário]
    B --> C[Agendamento Semanal]
    B --> D[Rastreamento em Tempo Real]
    B --> E[Check-in Digital]
    B --> F[Alertas e Notificações]
    B --> G[Alternativas de Transporte]

    style A fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style E fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style G fill:#444,stroke:#fff,stroke-width:2px,color:#fff
```

2. Funcionalidades secundárias do usuário:

```mermaid
flowchart TD
    B[Dashboard do Funcionário] --> H[Histórico e Estatísticas]
    B --> I[Achados e Perdidos]
    B --> J[Feedback e Avaliação]
    B --> K[Perfil e Configurações]
    B --> L[Suporte e Emergência]
    B --> M[Comunidade e Fórum]

    style B fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style H fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style I fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style J fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style K fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style L fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style M fill:#444,stroke:#fff,stroke-width:2px,color:#fff
```

3. Funcionalidades específicas:

```mermaid
flowchart TD
    D[Rastreamento em Tempo Real] --> N[Alarmes de Proximidade]
    E[Check-in Digital] --> O[Modo Soneca]
    F[Alertas e Notificações] --> P[Configurar Alertas]
    G[Alternativas de Transporte] --> Q[Carona Compartilhada]

    style D fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style E fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style G fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style N fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style O fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style P fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style Q fill:#444,stroke:#fff,stroke-width:2px,color:#fff
```

4. Fluxo do motorista:

```mermaid
flowchart TD
    R[Dashboard do Motorista] --> S[Lista de Passageiros]
    R --> T[Rastreamento e Rota]
    R --> U[Confirmação de Embarque]
    R --> V[Relatórios e Desempenho]

    style R fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style S fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style T fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style U fill:#444,stroke:#fff,stroke-width:2px,color:#fff
    style V fill:#444,stroke:#fff,stroke-width:2px,color:#fff
```
