# officium

Spring Core Configuration
1.	Which annotation is used to define a Spring configuration class?
o	a) @Service
o	b) @Configuration
o	c) @Controller
o	d) @Component
o	Answer: b) @Configuration
2.	What is the default scope of a Spring bean?
o	a) Singleton
o	b) Prototype
o	c) Request
o	d) Session
o	Answer: a) Singleton
Dependency Injection
3.	Which of the following is NOT a method of Dependency Injection in Spring?
o	a) Constructor Injection
o	b) Setter Injection
o	c) Interface Injection
o	d) Field Injection
o	Answer: c) Interface Injection
4.	In Spring, which annotation is used to inject a bean by its name?
o	a) @Inject
o	b) @Autowired
o	c) @Resource
o	d) @Qualifier
o	Answer: c) @Resource
Spring IOC (Inversion of Control)
5.	What is Inversion of Control (IOC) in Spring?
o	a) A design pattern
o	b) A core feature where control over the flow of a program is transferred to a framework
o	c) An annotation for configuring beans
o	d) A method to handle exceptions
o	Answer: b) A core feature where control over the flow of a program is transferred to a framework
6.	Which of the following describes the role of the Spring IOC container?
o	a) Manages the lifecycle of Spring beans
o	b) Provides configuration metadata
o	c) Wires beans together
o	d) All of the above
o	Answer: d) All of the above
Spring AOP (Aspect-Oriented Programming)
7.	Which annotation is used to define a pointcut in Spring AOP?
o	a) @Aspect
o	b) @Pointcut
o	c) @Around
o	d) @Before
o	Answer: b) @Pointcut
8.	What is a join point in Spring AOP?
o	a) A specific point in the execution of a program where an aspect can be applied
o	b) A method in the aspect class
o	c) The configuration file for AOP
o	d) None of the above
o	Answer: a) A specific point in the execution of a program where an aspect can be applied
Spring MVC
9.	Which of the following annotations is used to map a web request to a method in Spring MVC?
o	a) @RequestMapping
o	b) @Service
o	c) @Repository
o	d) @Component
o	Answer: a) @RequestMapping
10.	Which annotation is used in Spring MVC to bind a method parameter to a web request parameter?
o	a) @RequestParam
o	b) @RequestBody
o	c) @PathVariable
o	d) @ResponseBody
o	Answer: a) @RequestParam
Annotations
11.	What does the @Autowired annotation do in Spring?
o	a) Defines a bean
o	b) Injects a bean automatically
o	c) Configures transaction management
o	d) None of the above
o	Answer: b) Injects a bean automatically
12.	Which annotation is used to handle exceptions in Spring MVC?
o	a) @ExceptionHandler
o	b) @ControllerAdvice
o	c) @RestController
o	d) Both a) and b)
o	Answer: d) Both a) and b)
Spring Bean Scope
13.	Which bean scope in Spring creates a new bean instance every time it is requested?
o	a) Singleton
o	b) Prototype
o	c) Request
o	d) Session
o	Answer: b) Prototype
14.	Which annotation is used to define a bean's scope in Spring?
o	a) @Scope
o	b) @Qualifier
o	c) @Service
o	d) @Component
o	Answer: a) @Scope


