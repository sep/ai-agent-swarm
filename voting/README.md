The alert is analyzed by three independent detection models.

The Consensus Agent evaluates their outputs (e.g., majority vote or confidence scoring).

The final decision is passed to the next stage of the swarm (e.g., incident investigation).

-----

flowchart TD
    A[Incoming Security Alert] --> B[Detection Model A]
    A --> C[Detection Model B]
    A --> D[Detection Model C]

    B --> E{Consensus Agent}
    C --> E
    D --> E

    E --> F[Final Classification Decision]
