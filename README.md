# Cyber Security Acronyms

**2FA** (Two-factor Authentication)

**CIAM** (Customer Identity and Access Management)

**CIBA** (Client Initiated Backchannel Authentication)
: OpenID Connect Client Initiated Backchannel Authentication Flow is an authentication flow like OpenID Connect. However, unlike OpenID Connect, there is direct Relying Party to OpenID Provider communication without redirects through the user's browser.

**CVE** (Common Vulnerabilities and Exposures)

**CVSS** (Common Vulnerability Scoring System)

**DPoP** (Distributed Proof of Possession)
: It's a security mechanism primarily used in OAuth 2.0 and OpenID Connect protocols to enhance the security of access tokens. The DPoP mechanism works by having the client sign a unique token, called a DPoP proof, using a private key associated with the access token. When making a request to a resource server, the client includes this DPoP proof along with the access token. The resource server can then verify the DPoP proof using the public key associated with the access token, ensuring that the client is in possession of the key and thus authorized to use the token.

**FAPI** (Financial-Grade API)
: The Financial-grade API is a highly secured OAuth profile that aims to provide specific implementation guidelines for security and interoperability. The Financial-grade API security profile can be applied to APIs in any market area that requires a higher level of security than provided by standard OAuth or OpenID Connect.

**IAM** (Identity and Access Management)

**IdP** (Identity Provider)

**JWT** (JSON Web Token)

**MFA** (Multifactor Authentication)

**OIDC** (OpenID Connect)
: OpenID Connect is a simple identity layer on top of the OAuth 2.0 \[RFC6749\] protocol.

**OP** (OpenID Provider)
: OAuth 2.0 Authorization Server that is capable of Authenticating the End-User and providing Claims to a Relying Party about the Authentication event and the End-User.

**OWASP** (Open Web Application Security Project)

**RP** (Relying Party)
: OAuth 2.0 Client application requiring End-User Authentication and Claims from an OpenID Provider.

**STS** (Security Token Service)

**SP** (Service Provider)

**SWT** (Simple Web Tokens)

**TOTP** (Time-Based One-Time)
[RFC6238](https://datatracker.ietf.org/doc/html/rfc6238)
: A type of authentication mechanism commonly used in two-factor authentication (2FA) systems. TOTP relies on a shared secret key between the user and the authentication system, typically stored on a user's device (like a smartphone). This shared secret is combined with the current time to generate a unique, one-time password that changes periodically (usually every 30 seconds).
