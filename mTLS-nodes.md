# mTLS
- mTLS (Mutual Transport Layer Security) is a way of confirming both that the client can trust the server to be legitimate *and* that the server can trust the client to be legitimate as well.

## mTLS vs TLS
- Because mTLS involves the client proving its identity in addition to the server, it differs from TLS, in which only the server must prove it can be trusted and any client can therefore be granted access.
- In TLS, once the server's certificate has been verified, the transmission of data can begin. In mTLS, it is here that the client must hand over its certificate and await approval before receiving information.
- A key difference is also the certificates themselves; applications using mTLS serve as their own CAs, creating self-signed root certificates. On the contrary, in TLS, CAs are trustworthy third-parties such as IdenTrust or GlobalSign that confirm that the organisation owns a given domain.
- This has benefits such as greater independence (reliance on an external CA is not necessary), full control over keys, greater scalability, and more flexibility in the choice of algorithms, keys and certain parameters used in the encryption process.

## What are the benefits?
mTLS is useful in situations where particularly high levels of security are required. TLS provides sufficient security for most operations on the internet, but where particularly sensitive data is involved, it might not be enough.

mTLS is especially secure because, by ensuring that the client's identity is also legitimate, it prevents attacks such as:

- On-path attacks
- Spoofing attacks
- Credential stuffing
- Brute force attacks
- Phishing attacks
- Malicious API requests

It is also useful for IoT devices that do not follow typical login processes. 

## Example of mTLS


## Diagram

- How is mTLS different from what has been described in this lecture (securing websites)?
- Where is mTLS frequently used?
- Give an example application which uses mTLS
- Draw a diagram (I suggest https://excalidraw.com/) to show the process
