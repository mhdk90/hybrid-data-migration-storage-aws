# Architecture

```mermaid
flowchart LR
  NFS[On-Prem NFS Server] --> AGENT[AWS DataSync Agent]
  AGENT --> TASK[AWS DataSync Task]
  TASK --> S3[Amazon S3 Destination Bucket]

  VPN[VPN / Direct Connect - optional] -. documented path .-> TASK
  SGW[Storage Gateway - related pattern] -. documented path .-> S3
  SNOW[Snowball Edge - offline migration option] -. documented path .-> S3
