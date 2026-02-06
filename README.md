# Beirut Cloud

**Beirut Cloud** is my cloud imitation project to learn the nits n cranies of building a cloud platform (from networking to the smallest possible race conditions to databases). It is based on the workhorse called Linux and the raw power of golang.
I acknowledge as an aspiring developer how important to make it in rust, but for now velocity and good quality is prioritized (might stay in go).

---

# Philosophy

A cloud that uses lebanese area names for regions, in hopes someday we could have our own cloud in Lebanon.
**But why our own cloud?**
A local cloud to serve the local community with the compute that it needs and to develop the region's skills in cloud.
**Does Lebanon need its own compute?**
Current compute providers offer cheaper prices, better know-how and beautiful UI.
We don't need more of those. But we need ...

---

# plan

- We will start setting up simple IAM with a simple login. Putting Machine-To-Machine authentication in the backlog. 
- IAM will be based on 
- User validation will be done with Project level IAM. Putting Organization-level validation in the backlog.

---

# What is Keycloak

**Keycloak** is an open source Identity and Access Management service that handles users and authentication, without authorization.

| Feature| What It Means|
|---|---|
| **User database**     | Stores usernames, passwords (hashed), emails, profiles        |
| **Login pages**       | Provides ready-made screens: login, register, forgot password |
| **Password security** | Handles hashing, password policies, breach detection          |
| **Multi-factor auth** | TOTP (Google Authenticator), SMS, WebAuthn (YubiKey)          |
| **Social login**      | "Sign in with Google/GitHub"                                  |
| **Single sign-on**    | Log in once, access multiple apps                             |
| **Admin console**     | Web UI to manage users, see who logged in when                |





| TODO | In Progress | done |
| --- | --- | --- |
| Cell A1 | Cell A2 | Cell A3 |
| Cell B1 | Cell B2 | Cell B3 |