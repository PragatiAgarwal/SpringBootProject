# SpringBootProject
Important Sprint properties : Java Brains : https://www.youtube.com/watch?v=dpgwqStAj3k

Important Spring Annotations : Java Brains :  https://www.youtube.com/watch?v=wf70Hs-aCcI&t=3s

  @Component : Class level annotation. Spring manages such classes and creates bean and provide dependency injection, etc.
  @Service, @Repostiory, @Controller -> Class level annotation. Tells spring that a class is special type and more than just a component.
  @Autowired : Field level annotation, method level annotation(setter method)
  @Value : find the value of a certain property from property file and inject the value. Promotes loose copling, helps in configurations and externalize the configuration. It works only with Spring beans
    spEL
  @Configuration : contains setup and wiing logic. can be used with @ComponentScan("")
  @Bean : Method level annotation -> Tells spring execute this method and whatever this method returns take that instance and make that spring bean. used in combo of @Configuration Different from annotating the     
  class. see video for reason
  @Trasactional : 
  @RequestMapping : can be annotated on class level or method level. Keeps controller clean and maps the web http request based on http method and path in your controller class
    @GetMapping, @PostMapping, etc.
  @RestController -> help to return the controller a json response. Combo of @Controller + @responseBody
  @SpringBootApplication : Bootstrapping spring boot application
