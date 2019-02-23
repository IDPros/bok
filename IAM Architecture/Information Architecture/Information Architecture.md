Information/Data Architecture
-----------------------------

The information architecture (IA) defines the data required to support
an organization's business systems. A comprehensive IA will ensure
sufficient data is collected and stored, and, that no data is collected
and stored that is not required by one or more business system.

This is particularly important for the IAM infrastructure. Privacy
legislation in most western jurisdictions prohibit the collection of
identity data that is not required for a business purpose. A good IA
significantly assists with legislation compliance.

The IA must document the structure of identity data storage within the
IAM environment. In many cases the IAM system will maintain its own data
repository of identity data i.e. maintain an interface to the HR system
and to relying applications via connectors that update the IAM system.

The recommended way to document the data requirements for the IAM system
and relying applications is via an entity relationship diagram that
shows each identity data attribute that is collected and used within the
business. This will enable the identity management professional to
understand the use and storage of identity data. Increasingly
organizations are seeking to maintain a directory that is the "source of
truth" for identity information within the organization and each
application maintains a connector to this repository which is typically
an electronic directory. In some cases this is an LDAP directory, in
Microsoft environments it is increasingly Active Directory (AD) or Azure
AD. A central repository simplifies the IAM task but in many cases
applications are not designed to use an external directory, they
maintain their own internal databases of identity and account permission
information.

Note: in some cases identity management processes will be constrained by
technical and political issues within an organization. The IA must
accommodate these constraints. For instance, an application may not be
able to be provisioned automatically because the permissions rules that
have been developed over many years and are too complex to automate e.g.
ERP systems with multiple permission levels. In some cases manual
assignment of permissions will be mandated e.g. some acute care medical
facilities. In these instances the IAM provisioning system will use a
manual interface and place a request on the appropriate service desk
queue.

#### Example

![Entity Relationship Diagram](Figure4.png)
Figure 4 - Entity Relationship Diagram
