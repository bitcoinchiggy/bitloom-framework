# Diagrams

This page renders the two main diagrams directly inside the site.

## Wallet Design – Flowchart

    ```mermaid
    flowchart TD
      A["OpsCo (Client)<br/>- Legal owner of BTC<br/>- Holds >=1 signing key"]
      B["Parent-Owned LLC<br/>(Coordinator / XPUB Licensor)"]
      C1["Senior Technician (Employee)<br/>- Custodial agent<br/>- Signs on instruction<br/>- Reviews logs"]
      C2["Junior Technician (Employee)<br/>- Custodial agent<br/>- Signs on instruction"]
      P["Key Management Policy<br/>Backups, Rotation, Logging, Incidents"]

      A --- B
      B --- C1
      B --- C2
      B --- P
    ```

## Wallet Transaction Flow – Sequence

    ```mermaid
    sequenceDiagram
      participant OpsCo
      participant Manager
      participant Senior
      participant Junior
      participant Network

      OpsCo->>Manager: Submit transfer request (amount, destination)
      Manager->>Manager: Construct PSBT from multisig XPUB set
      Manager->>Senior: Request signature (K2)
      Senior-->>Manager: Return partial signature
      Manager->>Junior: Request signature (K3)
      Junior-->>Manager: Return partial signature
      Manager->>Network: Broadcast fully signed transaction
      Manager-->>OpsCo: Provide txid and log entry
    ```
