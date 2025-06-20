# meeting-agent-frontend
Repository with all the components of Meeting Agent front-end

```mermaid
flowchart TD
    A[User accesses Login Page] --> B[Login Page authenticates User]
    B --> C[Load Chat Front-End Page]
    C --> D[Router Agent]
    
    D -->|Parallel| E[Company Meeting Agent]
    D -->|Parallel| F[Person Meeting Agent]
```
