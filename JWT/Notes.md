## JWT

* Representing claims to be transferred between two parties.
* Stateless authentication.
* Header consists of two main part. The type of token which is JWT, and the signing algorithm, for example RSA.
* The payload contains the claims.
* JWT also has a signature that uses header, payload, and a secret to be created.
* The resulting JWT is a compact and url-safe string.
* URL-safe means that JWTs can be safely included in HTTP headers or stored in cookies.
