# Software Architecture Notes & Resources

## Generic Resources

 - [Martin Fowler - Software Design in the 21st Century](https://www.thoughtworks.com/talks/software-development-21st-century-xconf-europe-2014)

## Domain Design, Domain-Driven Architecture

### Notes

 - "Use objects as consistency boundaries." - Mathias Verraes
 - "If multiple rules can apply to an object, there are in different
   contexts." - Mathias Verraes
 - "In essence the problem with anemic domain models is that they incur
    all of the costs of a domain model, without yielding any of the
    benefits." - Martin Fowler
 - "Commands" are typically use-cases (But not in CQRS)
 - "DRY is not about code duplication, but a single source of truth" - Mathias Verraes
 - 



### Resources

 - Articles
  - [Martin Fowler - Bounded Context](https://martinfowler.com/bliki/BoundedContext.html)
  - [Martin Fowler - UbiquitousLanguage](https://martinfowler.com/bliki/UbiquitousLanguage.html)
 - Community
  - [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp)
 - Video
  - [Implementing Domain-Driven Design, 1st Edition, by Vaughn Vernon (via Amazon)](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)
  - [PHP UK Conference 2014 - Mathias Verraes - Unbreakable Domain Models](https://www.youtube.com/watch?v=ZJ63ltuwMaE&feature=youtu.be)

## Hexagonal

 - The key point is to make sure to decouple concerns.
 - Hexagonal Layers, according to Chris Fidao (Fidelper)
    - Domain
    - Application
    - Framework
    - Infrastructure
    - Persistence
 - "Hexagonal Architecture espouses a one-way flow of dependencies: From
   the outside, in. The Domain Layer (the inner-most layer) should not
   depend on layers outside of it." - Fidelper
 - "At the boundary of our Domain Layer, we find definitions in how the
   outside layer (the Application Layer) can communicate with the domain
   objects/entities found in the Domain Layer." - Fideloper / Chris Fidao
 - The interface is the port, and the implementations of it are the
   adapters to that port.
 - "A way to decouple your code in different layers -- a way to
   encapsulate variances -- a way to encapsulate what changes in your
   code" - Fideloper / Chris Fidao

### Resources

 - Code Examples
   - [github: garethp/hexagonal-ddd: a sample todo app](https://github.com/Garethp/hexagonal-ddd)
   - [webdevilepers: ddd repositories with doctrine orm/odm in symfony](http://blog.webdevilopers.net/domain-driven-design-repositories-with-doctrine-orm-and-odm-in-symfony/)
   - [github: fideveloper/hexagonal-php](https://github.com/fideloper/hexagonal-php)
   -
 - Video
   - [DrupalCon Amsterdam 2014: Models & Service Layers; Hemoglobin & Hobgoblins](http://www.youtube.com/watch?v=ajhqScWECMo&t=1519s)
   - [Chris Fidao - Hexagonal Architecture](https://www.youtube.com/watch?v=6SBjKOwVq0o)

## Microservices

 - "In short, the microservice architectural style is an approach to
   developing a single application as a suite of small services, each
   running in its own process and communicating with lightweight
   mechanisms, often an HTTP resource API." - Martin Fowler
 - "The microservice approach to division is different, splitting up
   into services organized around business capability." - Martin Fowler
 - "The microservice community favours an alternative approach: smart
   endpoints and dumb pipes. Applications built from microservices aim
   to be as decoupled and as cohesive as possible - they own their own
   domain logic" - Martin Fowler

### Resources

#### Articles

 - [Martin Fowler - Microservices](https://martinfowler.com/articles/microservices.html)