Spring Core Configuration
15.	Which method in a @Configuration annotated class returns a bean that is managed by Spring?
o	a) @Autowired
o	b) @Bean
o	c) @Component
o	d) @Import
o	Answer: b) @Bean
16.	What is the purpose of the @ComponentScan annotation in Spring?
o	a) To scan for beans in the classpath
o	b) To specify the base packages to scan for annotated components
o	c) To configure property sources
o	d) To enable AOP
o	Answer: b) To specify the base packages to scan for annotated components
Dependency Injection
17.	Which of the following annotations can be used to inject values from a properties file into a Spring bean?
o	a) @Value
o	b) @Inject
o	c) @Resource
o	d) @PropertySource
o	Answer: a) @Value
18.	Which Spring annotation would you use to inject a collection of beans into a single property?
o	a) @Autowired
o	b) @Qualifier
o	c) @Resource
o	d) @Autowired with List
o	Answer: d) @Autowired with List
Spring IOC (Inversion of Control)
19.	Which interface must be implemented for a class to act as a factory for Spring beans?
o	a) FactoryBean
o	b) BeanFactory
o	c) ApplicationContext
o	d) BeanDefinition
o	Answer: a) FactoryBean
20.	What is the primary difference between BeanFactory and ApplicationContext in Spring?
o	a) ApplicationContext includes more enterprise-specific functionality
o	b) BeanFactory is deprecated
o	c) BeanFactory provides more features than ApplicationContext
o	d) ApplicationContext does not support internationalization
o	Answer: a) ApplicationContext includes more enterprise-specific functionality
Spring AOP (Aspect-Oriented Programming)
21.	Which of the following is NOT a type of advice in Spring AOP?
o	a) Before
o	b) Around
o	c) After
o	d) Instead
o	Answer: d) Instead
22.	Which annotation is used to indicate that a class is an aspect in Spring AOP?
o	a) @Aspect
o	b) @Configuration
o	c) @Controller
o	d) @Service
o	Answer: a) @Aspect
Spring MVC
23.	Which annotation is used in Spring MVC to map a request parameter to a method argument, assuming that the parameter name and the argument name are the same?
o	a) @RequestParam
o	b) @RequestAttribute
o	c) @RequestHeader
o	d) @RequestPart
o	Answer: a) @RequestParam
24.	In Spring MVC, which annotation is used to indicate that a method parameter should be bound to a URI template variable?
o	a) @RequestParam
o	b) @PathVariable
o	c) @RequestBody
o	d) @ModelAttribute
o	Answer: b) @PathVariable
Annotations
25.	Which annotation in Spring allows you to define transactional behavior on a method?
o	a) @Transactional
o	b) @Service
o	c) @Repository
o	d) @Controller
o	Answer: a) @Transactional
26.	Which annotation is used to apply cross-cutting concerns in Spring?
o	a) @Aspect
o	b) @Component
o	c) @Around
o	d) @EnableAspectJAutoProxy
o	Answer: d) @EnableAspectJAutoProxy
Spring Bean Scope
27.	Which of the following scopes is NOT available in a standalone Spring application?
o	a) Singleton
o	b) Prototype
o	c) Request
o	d) Session
o	Answer: c) Request (available in web context)
28.	Which bean scope should be used for a bean that should be created once per HTTP session in a web application?
o	a) Singleton
o	b) Prototype
o	c) Request
o	d) Session
o	Answer: d) Session
Additional Questions
29.	Which method of the ApplicationContext is used to publish an application event to all registered listeners?
o	a) publishEvent
o	b) registerEvent
o	c) fireEvent
o	d) sendEvent
o	Answer: a) publishEvent
30.	Which annotation in Spring is used to handle HTTP PUT requests?
o	a) @PostMapping
o	b) @GetMapping
o	c) @PutMapping
o	d) @DeleteMapping
o	Answer: c) @PutMapping
31.	Which of the following best describes Spring Boot?
o	a) A part of the Spring Framework focused on simplifying the development of new Spring applications
o	b) A replacement for the Spring Framework
o	c) An IDE for developing Spring applications
o	d) A database management tool
o	Answer: a) A part of the Spring Framework focused on simplifying the development of new Spring applications
32.	In Spring Boot, which file is used to configure application properties?
o	a) application.xml
o	b) application.properties
o	c) spring-config.yml
o	d) settings.json
o	Answer: b) application.properties
33.	Which annotation is used in Spring Boot to enable auto-configuration?
o	a) @EnableAutoConfiguration
o	b) @SpringBootApplication
o	c) @ComponentScan
o	d) @Configuration
o	Answer: a) @EnableAutoConfiguration


Spring Core Configuration
•	@Configuration: Indicates that a class declares one or more @Bean methods.
•	@Bean: Indicates that a method produces a bean to be managed by the Spring container.
•	@ComponentScan: Configures which packages to scan for components.
•	ApplicationContext: Central interface to provide configuration for an application.
Dependency Injection
•	Constructor Injection: Dependencies are provided through a class constructor.
•	Setter Injection: Dependencies are provided through setter methods.
•	Field Injection: Dependencies are injected directly into fields.
•	@Autowired: Automatically wires beans by type.
•	@Qualifier: Specifies the exact bean to wire when multiple beans of the same type exist.
•	@Resource: JSR-250 annotation for dependency injection by name.
Spring IOC (Inversion of Control)
•	BeanFactory: Basic container that provides basic functionality for dependency injection.
•	ApplicationContext: Extends BeanFactory and provides more enterprise-specific functionality.
•	FactoryBean: Allows custom instantiation logic in beans.
•	@Component: Indicates a class as a Spring component.
•	@Service: Indicates a class as a service layer component.
•	@Repository: Indicates a class as a data access layer component.
Spring AOP (Aspect-Oriented Programming)
•	@Aspect: Declares a class as an aspect.
•	@Pointcut: Declares a pointcut, a predicate that matches join points.
•	@Before: Advice that runs before a matched join point.
•	@After: Advice that runs after a matched join point.
•	@Around: Advice that surrounds a matched join point.
•	@AfterReturning: Advice that runs after a matched join point completes normally.
•	@AfterThrowing: Advice that runs if a matched join point throws an exception.
Spring MVC
•	@Controller: Indicates a class as a web controller.
•	@RequestMapping: Maps web requests to handler methods of MVC and REST controllers.
•	@GetMapping: Shortcut for @RequestMapping(method = RequestMethod.GET).
•	@PostMapping: Shortcut for @RequestMapping(method = RequestMethod.POST).
•	@PutMapping: Shortcut for @RequestMapping(method = RequestMethod.PUT).
•	@DeleteMapping: Shortcut for @RequestMapping(method = RequestMethod.DELETE).
•	@RequestParam: Binds a request parameter to a method argument.
•	@PathVariable: Binds a URI template variable to a method argument.
•	@ModelAttribute: Binds a method parameter or method return value to a named model attribute.
Annotations
•	@Autowired: Automatically wires dependencies by type.
•	@Qualifier: Used in conjunction with @Autowired to specify the exact bean to inject.
•	@Resource: Injects dependencies by name.
•	@Value: Injects values from properties files.
•	@Component: Indicates a class as a Spring component.
•	@Service: Indicates a service layer component.
•	@Repository: Indicates a data access layer component.
•	@Controller: Indicates a web controller.
•	@RestController: Indicates a RESTful web controller.
•	@ExceptionHandler: Handles exceptions thrown by request handling methods.
•	@ControllerAdvice: Allows the definition of global exception handling.
Spring Bean Scope
•	Singleton: One shared instance per Spring IoC container.
•	Prototype: A new instance each time it is requested.
•	Request: A single instance for each HTTP request (web applications).
•	Session: A single instance for an HTTP session (web applications).
•	Global Session: A single instance for a global HTTP session (web applications, typically in portlets).
Additional Points on Spring Boot
•	@SpringBootApplication: Combines @Configuration, @EnableAutoConfiguration, and @ComponentScan with their default attributes.
•	application.properties: File used for configuring application properties.
•	Spring Boot Starters: Pre-configured templates for setting up various Spring technologies.
•	Spring Boot Auto-Configuration: Automatically configures your Spring application based on the jar dependencies you have added.
•	Spring Initializr: Web-based tool for generating Spring Boot project structures.
•	Spring Boot Actuator: Provides production-ready features such as monitoring and management over HTTP.

