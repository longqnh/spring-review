# Java Spring Review for Interview

## Spring
1. Dependency Injection:
    - A technique of creating software in which objects do not create their dependencies on itself, 
      instead objects declare dependencies that they need, and it is external object job or framework job to provide 
      concrete dependencies to objects
    - Types of Dependency Injection:
        - Construction Injection
        - Setter Injection
        - Interface Injection
    - Advantages of using dependency injection:
        - Increase code reusability
        - Increase code readability
        - Increase code maintainability
        - Increase code testability
        - Reduce coupling
        - Increase cohesion


2. Application Context:
    - A central part of Spring application, holds bean definition and contains registry of application components.
    - Application Context:
        - Init Beans
        - Configures Beans
        - Assemblies Beans
        - Manages Beans LifeCycle
        - Is a bean factory
        - Is a resource loader
        - Has ability to push events to registered even listeners
        - Exposes environment which allows resolving properties


3. Spring container lifecycle:
    - Application started
    - Spring container is created
    - Containers read configuration
    - Beans definitions are created from configuration
    - BeanFactoryPostProcessors are processing bean definition
    - Instances of Spring Beans are created
    - Spring Beans are configured and assembled - resolve properly value and inject dependency
    - BeanPostProcessor are called
    - Application runs
    - Application gets shutdown
    - Spring Context is closed
    - Destruction callbacks are invoked

## Spring Boot

