# OAuth

- OAuth is an open standard for access delegation, commonly used as a way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords.

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/OpenIDvs.Pseudo-AuthenticationusingOAuth.svg/512px-OpenIDvs.Pseudo-AuthenticationusingOAuth.svg.png)

- The simplest example of OAuth in action is one website saying “hey, do you want to log into our website with other website's login?” In this scenario, the only thing the first website – let's refer to that website as the consumer – wants to know is that the user is the same user on both websites and has logged in

# How OAuth Works

1. The User Shows Intent.
2. The Consumer Gets Permission.
3. The User Is Redirected to the Service Provider.
4. Bitly directs Joe to Twitter for authorization
5. The User Gives Permission.
6. The Consumer Obtains an Access Token.

# OpenID

- OpenID is an open standard and decentralized authentication protocol promoted by the non-profit OpenID Foundation.

### What's the difference between authentication and authorization? Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.

![img](https://www.okta.com/sites/default/files/styles/1640w_scaled/public/media/image/2020-10/Authentication_vs_Authorization.png?itok=uBFRCfww)

# Authorization Code Flow

- Authorization code flow is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction.

### The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.

### Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

### The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. It can be nightly operations, or other that involve contacting OAuth protected APIs.

### The authorization flow defined by this specification, sometimes referred to as the "device flow", instructs the user to review the authorization request on a secondary device, such as a smartphone, which does have the requisite input and browser capabilities to complete the user interaction.

### The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. The primary difference is that the user's password is accessible to the application.

![img](https://cxlabs.sap.com/wp-content/uploads/2012/06/oauth2_resource_owner_password_flow.png)
