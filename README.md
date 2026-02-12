# Domain-Driven-Backend
Experimental sample of Onion architecture and Spring Boot best practices


## Project Folder Structure
<pre>
├── core
│   ├── application
│   │   ├── dto
│   │   ├── event
│   │   ├── exception
│   │   ├── handler
│   │   ├── interface
│   │   ├── mapper
│   │   ├── security
│   │   ├── service
│   │   └── validation
│   └── domain
│       ├── aggreagte
│       ├── entity
│       ├── event
│       ├── exception
│       ├── interface
│       │   ├── repository
│       │   └── unitofwork
│       ├── service
│       ├── shared
│       │   ├── constant
│       │   └── enum
│       ├── specification
│       └── valueobject
└── external
    ├── infrastructure
    │   ├── api
    │   ├── config
    │   │   ├── datasource
    │   │   ├── kafka
    │   │   └── security
    │   ├── logging
    │   ├── messaging
    │   ├── persistance
    │   │   ├── mapper
    │   │   └── repository
    │   ├── security
    │   ├── storage
    │   └── util
    └── webapi
        ├── advice
        ├── config
        ├── controller
        ├── documentation
        ├── mapper
        ├── request
        ├── response
        └── validator 
</pre>
