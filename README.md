# ldapjwt
Spring Boot 2.x + openLDAP authentication + REST API + JWT

This Project Demonstrates a working example of authentication using openLDAP in Spring boot 2.x + REST API + JWT toekn
You can read my blog for more information : https://devcrutch.com/2020/09/15/how-to-create-jwt-token-using-ldap-and-spring-boot-part-1/

Login Via REST 
POST:http://localhost:8080/api/login

Request Body 

{
"username" : "hero78",
"password" : "admin123"
}

LDAP Local Instance
http://localhost/phpLDAPadmin-1.2.6.4/htdocs/cmd.php 
LDAP Credentials On Local 
username:cnadmin,dc=example,dc=com
password:f43K...... /admin123