# Santander Dev Week 2025
Java RESTful API criada para o Santander Dev Week

## Diagrama de classes 

```mermaid
classDiagram
    class User {
        +String name
        +Account account
        +List<Feature> features
        +Card card
        +List<News> news
    }

    class Account {
        +String number
        +String agency
        +double balance
        +double limit
    }

    class Feature {
        +String icon
        +String description
    }

    class Card {
        +String number
        +double limit
    }

    class News {
        +String icon
        +String description
    }

    User --o Account
    User --o Feature
    User --o Card
    User --o News
```
