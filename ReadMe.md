Background

A set of services and tools for sending emails in a Spring Boot application using plain text, html or a template engine to generate dynamic content.

The Spring Boot project relies on a spring-boot-starter-mail module  that provides the core features (e.g. sending emails).

In you application.properties set the configuration needed to send the emails, e.g. if you want to send the emails using a Gmail account you can set:

spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=firstname.surname@gmail.com
spring.mail.password=V3rY_$tr0ng_P@$Sw0rd
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
spring.mail.properties.mail.smtp.starttls.required=true



To get it working properly using Google Mail, Please go to https://myaccount.google.com/secureaccount first and set "Allow less secure apps" to "ON".