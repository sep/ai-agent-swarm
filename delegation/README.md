The Incident Commander assigns tasks to specialized response agents.

Each agent handles a specific phase of the response lifecycle.

-----

flowchart TD
    A[Incident Commander Agent] --> B[Containment Agent]
    A --> C[Eradication Agent]
    A --> D[Recovery Agent]

    B --> E[Contain Malware]
    C --> F[Remove Malware]
    D --> G[Restore Systems]
