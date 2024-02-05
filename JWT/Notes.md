## JWT

* Representing claims to be transferred between two parties.

* Stateless authentication.

* Header consists of two main part. The type of token which is JWT, and
the signing algorithm, for example RSA.

* The payload contains the claims.

* JWT also has a signature that uses header, payload, and a secret to be created.

* The resulting JWT is a compact and url-safe string.

* URL-safe means that JWTs can be safely included in HTTP headers or stored in
cookies.

* A secure cookie is a cookie that is only transmitted over encrypted connections
like HTTPS.

*  An HTTP-only cookie is a cookie that is inaccessible to JavaScript running in the
browser. This means that client-side scripts cannot access or manipulate the cookie
through the Document Object Model (DOM).

* These secure http-only cookies prevent stuff like XSS attacks.

* Cross-Site Scripting (XSS) occurs when an attacker injects malicious scripts
(usually JavaScript) into web pages viewed by other users. These scripts are then
executed in the context of the victim's browser, allowing the attacker to steal
information, hijack sessions, deface websites, or perform other malicious actions.
