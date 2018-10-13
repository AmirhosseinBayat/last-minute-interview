# Database
 - CAP Theorem [[1](http://www.ippon.tech/blog/use-cassandra-mongodb-hbase-accumulo-mysql/)]
 - Stored Procedures
   + Why?
   + performance/security
 - Triggers
 - Indexes
 - GROUP BY
 - PARTITION BY

# General Programming Questions
 - Immutability
 - Static vs. Dynamic Typing
 - Strong and Weak Typing
 - Big O efficiency

# Python
 - pip
 - Meta Classes
 - Generator
 - Python 2 vs 3
 - What's Lambda
 - What `zip` function does
 - Decotrators
 - Garbage Collection

# OOP
 - Interfaces (what/why)
 - Abstract Classes (what/why)
 - Polymorphism
 
# Package Managers
 - PHP: Composer
 - Erlang: Hex
 - Python: pip
 - Nodejs: npm

# Design Patterns
 - *Definition:* A general repeatable solution to a commonly occurring problem in software design.

## Examples ([link](https://github.com/kamranahmedse/design-patterns-for-humans))
 - Creational design patterns
   - Factory (Creates an instance of several derived classes)
   - Singleton (A class of which only a single instance can exist)
   - Prototype (A fully initialized instance to be copied or cloned)
   - Abstract Factory (Creates an instance of several families of classes)
 - Structural design patterns
   - Adapter (Match interfaces of different classes)
   - Decorator (Add responsibilities to objects dynamically)
   - Facade (A single class that represents an entire subsystem)
   - Proxy (An object representing another object)
 - Behavioral design patterns
   - Chain of responsibility (A way of passing a request between a chain of objects)
   - Iterator (Sequentially access the elements of a collection)
   - Mediator (Defines simplified communication between classes)
   - Null Object (Designed to act as a default value of an object)
   - Observer (A way of notifying change to a number of classes)
   - Template method (Defer the exact steps of an algorithm to a subclass)
 - Other
   - MVC
  
# Linux / Shell Scripting / Network
 - Explain each directory in `/`
 - awk
 - lsof
 - Default port numbers for HTTP/FTP/SSH/SSL/SMTP/POP3/MySQL [[1](http://support.hostgator.com/articles/commonly-used-port-numbers)]
 - What's inside `/proc`? [[1](https://twitter.com/b0rk/status/796554983810498560)]
 - What happens when you type google.com into your browser's address box and press enter? [[1](https://github.com/alex/what-happens-when)]
 - HSTS (what? how to enable?)
 - Different states of process in Linux
 - What is Virtual Memory
 - SIGINT vs SIGTERM vs SIGKILL [[1](https://www.quora.com/What-is-the-difference-between-the-SIGINT-and-SIGTERM-signals-in-Linux-What%E2%80%99s-the-difference-between-the-SIGKILL-and-SIGSTOP-signals), [2](https://major.io/2010/03/18/sigterm-vs-sigkill/)]
 - What is zombie/defunct process
 - Difference between TCP and UDP
 - Inode
   + what's the difference between `change` and `modify` timestamps in inode metadata?
 - iptables [[1](https://www.globo.tech/learning-center/wp-content/uploads/2014/05/Linux-Iptables-firewall-schema.png)]
   + Chains:
```
                FORWARD, POSTROUTING
               /
     PREROUTING
               \
                INPUT, OUTPUT
```
   + Tables: `Nat`, `Filter`, `Mangle`
   + Policies:
     * `ACCEPT`: allow through
     * `DROP`: block, no reply
   + extended polices
     * `REJECT`: block, with reply
     * `LOG`: allow, log
     * `MASQUERADE`: change the packet
   
# Security
 - SQL Injection
   - Problem
   - How to fix/prevent
 - XSS
   - Problem
   - How to fix/prevent

# Javascript
 - Context
 - Garbage Collection
 - bind vs closure vs apply vs call
 - What is a Closure? [ [1](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36#.sqm6f5d98) ]
 - Pure Function [ [1](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976#.stplb6zcz) ]
 - Asynchronous Programming [ [1](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) ]
 - What’s the Difference Between Class & Prototypal Inheritance? [ [1](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9#.t0458ztc5) ]
 - Difference between classical inheritance and prototypal inheritance [ [1](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) ]
 - What are two-way data binding and one-way data flow, and how are they different? [ [1](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) ]
 
# Git
 - Checkout
 - Rebase
 - Cherry Pick

# Development Process Frameworks
 - Scrum
 - Agile
 - Waterfall

# Tests
 - Unit Tests
 - Integration Tests
 - Functional Tests
 - Acceptance Tests
 - End-to-end Tests
