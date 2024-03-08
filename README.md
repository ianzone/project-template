# Badges

[![shields](https://img.shields.io/badge/shields.io-blue?logo=shieldsdotio&labelColor=grey)](https://shields.io/docs/logos)

# Diagram

https://mermaid.js.org/

```mermaid
flowchart TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end
    one --> two
    three --> two
    two --> c2
```
