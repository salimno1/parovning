<<<<<<< HEAD
 parovning

Userstory-001
```js
string name = "Salim"
```

=======
# parovning

## ER diagram in markdown

erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }
>>>>>>> c101a745dddcecaabbb7a6ed4dc62f7fbbbaf9d4

