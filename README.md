
## GitHub Actions flow

```mermaid
  graph TD;
    A[Events] -->|Trigger| B[Workflows]
    B --> |contains| C[Jobs]
    C --> |uses| D[Actions]

```
> Graph made using Mermaid markdown
