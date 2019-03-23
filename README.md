# SpringMVC-Validator
SpringMVC-Validator

Spring MVC Framework supports JSR-303 specs by default and all we need is to add JSR-303 and it’s implementation dependencies in Spring MVC application. Spring also provides @Validator annotation and BindingResult class through which we can get the errors raised by Validator implementation in the controller request handler method.

We can create our custom validator implementations by two ways – first one is to create an annotation that confirms to the JSR-303 specs and implement it’s Validator class. Second approach is to implement the org.springframework.validation.Validator interface and add set it as validator in the Controller class using @InitBinder annotation.

Below url Can be used for testing the application...

http://localhost:8080/SpringMVCValidator//cust/save
http://localhost:8080/SpringMVCValidator//emp/save

ForMore Details: https://www.journaldev.com/2668/spring-validation-example-mvc-validator

