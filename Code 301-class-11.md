# OAuth

## What is OAuth?

OAuth is an open-standard **authorization** protocol or framework that describes how unrelated servers and services can safely allow *authenticated* access to their assets without actually **sharing** the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

## OAuth examples

The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.

## How does OAuth work?

When we sign up in a website using another website (i.e singing in *auth0* using *github*) some processes happen by these steps:

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

3. The first site gives this token and secret to the initiating user’s client software.

4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

6. The user approves (or their software silently approves) a particular transaction type at the first website.

7. The user is given an approved access token (notice it’s no longer a request token).

8. The user gives the approved access token to the first website.

9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

10. The second website lets the first website access their site on behalf of the user.

11. The user sees a successfully completed transaction occurring.

12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

## What is OpenID?

is an open standard and decentralized authentication protocol. Promoted by the non-profit OpenID Foundation, it allows users to be authenticated by co-operating sites (known as relying parties, or RP) using a third-party service, eliminating the need for webmasters to provide their own ad hoc login systems, and allowing users to log into multiple unrelated websites without having to have a separate identity and password for each.Users create accounts by selecting an OpenID identity provider[1] and then use those accounts to sign onto any website that accepts OpenID authentication. Several large organizations either issue or accept OpenIDs on their websites, according to the OpenID Foundation.

## Difference between authorization and authentication?

Authentication and authorization might sound similar, but they are distinct security processes in the world of identity and access management (IAM).

**Authentication** confirms that users are who they say they are. **Authorization** gives those users permission to access a resource.

## Authorization code flow

Authorization code flow is used to obtain an access token to authorize API requests.

## Authorization Code Flow with Proof Key for Code Exchange (PKCE)

During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).

## Implicit flow

The Implicit flow was a simplified OAuth flow previously recommended for native apps and JavaScript apps where the access token was returned immediately without an extra authorization code exchange step.

## Client Credentials Flow

Instead, M2M apps use the Client Credentials Flow , in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.

## Device Authorization Flow

Device Authorization Flow instructs the user to review the authorization request on a secondary device, such as a smartphone.

## Resource Owner Password Flow

The Resource Owner Password Credential (ROPC) flow is one of the standard flows defined in OAuth.1 Unlike some of the other standard flows, it is a very straightforward request and response. The client simply makes a call to the OAuth server’s token endpoint and gets tokens in the response. It is a sort of “login” API, if you will.
