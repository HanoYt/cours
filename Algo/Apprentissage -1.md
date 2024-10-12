```mermaid 
CUSTOMER }|..|{ DELIVERY-ADDRESS : has CUSTOMER ||--o{ ORDER : places CUSTOMER ||--o{ INVOICE : "liable for" DELIVERY-ADDRESS ||--o{ ORDER : receives INVOICE ||--|{ ORDER : covers ORDER ||--|{ ORDER-ITEM : includes PRODUCT-CATEGORY ||--|{ PRODUCT : contains PRODUCT ||--o{ ORDER-ITEM : "ordered in"```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM4MjI0ODM1NF19
-->