
# Reading Note 8

1.	When is Basic Authorization used vs. Bearer Authorization?
-	Basic Authorization is used by prompting a Web site visitor for a username and password. This method is widely used because most browsers and Web servers support it.
-	Bearer Authorization is used when a client is making a requests to protected resources. It is also known as bearer token which allows developers to have a more secure point of entry for using some APIs, and are one of the core features of authentication, which uses a Bearer Token, is also known as application-only authentication.

2.	What does the JSON Web Token package do? 
-	JSON Web Token package is used to create access tokens for an application and then the server generates a token that certifies the user identity, and sends it to the client which is defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

3.	What considerations should we make when creating and storing a SECRET?
-	Never store unencrypted secrets in .git repositories. Avoid git add * commands on git. Add sensitive files in .gitignore. Don't rely on code reviews to discover secrets. Don't share your secrets unencrypted in messaging systems like slack. Store secrets safely. Restrict API access and permissions.



## Vocabulary Terms ##
- Encryption is the process of converting information or data into a code, especially to prevent unauthorized access. In other word a way to hash it. 

- Token is a single element of a programming language. There are five categories of tokens: 1) constants, 2) identifiers, 3) operators, 4) separators, and 5) reserved words.

- Bearer is is an opaque string, not intended to have any meaning to clients using it. 

- JSON Web Token is an Internet proposed standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key.

## Reading Reference
- https://www.google.com/search?ei=6YlRYOPOMpS_0PEP29-NsAs&q=creating+and+storing+a+SECRET&oq=creating+and+storing+a+SECRET&gs_lcp=Cgdnd3Mtd2l6EAwyBQghEKABUNblGVjW5RlgooEaaANwAngAgAGbAYgB_AGSAQMxLjGYAQCgAQGgAQKqAQdnd3Mtd2l6sAEAwAEB&sclient=gws-wiz&ved=0ahUKEwij55D1wrbvAhWUHzQIHdtvA7YQ4dUDCA4
- www.google.com


