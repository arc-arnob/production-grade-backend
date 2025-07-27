## Useful Mantars:
 - Keeps controllers skinny, services fat, repos dumb
## Tech Used:
| **Tech Stack**                  | **Purpose**                                   |
|---------------------------------|-----------------------------------------------|
| **Spring Boot**                 | Core framework for application setup & config |
| **Spring Web / Spring MVC**     | Build REST APIs                               |
| **Spring Security + JWT**       | Authentication & authorization                |
| **Spring Data JPA (Hibernate)** | ORM for database persistence                  |
| **PostgreSQL** (or MySQL)       | Relational database                           |
| **Spring Validation**           | Input validation with `@Valid` & constraints  |
| **Spring Boot Actuator**        | Health checks & metrics                       |
| **Spring Cloud OpenFeign**      | HTTP client for calling Stripe API            |
| **Maven**                       | Dependency management & build tool            |

## Phases
### Phase 1: Authentication using JWT.
    - [] Users can sign up & login → get JWT token.
    - [] Token must be sent in header for all secured requests.
### Phase 2 – Admin Features
    - [] CRUD products
### Phase 3 -  Customer Features
    - [] Read and Search Products
    - [] CRUD item cart
    - [] View and checkout Cart.
### Phase 4 - Checkout & Payment
    - [] Integrate StripeAPI
    - [] Send Payment request
    - [] Handle Stripe webhook response
### Phase 5 - Observability & Hardening
    - [] Actuator
    - [] API logging
    - [] Global Execption handler
    - [] Dockerize
### Phase 6 - Add More Services
    - [] Think of Business Units as Services.
