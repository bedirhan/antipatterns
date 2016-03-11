# Widening Whitelists Without Precautions

Whitelisting is one of the best strategies of input validation since it means to accept the expected only. Not enough to make an application completely secure [1], it helps a lot and much, much more than blacklisting.

For example, it is easy to write a hardened regular expression for a username field, where the input comes from the user. It may as well be easy to write a nice secure regular expression for a comment field, too. However as the business requirements evolve more characters might be wanted to be in the safe list. The immediate response to this new requirement will be to include the "extra" characters in the regular expression. 

An uncontrolled (without applying appropriate output encodings) widening of the white list regular expression will wipe out its security effectiveness.

# References

[1] www.guvenlikod.com/loti
