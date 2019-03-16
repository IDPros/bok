# Identity and Context

## Abstract
Identity is a concept that fundamentally depends on the context in which
the identity might be used. The purpose of establishing the context of an
Identity is to allow for acess control to a resource.

## Introduction
Identity is a broad concept. In fact, there are many definitions of the
term 'Identity'. Our scope is to define identity so that it can be used
as a means to get access to protected resources. Be it a document, or a
record in a database, or even a physical location. In most cases an
identity is required to prove that one has a legitimate reason to access
a resource. But getting access depends on the context of the access
requested and on the context of the identity requesting access.

Most identities cannot be used globally: an identity is valid within a
certain context. For instance your identity can be father or mother
within the boundaries of your family. In another family you are not.
This means that the identity is valid within a certain trusted domain.
Either your family, your company, your football club or bar. Within this
context identities are created and provided to the person concerned to
use within this context. And based on the fact that the identity is
created in the trust domain, these identities are trusted. Within this
trust domain, all trust is equal.

## Terminology
Identity

Context

Trust Domain

Federation

## Identity and the Trust Domain

An Identity is valid, or trusted, within the boundaries of this trust
domain. But even within such a trust domain, not all identities are
treated equally, some are more valuable than others, some have more
power(s) than others. But at least an identity is required to be able to
use this power within the domain.

Identities from external contexts can be given powers in certain trust
domains, but that is only possible if trust relations exist. This
relationship is called a federation. An identity from an external
federated context will, in most cases, not have the same level of trust
as in internally created identity and therefore will not have the same
power(s) as in internally provided identity. A facebook identity can be
used within the facebook community, but not elsewhere, unless someone
agrees on using facebook identities for certain tasks, like reading news
on a news website. Facebook is an external Identity Provider.

It is important to understand is that not all access to a protected
resource requires an identity. Getting access without an identity is
possible, if the resource owners hase means to limit the risk of abuse.
For instance to travel by train, the company requires payment befor
travel. The railway shouldn't have to care about abuse, if a traveller
can show that the travel has been paid (see [Harper2006]).

## Identity and Authentication
To get access to a protected resource, it is not enough to just
identify. To prove the legitimate existance and use of an identity,
verification needs to take place.

-   Provisioning of an identity requires verification of the person who
    requests an identity. This means that the Identity Provider will
    assure the actual existence of the subject, by means of verification
    of the identity. In a family the birth of a baby is an accurate
    verification, but in other contexts verification of a passport, or
    verification of an email address is required. The means of
    verification depends on the trustlevel and risk level of the
    context.

-   Use of an identity to get access requires verification of the usage
    rights of the person that requests access. Using proof, like
    passports (again), or passwords and tokens provided by the Identity
    Provider.

## Author Bio
André Koot is an IAM and Security Consultant at Nixu Benelux and is 
the IAM Internal Practice Lead within Nixu.

## References
[Harper2006] Harper, Jim. Identity Crisis: How Identification is Overused and Misunderstood. 250 pages. Cato Institute. 2006.
