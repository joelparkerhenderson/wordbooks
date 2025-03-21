# Authentication

Authentication in the context of software applications refers to the process of verifying the identity of a user, device, or system trying to access the software or its resources. This ensures that only authorized users can perform certain actions or access specific data. 

Authentication methods can vary based on security requirements and the sensitivity of the information being protected.

## Helpful terminology

### Type 1 Authentication: something you know

**Username or Email Address**: A user provides a unique identifier (such as a username or email address) to initiate the login process. This is typically the first step before entering other forms of credentials.

**Password or Passphrase**: A password is a secret string of characters (letters, numbers, symbols) used to authenticate a user. A passphrase is similar but typically longer and more complex.
   
**Security Challenge Questions**: The user answers a set of pre-determined questions, such as "What is your favorite color?" or "Who wrote your favorite book?" to verify their identity.

**Recovery Codes**: Temporary or one-time codes that are used to regain access when the usual authentication method (like a password) is unavailable. These codes are often provided during account setup or via email/SMS.

**Personal Identification Number (PIN)**: A numeric password that is usually shorter than a password but is used to authenticate a user, often on bank automatic teller machines (ATMs), or phone call services.

### Type 2 Authentication: something you have

**Mobile Authentication Application (Authenticator App)**: Applications like Google Authenticator, Microsoft Authenticator, or Authy generate a time-limited one-time password (TOTP) that proves the user has access to the user's personalized authentication application.

**OTP (One-Time Password)**: A single-use password for a user to complete a transaction or login session. A popular use is for a website to send an OTP to a user via the email or mobile phone text message.

**TOPT (Time-Based One-Time Password)**: A type of OTP that is valid for a very short period (e.g., 30 seconds). The password is generated based on the current time and a secret key shared between the server and the client.

**FIDO2 (Fast IDentity Online 2)**: A set of standards for strong authentication that enables passwordless login using public key cryptography. Users authenticate using devices such as biometric sensors or security keys (e.g., YubiKey).

**RFID (Radio Frequency Identification)**: Authentication using RFID involves the use of a small device, such as an RFID card or tag, that contains unique identifying information. It is scanned by a reader to authenticate the user.

**NFC (Near Field Communication)**: Authentication via NFC uses devices (e.g., smartphones, cards) to communicate with each other when they are in close proximity. It’s often used for contactless payments or authentication.

**Identification card or badge or letter**

**Government passport**

**Smart card**

**Security token**

**Browser cookie**

**Pinned certificate**

**SSH key**

**Electronic signature**: An electronic signature, or e-signature, is data that is logically associated with other data and which is used by the signatory to sign the associated data.
  
### Type 3 Authentication: something you are

**Biometrics**: biometric authentication uses physical traits such as fingerprints, facial recognition, iris scans, or voice patterns to verify the identity of a user.

**Fingerprint**

**Palm print**

**Face recognition**

**Voice recognition**

**Gesture recognition**

**Iris scan**

**Gait analysis**

**Keystroke dynamics**

**Touch dynamics**

### More terminology

**Authentication factors**: The three typical authentication factors (a.k.a. categories) are something you know, something you have, something you are.

**Single-factor authentication (SFA)**: Require one authentication factor to authenticate. The use of only one factor does not offer much protection.

**Multi-Factor Authentication (MFA)**: Require multiple authentication factors to authenticate. The use of multiple factors offers much better protection than single-factor authentication. A typical example: require a password (which is something you know) and time-based one-time password using your mobile phone (which is something you have). [Wikipedia](https://wikipedia.org/wiki/Multi-factor_authentication)

**Continuous authentication**: Most computer systems authenticate users once at the initial log-in session. Some higher-security systems need continuous user authentication methods that continuously monitor and authenticate users based on some biometric trait(s).

**Authentication protocol**: This is a type of computer communications protocol or cryptographic protocol specifically designed for transfer of authentication data between two entities. It allows the receiving entity to authenticate the connecting entity (e.g. a client connecting to a server) as well as authenticate itself to the connecting entity (a server to a client) by declaring the type of information needed for authentication as well as syntax. - Wikipedia.

**Federated identity**: A federated identity is the means of linking a person's electronic identity and attributes, stored across multiple distinct identity management systems. [Wikipedia](https://wikipedia.org/wiki/Federated_identity).

**Federated authentication**: A federated authentication system allows users to authenticate to multiple systems using a single set of credentials.

**Single sign-on (SSO)**: An authentication scheme that allows a user to log in with a single ID to any of several related, yet independent, software systems. True single sign-on allows the user to log in once and access services without re-entering authentication factors. [Wikipedia](https://wikipedia.org/wiki/Single_sign-on).

## Popular directory terminology

**LDAP (Lightweight Directory Access Protocol)**: LDAP is an application protocol used to query and modify directory services. In authentication, it allows users to log in using a centralized directory, such as Active Directory, without needing separate credentials.

**Active Directory**: A directory service provided by Microsoft that helps organizations manage user accounts, authenticate users, and assign permissions to resources within a network. Authentication occurs through LDAP or Kerberos protocols.

**Windows Hello**: A feature of Windows 10 and later that provides passwordless authentication via biometrics (facial recognition or fingerprint) or a PIN. It can also support external security keys.

## Challenges for automatic testing

Software engineering often uses automatic testing, such as for continuous integration (CI), continuous delivery (CD), continuous telemetry (CT), etc. 

However, authentication can be a challenge for automatic testing, especially for multi-factor authentication:

* Example 1: if test code needs to use a mobile phone application for TOPT, then somehow the CI/CD/CT system needs to be able to simulate a phone, or manipulate a phone. Some test systems can simulate a phone by using a virtual device. Some test systems can manipulate a phone by using a robot finger.

* Example 2: if test code needs to do biometrics such as a fingerprint, then the CI/CD/CT system needs to be able to simulate the fingerprint, or manipulate a fake. Some test systems can simulate a fingerprint by mocking the fingerprint scanner. Some test systems can manipulate a fingerprint by using a prosthetic finger that is modeled to match the fingerprint of a real person.
