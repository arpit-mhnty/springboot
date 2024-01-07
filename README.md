# springboot

### anotations and it's use
```
Spring Boot Main annotations
--------------------------------------------------
1. @SpringBootApplication
2. @ComponentScan
3. @EanbleAutoConfiguration
4. @Configuration

Stereotype annotation
----------------------------------------
1.  @Component - it used to mark class as spring bean
2.  @Service- it make where u find business logic
3.  @RestController / @Controller-it hander class to handle web rewquest
4.  @Repository - it class hwichused to call datasource(connection with physical datasource)

Spring Core related Annotations:
----------------------------------------------------
@Configuration
@Bean
@Autowired 
@Qualifier 
@Lazy 
@Value 
@PropertySource
@ConfigurationProperties 
@Profile
@Scope

REST API related Annotations:
------------------------------------------------
@RestController -it create restful webservice it basically merge of @ResponseBody(it return valuein jsonormlformat) and @controller
@RequestMapping- it keep on method used to handle specfy method
@GetMapping- it specfialisefor handle get request
@PostMapping- it specialise for handle post request(creating data)
@PutMapping- it specialise for update whole data not like patch which partially update
@DeleteMapping- it delet the data from db
@RequestBody- this anotaion(metadata) convert to a method body(basicaly a object)pojo-plain old java objects
@PathVariable - map the varaiable from endpoint to method argument it got from url path
@RequestParam- itget valuefrom url butuse ? localhost:02/data?id=292 it got from url parameter but pathvariable got{id} basically localhost/101
@ControllerAdvice-it's global exceptionhandeler that handle exctionfeffciantly
@ExceptionHandler-it handle specfic exction it is method return response body with status code

Spring Data JPA related annotations:
------------------------------------------------------------
@Entity
@Table
@Column
@Transactional 
Entity class relationships 
@OnetoOne 
@OnetoMany 
@ManytoOne
@ManytoMany
```
