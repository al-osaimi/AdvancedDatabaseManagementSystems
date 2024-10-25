1. **Explain the role of servlets in Java-based web applications and how they contribute to dynamic web content generation. What advantages do servlets offer over traditional client-side scripting?**
   <details>
   <summary>Answer</summary>
   Servlets are Java-based server-side programs that handle client requests (usually HTTP requests) and generate dynamic web content. They run on a server and can interact with databases and other resources to provide real-time data to users. Unlike client-side scripts, servlets can handle business logic securely on the server and are not exposed to the client. This ensures better control over data processing and security. Servlets also support scalability, as multiple clients can be handled concurrently by the server without sending heavy processing tasks to the client.
   </details>

2. **How does session management using cookies and HTTP sessions ensure user continuity and security in web applications, and what are the potential risks if improperly implemented?**
   <details>
   <summary>Answer</summary>
   Session management allows a web application to track a user's interactions over multiple requests. Cookies store session IDs on the client-side, which are sent back to the server with each request, while the server maintains the session state. This ensures that users don’t need to log in every time they navigate to a new page. However, if session management is not properly secured (e.g., if session IDs are exposed or not encrypted), it can lead to session hijacking or fixation, where an attacker takes over a valid session, posing significant security risks.
   </details>