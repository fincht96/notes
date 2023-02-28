Clean Architecture is a software architecture pattern that focuses on creating a modular and maintainable software application. It emphasizes the separation of concerns and the independence of layers, making the codebase easier to test, maintain, and evolve over time. The Clean Architecture pattern consists of several layers, which are as follows:

<ol>
  <li>
    <b>Presentation layer:</b> This layer represents the user interface of the application, such as a web interface or a mobile app. It is responsible for handling user input, presenting data to the user, and receiving feedback from the user. The presentation layer communicates with the application layer to access the business logic and data of the system.
  </li>

 <li>
<b>Application layer:</b> This layer contains the use cases and business logic of the application. It is responsible for coordinating and executing the use cases defined in the Domain layer. The application layer communicates with the Domain layer to access the entities, value objects, and interfaces of the system.
     </li>
  
 <li>
<b>Domain layer:</b> This layer represents the core of the application and contains the business rules and domain objects of the system. It defines the entities, value objects, and interfaces that interact with the system's data. The Domain layer is independent of any external infrastructure or technology and can be tested independently of the rest of the application.
  </li>
 <li>
<b>Infrastructure layer:</b> This layer contains the implementation details of the system, such as the database, network communication, and external libraries or services. It is responsible for providing the interfaces and concrete implementations of the interfaces defined in the Domain layer. The infrastructure layer communicates with the Domain layer to provide data and services to the application layer.
  </li>
</ol>
  
The Clean Architecture pattern emphasizes the independence and separation of these layers to achieve a modular and maintainable codebase. Each layer should have clear responsibilities and dependencies on other layers should be minimized. This architecture also allows for easy testing and swapping out of components, making it more flexible and adaptable to changing requirements.
