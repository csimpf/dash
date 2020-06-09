# Security Considerations
I have limited knowledge of web security, so here's a list off the top of my head, of security considerations:
- Access to the page from others in my network
  I initially pictured an easy to reach URL like `my.dash` that I could access straight away in my network, but that would mean anybody could see my emails.
  I should look into how I can limit access on a per-computer basis. I've heard of OAuth2, maybe this would be helpful.
  Maybe a password is required
- Auth keys
  Any authorisation keys *must* be used in a way that they are not required to be pushed to the repository, as this is a public repo. No "passwords in configs" any more.
- Code
  Anything in this code should not be able to identify me.
