### Email handler
The email handler component manages communication between the system and users via email. It is responsible for sending emails to users. The code is implemented in the file ``email_handler.py``.

--- 

### Hash Encryption
The hash encryption component is responsible for securing sensitive data, such as user passwords and authentication tokens, by converting them into irreversible hash values. It is used to generate hash values for sensitive data using bcrypt algorithm. The code is implemented in the file ``hash.py``.

---

### Role checker
The role checker component determines the role of users accessing the system, distinguishing between administrators and regular users, and granting appropriate privileges based on their roles. The code is implemented in the file ``role_checker.py``.

---

### Token Generation
The token generation component creates unique tokens that are used for authentication and access control within the system. Utilizes cryptographic token generation techniques, such as JSON Web Tokens (JWT), to create and manage secure tokens for user authentication and authorization. The code is implemented in the file ``token.py``.