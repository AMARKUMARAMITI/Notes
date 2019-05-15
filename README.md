# Notes
The pattern language is your guide
The microservice architecture is not a silver bullet. It has several drawbacks. Moreover, when using this architecture there are numerous issues that you must address.

The microservice architecture pattern language is a collection of patterns for applying the microservice architecture. It has two goals:

The pattern language enables you to decide whether microservices are a good fit for your application.
The pattern language enables you to use the microservice architecture successfully.

Sample of spring boot Application
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class SpringBootExampleApplication {

	public static void main(String[] args) {
		SpringApplication.run(SpringBootExampleApplication.class, args);
	}

}



@SpringBootApplication
public class CourseApiWeb {
	public static void main(String[] args) {
		SpringApplication.run(CourseApiWeb.class, args);
	}

}
