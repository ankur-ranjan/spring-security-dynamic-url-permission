# spring-security-dynamic-url-permission
In Spring Security, the intercept-url pattern permissions are either configured in the application context xml or the annotated context class file, for example 

    <security:intercept-url pattern="/admin/**" access="hasRole('ROLE_ADMIN')"/>

But, what if there is a business requirement that the URL pattern and the corresponding role permission be picked from a database.
The sample project (WIP) demonstrates how to dynamically pick the url mapping and corresponding role permission from database in Spring Security
.

