# Incomplete Mediation

Authorization is usually the key security factor of a software product. Not every resources should be reached or consumed by all users.

There are various cases where lack of authorization might allow attackers to access resources where they shouldn't. 

For example, usually GET requests, triggered by generic URLs, are checked against authorization code, which applies the access rules, very well. However, these same access rules are usually forgotten against the relevant POST actions. However, it is rather easy for an attacker to forge a POST request.

Another example to incomplete mediation anti-pattern would be to forget to apply authorization checks against administrator interfaces or requests triggered by native mobile phone applications (who would or could fool around with mobile applications, right? wrong.).
