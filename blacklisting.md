# Blacklisting

There are a handful of input validation strategies that a developer can utilize; blacklisting, normalization, whitelisting, encoding and such. However, the first strategy usually that comes to mind against a security problem is unfortunately the blacklisting.

It seems to be the easiest and non-intrusive way of all the input validation strategies. However, it turns out to be the worst for security.

There are various sites for hackers that list plethora of security control bypass payloads. It is really hard to form a solid, hackproof blacklist since the applications get more complex and the attackers/testers are smart when it comes to bypassing the filters [1].

# References

[1] https://packetstormsecurity.com/files/112152/Cross-Site-Scripting-Payloads.html
