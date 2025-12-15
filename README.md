# Cyber Security Acronyms

Welcome to the this Cyber Security Acronyms Glossary, a resource for deciphering the myriad of acronyms and abbreviations commonly encountered in cybersecurity.

This glossary aims to provide concise explanations for a wide range of acronyms spanning various facets of cybersecurity, including network security, cryptography, malware, and more.

**2FA** (Two-factor Authentication)

**ABAC** (Attribute-Based Access Control)
: A type of access control that uses attributes to determine access rights. An access control decision is based on the attributes of the user, the resource to be accessed, and the current environment.

**ACL** (Access Control List)
: A list of permissions attached to an object that specifies which users or system processes are granted access to objects, as well as what operations are allowed on given objects.

**AD** (Active Directory)
: A directory service developed by Microsoft for Windows domain networks. It is included in most Windows Server operating systems as a set of processes and services. Initially, Active Directory was only in charge of centralized domain management. However, Active Directory became an umbrella title for a broad range of directory-based identity-related services.

**CIAM** (Customer Identity and Access Management)

**CIBA** (Client Initiated Backchannel Authentication)
: OpenID Connect Client Initiated Backchannel Authentication Flow is an authentication flow like OpenID Connect. However, unlike OpenID Connect, there is direct Relying Party to OpenID Provider communication without redirects through the user's browser.

**CVE** (Common Vulnerabilities and Exposures)
: A list of entries—each containing an identification number, a description, and at least one public reference—for publicly known cybersecurity vulnerabilities.

**CVSS** (Common Vulnerability Scoring System)
: A free and open industry standard for assessing the severity of computer system security vulnerabilities. CVSS attempts to assign severity scores to vulnerabilities, allowing responders to prioritize responses and resources according to the threat.

**CWE** (Common Weakness Enumeration)
: A community-developed list of common software and hardware weakness types that have security ramifications.

**DAST** (Dynamic Application Security Testing)
: A type of security testing that examines an application while it is running to identify security vulnerabilities.

**DDoS** (Distributed Denial of Service)
: A cyber-attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by temporarily or indefinitely disrupting services of a host connected to the Internet.

**DLP** (Data Loss Prevention)

**DPoP** (Distributed Proof of Possession)
: It's a security mechanism primarily used in OAuth 2.0 and OpenID Connect protocols to enhance the security of access tokens. The DPoP mechanism works by having the client sign a unique token, called a DPoP proof, using a private key associated with the access token. When making a request to a resource server, the client includes this DPoP proof along with the access token. The resource server can then verify the DPoP proof using the public key associated with the access token, ensuring that the client is in possession of the key and thus authorized to use the token.

**DSPM** (Data Security Posture Management)
: A set of security tools and processes that help organizations manage and secure their data. DSPM tools provide visibility into an organization's data security posture, helping to identify and remediate security risks and compliance issues.

**FAPI** (Financial-Grade API)
: The Financial-grade API is a highly secured OAuth profile that aims to provide specific implementation guidelines for security and interoperability. The Financial-grade API security profile can be applied to APIs in any market area that requires a higher level of security than provided by standard OAuth or OpenID Connect.

**FIDO** (Fast IDentity Online)
: Set of open standards for secure authentication, aiming to reduce reliance on passwords by enabling users to authenticate to online services using simpler and more secure methods such as biometrics or hardware tokens.

**HRD** (Home Realm Discovery)
: A mechanism to identify the realm or domain that a user is logged into. It is sometimes from email address or username and can be used to determine the identity provider.

**IAM** (Identity and Access Management)

**IdP** (Identity Provider)
: A trusted entity that provides authentication services to users. It is a server that creates, maintains, and manages identity information for principals while providing authentication services to relying applications within a federation or distributed network.

**IWA** (Integrated Windows Authentication)
: A term associated with Microsoft products that refers to the SPNEGO, Kerberos, and NTLMSSP authentication protocols with respect to SSPI functionality introduced with Microsoft Windows 2000 and included with later Windows NT-based operating systems. Integrated Windows Authentication uses the security features of Windows clients and servers to provide secure, single sign-on to applications and websites.

