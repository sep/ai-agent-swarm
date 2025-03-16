Each agent specializes in a different data source (network, host, threat intel).

The Evidence Aggregator combines the outputs into a unified incident report.

-----

flowchart TD
    A[Incident Alert] --> B[Network Forensics Agent]
    A --> C[Host Forensics Agent]
    A --> D[Threat Intelligence Agent]

    B --> E{Evidence Aggregator}
    C --> E
    D --> E

    E --> F[Complete Incident Report]
