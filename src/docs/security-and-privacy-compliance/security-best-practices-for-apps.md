---
title: Security Best Practices For Apps

slug: security-best-practices-for-apps

description: 

keywords: 

page_purpose: 

audience: developer, technical lead

author: Matt Spencer 

content_owner: Nick Corcoran
---
<!-- Draft in progress -->

# Security Best Practices For Apps

Government employees should take particular care to adhere to security and privacy requirements when working on content in an open environment such as GitHub. The Office of the Chief Information Officer (OCIO) provides the IM/IT Standards you are required to follow, and the content you work with on GitHub must conform with the requirements of being labeled as "Public" using the OCIO Information Security Classification Framework.



## On this page
- [Open Development Basics](#open-development-basics)
- [What does 'doing it right' mean?](#doing-it-right)

## Open Development Basics <a name="open-development-basics"></a>

There is a [healthy debate](http://www.dwheeler.com/secure-programs/Secure-Programs-HOWTO/open-source-security.html) in the security community around the use and development of OSS applications and the implications of exposing the code publicly vs keeping it behind closed doors. The debate boils down to the fact that there is no conclusive evidence that deems either Open or Closed source as inherently more secure. It all comes down to the people (the coders) and their willingness to build security into their code. The one thing that coding in the open does for security is that the public scrutiny of a coders work is proven as a motivating factor for "doing it right" from the start.

## What does "doing it right" mean? <a name="doing-it-right"></a>

### Separate Code from Deployment

Keys, passwords and other secrets must always be stored safely and securely away from source code. This separation of project code from deployed instances of a project is good development practice regardless of whether or not the software itself is shared in public.

### Circle of Trust

It’s advisable for large, significant projects to have a private space to discuss security issues and develop a patch. This removes the risk of flagging a vulnerability before a fix has been deployed. This is especially advisable if there’s a small number of participating developers.

### Review the code

Sounds obvious but this step has been skipped by every developer in the world at least once. The simple action of having a second set of eyes on the code can avoid many pitfalls before it's too late.

### Stay up to date on security best practices

Most languages, platforms and products have best practices for securing applications - find them, follow them and keep current because security is a moving target.

---
Related links:
- [Vault Secret Management Service](./vault-secret-management-service.md)
- [Linux Foundation OSS Security Badges](https://github.com/linuxfoundation/cii-best-practices-badge)
- [Unix, PHP, Python and general programing](http://www.dwheeler.com/secure-programs/Secure-Programs-HOWTO/index.html)
- [Java](https://www.java.com/en/security/developer-info.jsp)
- [MSDN: Windows & .NET](https://msdn.microsoft.com/en-us/library/zdh19h94(v=vs.140).aspx)
- [WordPress](http://stevegrunwell.github.io/wordpress-security-basics/#/)
- [Node.js](http://blog.risingstack.com/node-js-security-tips/)
- [Drupal](https://www.drupal.org/writing-secure-code)


Rewrite sources:
* https://developer.gov.bc.ca/Platform-Services-Security/BC-Government-Vault-Secrets-Management

---
