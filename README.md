## Architecture Overview

```text
                    Internet
                       │
                       ▼
              ┌─────────────────┐
              │   AWS Amplify   │
              │    Frontend     │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │   Amazon VPC    │
              │                 │
              │  Public Subnet  │
              │  ┌───────────┐  │
              │  │    EC2     │  │
              │  └─────┬─────┘  │
              │        │        │
              │  Private Subnet │
              │  ┌───────────┐  │
              │  │    RDS    │  │
              │  └───────────┘  │
              └─────────────────┘
```

## 🎥 Project Demo

[▶️ Watch ZenVPC Project Demo](https://github.com/user-attachments/assets/db38cb82-6962-43dd-a2ba-4b164)
