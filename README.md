# An Angular 6 application that calls RESTful Web service

> The Angular application will use Angular Http API for CRUD operation and it will be single page application that will perform CRUD operation. On the basis of REST web service response HTTP status code, the Angular application will display messages for success and failure of CRUD operation. 

## HTTP URLs, Methods and Response Status Code for CRUD Operation

We will use following HTTP URLs, methods and response status code for CRUD operation in our example. 
>1. Create : 
HTTP Method: POST, URL: /user/article 
Angular API: Http.post() 
HTTP Response Status Code: 201 CREATED and 409 CONFLICT 

>2. Read : 
> HTTP Method: GET, URL: /user/article?id={id} (Fetches article by id) 
> HTTP Method: GET, URL: /user/all-articles (Fetches all articles) 
> Angular API: Http.get() 
> HTTP Response Status Code: 200 OK 

>3. Update : 
HTTP Method: PUT, URL: /user/article 
Angular API: Http.put() 
HTTP Response Status Code: 200 OK 

>4. Delete : 
HTTP Method: DELETE, URL: /user/article?id={id} 
Angular API: Http.delete() 
HTTP Response Status Code: 204 NO CONTENT

## Steps
>1.	install the Node.js JavaScript runtime and npm (the Node.js package manager) and you can get them from https://nodejs.org/en/download/
Tip: To test that you have Node.js and npm correctly installed on your machine, you can type node --version and npm --version.
>2.	install the Angular CLI, in a terminal or command prompt type:
npm install -g @angular/cli
>3.	create a new Angular application by typing:
ng new articles-client
>4.	run the Angular application by navigating to the new folder and typing ng serve to start the web server and open the application in a browser, "Welcome to app!!" will be on http://localhost:4200 page
cd articles-client
ng serve
>5.	open your Angular application in VS Code, open another terminal (or command prompt) and navigate to the my-app folder and type code .
>cd articles-client
>code .
 
>6.	work on 
app.components.ts
article.component.css
article.component.html
article.component.ts
article.module.ts
article.service.ts
article.ts
>7.	Run REST Web Service using Spring Boot
>8.	Our Angular application is ready on the following URL.
http://localhost:4200

## Reference
>1. Using Angular in VS Code (https://code.visualstudio.com/docs/nodejs/angular-tutorial)
>2. Spring Boot REST + Angular 2/4 + JPA + Hibernate + MySQL CRUD Example (https://www.concretepage.com/spring-boot/spring-boot-rest-angular-2-jpa-hibernate-mysql-crud-example)


