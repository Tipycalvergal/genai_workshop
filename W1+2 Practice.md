```mermaid
flowchart TD
    A[💡 Idea] --> B[⚙️ In Progress]
    B --> C[🔍 Review]
    C --> D[✅ Done]

    B -->|Blocked| E[🚧 Waiting]
    E --> B
