### General
* encapsulate concept that varies
* SOLID
 * [in pictures](http://lostechies.com/derickbailey/2009/02/11/solid-development-principles-in-motivational-pictures)
 * SRP - Single responsibility principle
 * OCP - Open/closed principle
 * LSP - Liskov substitution principle (square vs rectangle)
 * ISP - Interface segregation principle (worker, person, robot example)
 * DIP - Dependency inversion principle (http://lostechies.com/gabrielschenker/2009/01/30/the-dependency-inversion-principle/)

### Inheritance
* favor object composition over class inheritance
* defining a subclass requires an in-depth understanding of the parent class (ex overriding one method may need override another)
* can lead to an explosion of classes, because you might have to introduce many new subclasses for even a simple extension

### Key OO design considerations
* encapsulation
* granularity
* dependency
* flexibility
* performance
* evolution
* reusability
* decomposition

### Desing patterns
* singleton
* abstract factory
* factory method
* template
* decorator
* adapter
* proxy
* bridge
* facade
* composite
* command
* observer
* template
* state
* strategy
* mvc

* object pool
* thread pool
* connection pool
* mediator

* [decorator vs adapter vs bridge vs facade](http://stackoverflow.com/questions/350404/how-do-the-proxy-decorator-adapter-and-bridge-patterns-differ)

#### Categorisation by Gamma et al. from 2009
* Core: Composite, Strategy, State, Command, Iterator, Proxy, Template Method, Facade
* Creational: Factory, Prototype, Builder, Dependency Injection
* Peripheral: Abstract Factory, Visitor, Decorator, Mediator, Type Object, Null Object, Extension Object
* Other: Flyweight, Interpreter



### API Design
* consistency, information hiding, loose coupling
* model the problem domain
* model key objects
* be minimally complete
* information hiding: physical and logical
* class should define what to do not how its done
* beware of extra generality - may never be needed, if it's needed you may know more about problem later, it is easier to add to simple api than complex one
* orthogonality
* consistency
* what can be executed in parallel? - design for parallelism; UML sequence diagrams
* adaptation (configuration, problem domain scripting)
* Demeter Law
* minimize links (and complexity)
* resources balancing

### Singleton
* API Design for C++ 3.2.5

### Static factory method
* Consider static factory method(s) instead of constructors
* They have names
* Objects can be cached
* Return type co-variance possible

### Code reuse
A fundamental trade-off in code design: reusing code saves effort and avoids bugs, but makes the reused code harder to change later
