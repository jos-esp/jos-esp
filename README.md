graph TD
    A[Iniciativa de Leyes (Artículo 71)] --> B[Presentación de la iniciativa]
    B --> C[Discusión y votación en la Cámara de origen]
    C --> D{Aprobada en Cámara de origen?}
    D -->|Sí| E[Envío a la Cámara revisora]
    D -->|No| F[Rechazada]
    E --> G[Discusión y votación en la Cámara revisora]
    G --> H{Aprobada sin cambios?}
    H -->|Sí| I[Envío al Ejecutivo]
    H -->|No| J[Modificada y regresa a la Cámara de origen]
    I --> K{Aprobada por el Ejecutivo?}
    K -->|Sí| L[Publicación en el Diario Oficial de la Federación]
    K -->|No| M[Regresa al Congreso para reconsideración]
