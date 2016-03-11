# Pardon The Malintent

Exception handling is a vital way of providing fail-safe flows through out the source code. Unexpected conditions are caught at runtime and appropriate actions are taken through exception handlers. Logging, notifications, releasing resources are some of the actions taken at the exception handler code.

The same care is usually forgotten to be applied when it comes to producing alerts when there's a hacking attempt caught by the code. For example, in an XML parsing code, a DTD processing or an undefined external entity exception most likely mean a hacker attempting to trigger a XXE [1].

A developer should log and produce a notification when an attacker starts to play around with the product. Even more blocking actions might be taken. Instead of WAFs, the source code itself is a much better playground for such actions because of several factors including impedance mismatch.

# References

[1] https://www.owasp.org/index.php/XML_External_Entity_(XXE)_Processing