**JWT** (JSON Web Token)

**LCM** (LifeCycle Management)
: The process of managing the entire lifecycle of digital certificates or identities. For certificates it includes issuance, renewal, revocation, and expiration. For identities it includes creation, provisioning those to applications, modification, and deletion.

**LDAP** (Lightweight Directory Access Protocol)
: A protocol for accessing and maintaining distributed directory information services over an IP network. It is a set of protocols for accessing information directories. These directories can contain a wide variety of information, such as the email addresses of individuals in an organization and the public keys of computer servers.

**MFA** (Multifactor Authentication)
: A security system that requires more than one method of authentication from independent categories of credentials to verify the user's identity for a login or other transaction.

**OIDC** (OpenID Connect)
: OpenID Connect is a simple identity layer on top of the OAuth 2.0 \[RFC6749\] protocol.

**OP** (OpenID Provider)
: OAuth 2.0 Authorization Server that is capable of Authenticating the End-User and providing Claims to a Relying Party about the Authentication event and the End-User.

**OWASP** (Open Web Application Security Project)

**PII** (Personally Identifiable Information)
: Information that can be used on its own or with other information to identify, contact, or locate a single person, or to identify an individual in context.

**ROP** (Resource Owner Password)
**ROPC** (Resource Owner Password Credentials)
**ROPF** (Resource Owner Password Flow)
: A way to exchange a user's credentials for an access token. This OAuth 2.0 flow is suitable for clients capable of obtaining the resource owner's credentials (username and password, typically using an interactive form).

**RP** (Relying Party)
: OAuth 2.0 Client application requiring End-User Authentication and Claims from an OpenID Provider.

**SAML** (Security Assertion Markup Language)
: An open standard for exchanging authentication and authorization data between parties, in particular, between an identity provider and a service provider. SAML is an XML-based markup language for security assertions (statements that service providers use to make access-control decisions).

**SAST** (Static Application Security Testing)
: A type of security testing that relies on examining the source code of an application to identify security vulnerabilities.

**SCIM** (System for Cross-domain Identity Management)
: A standard for automating the exchange of user identity information between identity domains, or IT systems. It aims to simplify user provisioning and management in the cloud by defining a schema for representing users and groups and a RESTful API for managing these objects. The protocol is designed to be simple and extensible, and it is based on standard web technologies such as HTTP and JSON.

**SP** (Service Provider)
: An entity that provides services to one or more end-users. In the context of SAML, a service provider is a system entity that provides services to users. These services can be anything from a simple web application to a full-fledged enterprise application.

**SSO** (Single Sign-On)
: A session and user authentication service that permits a user to use one set of login credentials (e.g., name and password) to access multiple applications.

**STS** (Security Token Service)

**SWT** (Simple Web Tokens)
: A token format that is used to pass claims between a client and a web service. SWT is designed to be easily parsed and validated by web services, making it a lightweight and efficient token format for use in web-based scenarios.

**TOTP** (Time-Based One-Time)
[RFC6238](https://datatracker.ietf.org/doc/html/rfc6238)
: A type of authentication mechanism commonly used in two-factor authentication (2FA) systems. TOTP relies on a shared secret key between the user and the authentication system, typically stored on a user's device (like a smartphone). This shared secret is combined with the current time to generate a unique, one-time password that changes periodically (usually every 30 seconds).

**U2F** (Universal 2nd Factor)
[FIDO Universal 2nd Factor Specs](https://fidoalliance.org/specs/u2f-specs-master/fido-u2f-overview.html)
: Specific authentication protocol within the FIDO framework, providing an additional layer of security by requiring a physical token, typically a USB or NFC device, in addition to passwords or other authentication methods.

**WAAD** (Windows Azure Active Directory)
: A cloud-based identity and access management service from Microsoft. It basically an Active Directory deployed and operated on Microsoft Azure.
