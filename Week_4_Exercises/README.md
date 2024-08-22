WEEK 4 EXERCISES 

Exercise 1: Online Bookstore - Setting Up RESTful Services
Business Scenario: 
You are tasked with developing a RESTful service for an online bookstore. The service will manage books, authors, and customers.
Instructions:
1.	Setup Spring Boot Project:
o	Initialize a new Spring Boot project named BookstoreAPI.
o	Add dependencies: Spring Web, Spring Boot DevTools, Lombok.
2.	Project Structure:
o	Familiarize yourself with the generated project structure.
3.	What's New in Spring Boot 3:
o	Explore and document the new features introduced in Spring Boot 3.

Exercise 2: Online Bookstore - Creating Basic REST Controllers
Business Scenario: 
Implement RESTful endpoints to manage books.
Instructions:
1.	Create Book Controller:
o	Define a BookController class with request mappings for /books.
2.	Handle HTTP Methods:
o	Implement methods to handle GET, POST, PUT, and DELETE requests.
3.	Return JSON Responses:
o	Ensure the controller returns JSON responses.
o	Define the Book entity with attributes like id, title, author, price, and isbn.

Exercise 3: Online Bookstore - Handling Path Variables and Query Parameters
Business Scenario: 
Enhance the book management endpoints to handle dynamic URLs and query parameters.
Instructions:
1.	Path Variables:
o	Implement an endpoint to fetch a book by its ID using a path variable.
2.	Query Parameters:
o	Implement an endpoint to filter books based on query parameters like title and author.

Exercise 4: Online Bookstore - Processing Request Body and Form Data
Business Scenario: 
Create endpoints to accept and process JSON request bodies and form data for customer registrations.
Instructions:
1.	Request Body:
o	Implement a POST endpoint to create a new customer by accepting a JSON request body.
2.	Form Data:
o	Implement an endpoint to process form data for customer registrations.

Exercise 5: Online Bookstore - Customizing Response Status and Headers
Business Scenario: 
Customize the HTTP response status and headers for the book management endpoints.
Instructions:
1.	Response Status:
o	Use @ResponseStatus to customize HTTP status codes for your endpoints.
2.	Custom Headers:
o	Add custom headers to the response using ResponseEntity.

Exercise 6: Online Bookstore - Exception Handling in REST Controllers
Business Scenario: 
Implement a global exception handling mechanism for the bookstore RESTful services.
Instructions:
1.	Global Exception Handler:
o	Create a GlobalExceptionHandler class using @ControllerAdvice.
o	Define methods to handle various exceptions and return appropriate HTTP status codes.

Exercise 7: Online Bookstore - Introduction to Data Transfer Objects (DTOs)
Business Scenario: 
Use DTOs to transfer data between the client and server for books and customers.
Instructions:
1.	Create DTOs:
o	Define BookDTO and CustomerDTO classes.
2.	Mapping Entities to DTOs:
o	Use a library like MapStruct or ModelMapper to map entities to DTOs and vice versa.
3.	Custom Serialization/Deserialization:
o	Customize JSON serialization and deserialization using Jackson annotations.
