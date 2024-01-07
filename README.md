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
@RestController
@RequestMapping
@GetMapping
@PostMapping
@PutMapping
@DeleteMapping
@RequestBody 
@PathVariable
@RequestParam
@ControllerAdvice & @ExceptionHandler

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
