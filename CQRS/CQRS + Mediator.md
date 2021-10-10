# CQRS + Mediator

- Define commands and queries as requests
- Application layer is just a series of request / response objects
- Ability to attach additional behaviour before and/or after each request, e.g. logging, validation, caching, autorisation and so on

### Key Points

- Using CQRS + MediatR simplifies your overall design
- MediatR simplifies cross cutting concerns
- Fluent Validation is useful for all validation scenarios
- AutoMapper simplifies mapping and projections
- Independent of infrastructure and data access concerns