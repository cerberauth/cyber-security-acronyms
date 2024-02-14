# Cyber Security Acronyms

<dl>
    <dt><strong>2FA</strong> (Two-factor Authentication)</dt>
</dl>

<dl>
    <dt><strong>CIAM</strong> (Customer Identity and Access Management)</dt>
</dl>

<dl>
    <dt><strong>CIBA</strong> (Client Initiated Backchannel Authentication)</dt>
    <dd>OpenID Connect Client Initiated Backchannel Authentication Flow is an authentication flow like OpenID Connect. However, unlike OpenID Connect, there is direct Relying Party to OpenID Provider communication without redirects through the user's browser.</dd>
</dl>

<dl>
    <dt><strong>CVE</strong> (Common Vulnerabilities and Exposures)</dt>
</dl>

<dl>
    <dt><strong>CVSS</strong> (Common Vulnerability Scoring System)</dt>
</dl>

<dl>
    <dt><strong>DPoP</strong> (Distributed Proof of Possession)</dt>
    <dd>It's a security mechanism primarily used in OAuth 2.0 and OpenID Connect protocols to enhance the security of access tokens. The DPoP mechanism works by having the client sign a unique token, called a DPoP proof, using a private key associated with the access token. When making a request to a resource server, the client includes this DPoP proof along with the access token. The resource server can then verify the DPoP proof using the public key associated with the access token, ensuring that the client is in possession of the key and thus authorized to use the token.</dd>
</dl>

<dl>
    <dt><strong>FAPI</strong> (Financial-Grade API)</dt>
    <dd>The Financial-grade API is a highly secured OAuth profile that aims to provide specific implementation guidelines for security and interoperability. The Financial-grade API security profile can be applied to APIs in any market area that requires a higher level of security than provided by standard OAuth or OpenID Connect</dd>
</dl>

<dl>
    <dt><strong>IAM</strong> (Identity and Access Management)</dt>
</dl>

<dl>
    <dt><strong>IdP</strong> (Identity Provider)</dt>
</dl>

<dl>
    <dt><strong>JWT</strong> (JSON Web Token)</dt>
</dl>

<dl>
    <dt><strong>MFA</strong> (Multifactor Authentication)</dt>
</dl>

<dl>
    <dt><strong>OIDC</strong> (OpenID Connect)</dt>
    <dd>OpenID Connect is a simple identity layer on top of the OAuth 2.0 [RFC6749] protocol</dd>
</dl>

<dl>
    <dt><strong>OP</strong> (OpenID Provider)</dt>
    <dd>OAuth 2.0 Authorization Server that is capable of Authenticating the End-User and providing Claims to a Relying Party about the Authentication event and the End-User.</dd>
</dl>

<dl>
    <dt><strong>OWASP</strong> (Open Web Application Security Project)</dt>
</dl>

<dl>
    <dt><strong>RP</strong> (Relying Party)</dt>
    <dd>OAuth 2.0 Client application requiring End-User Authentication and Claims from an OpenID Provider.</dd>
</dl>

<dl>
    <dt><strong>STS</strong> (Security Token Service)</dt>
</dl>

<dl>
    <dt><strong>SP</strong> (Service Provider)</dt>
</dl>

<dl>
    <dt><strong>SWT</strong> (Simple Web Tokens)</dt>
</dl>

<dl>
    <dt><strong>TOTP</strong> (Time-Based One-Time)</dt>
    <dd>
        <a href="https://datatracker.ietf.org/doc/html/rfc6238">RFC6238</a>
    </dd>
    <dt>A type of authentication mechanism commonly used in two-factor authentication (2FA) systems. TOTP relies on a shared secret key between the user and the authentication system, typically stored on a user's device (like a smartphone). This shared secret is combined with the current time to generate a unique, one-time password that changes periodically (usually every 30 seconds).</dt>
</dl>
