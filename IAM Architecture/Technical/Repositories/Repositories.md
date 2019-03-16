### Repositories

If there is any topic that's unique to each IAM environment it's the
identity storage infrastructure. There is no best-practice that fits all
situations. A datastore with a directory front-end will typically suit
the storage of identity data best because of their fast retrieval
capabilities. But many of the larger corporate applications utilize
internal databases for identity information. The identity management
professional must decide how best to work with constraints posed by the
unique characteristics of the organization.

#### Relational Database

Most applications maintain one or more internal databases for the
storage of application data and there will often be a table for identity
data that will be used to determine access control to application
facilities. For instance, a staff member's entitlement to access the
accounts payable ledger will typically be held in a table within the
financial management system. The identity management professional must
determine whether there is an approval workflow API to write to the
permissions table, whether an exposed SQL interface with write
permissions is available or whether a service desk interface must be
used.

##### Query optimization

There are several reasons why database administrators (DBAs) are so well
paid. Working with a complex database is an art more than a skill. A
good DBA will be able to optimize a query by ensuring the table
structure is well designed and queries across multiple tables are well
constructed to minimize the time (and processing power) required to
return a result. DBAs will also enable the requisite security to be
constructed, since limitations on access to data is paramount.

##### Replication limitations

Few large organizations have a single campus. Most corporations are
spread across multiple locations either on a single continent or
globally. This provides a challenge for organizations with corporate
applications with an internal database. Replicating databases is not for
the faint-hearted. Fortunately cloud infrastructure is making this
easier, Azure, AWS and other purveyors of public cloud infrastructure
provide services that will replicate databases between multiple
locations and maintain data integrity. Typically the identity management
professional will select a master location for identity data and rely in
the underlying cloud technology to replicate this data to other
locations.

#### Directories

The preferred technology for the storage of identity data is a directory
because of the optimized interface that can lookup an indivudual's
record across millions of entries and return a result in milliseconds.

##### LDAP

In the past directories have been very hierarchical with idneity data
stored in OUs (organizational units) that parallel the company's
organizational structure. This was first standardize in the X.500
specification with a recommended schema called InetOrgPerson. The
lightweight directory access protocol (LDAP) specification became the
most widely-used directory interface for querying a directory and the
LDAP data interface format (LDIF) became the defacto standard for bulk
uploads to a directory.

##### S/LDAP

One of the deficiencies of LDAP in the modern age is its ease-of-use.
Anyone with an LDAP filter, with knowledge of the directory, can do a
bind to the directory and retrieve data from it. This obviously violates
privacy legislation and is unacceptable nowadays. One of the ways to
make directory access secure is to use S/LDAP. This requires the
directory bind to be made on a reserved port and for an authentication
mechanism to be utilized. Public key infrastructure (PKI) is often used
for this purpose. There is no need to throw-out a functioning LDAP
directory in order to satisfy modern access control requirements

#### NoSQL databases

As with many developments today there is a move away from hard work such
as setting up servers, configuring firewalls or writing code. We want
the servers to autoscale, the network discovery to document access
permissions and the development environment to write our apps. So is is
with databases. Why laboriously set up table strictures when all you
need to do is write the data to the database. NoSQL databases provide
this facility -- the directory determines how to store your data and
will respond when you request it. But when it comes to identity data we
would like a little more, this is where graph interfaces become
attractive.

##### Graph databases

With the development of identity management environments, the propensity
to adopt cloud infrastructure and the increased focus on relationships,
graph databases are increasingly being used for the storage of identity
information.

Rather than using a rigid schema a graph database stores identity
information in a relationship "mesh". This means that standard queries
such as "is Sally in the Finance department?" can be extended to "does
Sally know Bob in Purchasing?", which might be a probity issue. The
database query construction is important and determining the number of
"hops" in a query will significantly affect its efficiency.

#### Identity Provider (IdP) Trends

The future of IdPs is being forged shadow of major trends in identity
management:

-   Relationships -- identity providers need to be able to not only
    provide identity attributes but to provide detail on relationships
    between identities (or entities for that matter) as well.

-   Dynamic authentication -- risk-based access control means that
    additional data is required when a person requests access to a
    service. While a traditional data store might know my credit card
    number, it won't know if I've used it locally recently, which could
    be useful information to support a high-assurance authentication.

-   Staff costs - organizations are hesitant to engaged expensive staff
    such as DBAs. If a secure and functioning data storage facility can
    be purchased and deployed relatively easily this becomes the
    preferred option.

While LDAP directories are not dead the trend is to deploy identity
storage infrastructure that supports modern interfaces such as Graph.

##### Distributed Ledger (Blockchain)

There is significant development in the deployment of blockchain
technology in the provision of identity provider services. A person's
identity in a particular domain will be substantiated via attributes
that attest to their identity. In many cased the authoritative source
for an attribute will be distributed. Academic credentials are a cases
in point. If I want to establish my education credentials as part of a
job application the recruiter will want to verify these credentials.
Blockchain is the ideal technology to support this requirement i.e. the
university from which I have graduated can contribute this information
to a distributed data store to which I can give the recruiter access.

The Distributed Identity Foundation is proposing the use of
Decentralized IDentifiers (DIDs) for identities with attributes in a
distributed ledger. If an identity has a registered DID with one
Blockchain it should be recognised/used by another Blockchain on which
my credentials might be stored. A universally accessible DID Resolver
will support the use of Decentralized Identities across multiple
Blockchains i.e. there is no need for a centralized authoritative source
for credential assurance. A number of mainstream Blockchain suppliers
have indicated their support for this approach.
