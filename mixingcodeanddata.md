# Mixing Code And Data

Maybe the worst anti-pattern in software security are the string concatenation operators or methods. Solving a listing of books searched by an end-user utilizing SQL statements dynamically formed by supplied search criteria is asking for a disaster [1].

Injection types of security weaknesses all stem from mixing the user controlled data with the code. There aren't many APIs provided by the frameworks or programming languages that have the ability to keep the data and code separate till the code gets interpreted. Prepared statements are one of the best examples of these lacking APIs. 

Appropriate input validation strategies should be applied before uncontrolled mixing of data and code.

# References

[1] https://www.owasp.org/index.php/SQL_Injection
