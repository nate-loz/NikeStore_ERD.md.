# NikeStore_ERD.md.

---
title: Nike Store ERD
---

```mermaid
erDiagram
    CUSTOMER }|..|{ PRODUCT : knows
    PRODUCT ||--o{ SALE : yes
    SALE ||--o{ INVENTORY : "taken from"
``` 