Spring Core Configuration
Spring Core Configuration involves setting up the foundational aspects of a Spring application. It uses @Configuration classes to define beans with the @Bean annotation, which are managed by the Spring container. The @ComponentScan annotation specifies the packages to scan for components, enabling Spring to detect and register beans automatically. The ApplicationContext interface provides a central point for configuration, managing the lifecycle of beans, and facilitating dependency injection.
Dependency Injection
Dependency Injection (DI) is a core principle of Spring that allows the framework to manage the dependencies of objects. This can be achieved through constructor injection, setter injection, or field injection. The @Autowired annotation is commonly used to inject dependencies automatically by type. The @Qualifier annotation specifies which bean to inject when multiple beans of the same type exist. This decouples the creation of objects from their usage, enhancing modularity and testability.
Spring IOC (Inversion of Control)
Inversion of Control (IOC) in Spring is a design principle where the control of object creation and lifecycle management is transferred to the Spring container. The BeanFactory and ApplicationContext interfaces are key to this process, with ApplicationContext providing additional enterprise-specific functionality. Spring's IOC container uses dependency injection to manage object dependencies, promoting loose coupling and easier testing.
Spring AOP (Aspect-Oriented Programming)
Aspect-Oriented Programming (AOP) in Spring allows for the separation of cross-cutting concerns, such as logging and transaction management, from the business logic. Aspects are defined using the @Aspect annotation, and pointcuts are declared with @Pointcut to specify join points in the application flow. Advice annotations like @Before, @After, and @Around define actions to be taken at these join points, facilitating modular and reusable code for concerns that cut across multiple points of an application.
Spring MVC
Spring MVC is a framework for building web applications using the Model-View-Controller design pattern. Controllers, marked with the @Controller annotation, handle web requests and return views. Request mappings are defined using @RequestMapping, @GetMapping, @PostMapping, etc., to route requests to the appropriate handler methods. Annotations like @RequestParam and @PathVariable bind request parameters and path variables to method arguments, making it easy to handle and process web requests.
Annotations
Spring's extensive use of annotations simplifies configuration and reduces the need for XML. Annotations like @Autowired for dependency injection, @Component for defining beans, and @Service, @Repository, and @Controller for specific layers of an application are fundamental. @Transactional manages transaction boundaries, while @RestController combines @Controller and @ResponseBody for RESTful web services. These annotations streamline the development process and improve readability.
Spring Bean Scope
Spring Bean Scope defines the lifecycle and visibility of beans in the Spring container. The default scope is Singleton, where one instance of a bean is created per container. Other scopes include Prototype (a new instance for each request), Request (one instance per HTTP request), Session (one instance per HTTP session), and Global Session (used in portlet contexts). These scopes allow developers to manage bean instances according to their application requirements effectively.
Additional Points on Spring Boot
Spring Boot simplifies Spring application development by offering pre-configured templates (starters) and reducing boilerplate code. It uses @SpringBootApplication to enable auto-configuration and component scanning. Configuration properties are managed through the application.properties file. Spring Boot Actuator provides monitoring and management features, making it easier to develop production-ready applications. Spring Initializr is a web-based tool that generates project structures, further simplifying the setup process.
These explanations encapsulate the essential aspects of each topic within the Spring Boot framework, providing a foundational understanding for further exploration.

