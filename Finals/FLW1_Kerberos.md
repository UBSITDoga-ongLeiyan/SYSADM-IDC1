+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 2d99e404ab6a474087dc9918501de4f6 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doga-ong, Leiyan M.        | DATE PERFORMED:        | /50      |
|                                  | 11/06/2024             |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 11/06/2024             |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Kerberos Basics

Research Activity

1.  What is Kerberos, and why is it used?

-   A Kerberos is a system or router that provides a gateway between
    users and the internet. Therefore, it helps prevent cyber attackers
    from entering a private network. It is a server, referred to as an
    "intermediary" because it goes between end-users and the web pages
    they visit online.

2.  What are the main components of Kerberos?

-   The Kerberos system consists of three components: a client, a
    server, and a trusted third party, which is also known as a Key
    Distribution Center (KDC). The KDC interacts with both a client and
    server to accept the client's request, authenticate its identity,
    and issue tickets to the service. 

3.  What is a \"ticket\" in Kerberos, and why is it important?

-   Tickets in Kerberos are a set of electronic information that can be
    used to verify your identity. Your Kerberos tickets may be stored in
    a file, or they may exist only in memory.

-   Users, systems and services using Kerberos need only trust the KDC.
    It runs as a single process and provides two services: an
    authentication service and a ticket granting service (TGS). KDC
    \"[tickets](https://www.techtarget.com/searchenterprisedesktop/definition/authentication-ticket)\"
    provide [mutual
    authentication](https://www.techtarget.com/searchsecurity/definition/mutual-authentication),
    allowing nodes to prove their identity to one another in a secure
    manner.

4.  What is a Kerberos \"realm,\" and what is its purpose?

-   A ticket is a time-limited, secure data structure used in Kerberos
    that is sent by the Key Distribution Center (KDC) to authenticate a
    user or service to another service on a network. By using tickets as
    proof of identity, users can authenticate to a variety of services
    without having to input their passwords again.

-   A Kerberos ticket\'s main purpose is to authenticate a user to a
    service without requiring the password to be sent over the network
    each time. A Ticket Granting Ticket (TGT) is issued by the KDC to
    the user once they authenticate it using their password upon first
    logging in. By requesting access to additional services using this
    TGT, security and usability are improved without requiring the
    password to be entered repeatedly.

5.  How does Kerberos authenticate a user?

-   During authentication, Kerberos stores the specific ticket for each
    session on the end-user\'s device. Instead of a password, a
    Kerberos-aware service looks for this ticket. Kerberos
    authentication takes place in a Kerberos realm, an environment in
    which a KDC is authorized to authenticate a service, host, or user. 

-   Here are the most basic steps taken to authenticate in Kerberos.

1.  Client requests an authentication ticket (TGT) from the Key
    Distribution Center (KDC)

2.  The KDC verifies the credentials and sends back an encrypted TGT and
    session key

3.  The TGT is encrypted using the Ticket Granting Service (TGS) secret
    key

4.  The client stores the TGT and when it expires the local session
    manager will request another TGT (this process is transparent to the
    user)

# 

6.  What does each component (KDC, TGS, AS) contribute to the
    authentication process?

-   Kerberos uses symmetric
    key [cryptography](https://www.fortinet.com/resources/cyberglossary/what-is-cryptography) and
    a key distribution center (KDC) to authenticate and verify user
    identities. A KDC involves three aspects:

    1.  A ticket-granting server (TGS) that connects the user with the
        service server (SS)

    2.  A Kerberos database that stores the password and identification
        of all verified users 

    3.  An authentication server (AS) that performs the initial
        authentication 

7.  How does a ticket improve security compared to repeated password
    logins?

-   Compared to frequent password logins, Kerberos tickets provide a
    number of significant security advantages. Since the password is
    only used once to get a ticket rather than being sent continuously,
    they first lessen the risk of passwords. This reduces the
    possibility of being intercepted. Additionally, attackers have a
    smaller window of opportunity to misuse Kerberos tickets since they
    are time-limited, meaning they expire after a specific period of
    time. Because the tickets are encrypted, it is harder for hackers to
    intercept or abuse them. Lastly, Kerberos simplifies access control
    and lowers the overall security risks related to storing several
    passwords or credentials across various services by centralizing
    authentication through a single point of management.

<https://www.ibm.com/docs/en/cics-ts/6.x?topic=cics-kerberos>

<https://www.techtarget.com/searchsecurity/definition/Kerberos#:~:text=Kerberos%20is%20a%20protocol%20for,network%2C%20such%20as%20the%20internet>.

<https://www.fortinet.com/resources/cyberglossary/kerberos-authentication#:~:text=During%20authentication%2C%20Kerberos%20stores%20the,service%2C%20host%2C%20or%20user>.

<https://www.it.ucsb.edu/general-security-resources/password-best-practices>

<https://bestreviews.net/the-risks-of-using-the-same-password-for-different-accounts/>

<https://learn.microsoft.com/en-us/windows-server/security/kerberos/kerberos-authentication-overview>
