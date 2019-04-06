Application Portfolio
---------------------

The Application Portfolio (AP) is an inventory of the main applications in use
within an organization. It should include a name, description, owner,
type/pattern (client-server, “n-tier” webservice, AWS/Azure containerized, etc.),
OS version, databases and version(s), interfaces (LDAP, ODBC, SAML RESTful APIs,
etc.) technical condition (legacy, architecture compliant etc.) and development
plans. It is important that the identity management professional ensures the
development of the IAM environment is aligned with the deployment of new
applications and development of legacy applications.

The application portfolio should also define if and how applications require
provisioning. For application that maintain identity data the identity manager
should be able to provision automatically, via an approval workflow. But in some
circumstances the permissions rules that have been developed over many years
make automated provisioning too complex. For instance, an ERP system with
multiple permission levels may have more “roles” than users which makes it hard
to automate. In other cases manual assignment of permissions will be mandated by
the organization. For instance, some acute care medical facilities require the
IAM provisioning system to use a manual interface to grant access to certain
medical applications. In these instances the identity manager system will place
the provisioning request on the appropriate service desk queue.

Critical to the IAM environment is the ability to support a wide variety of
applications from legacy client-server apps to cloud-based containerized apps.
This effectively mandates an API approach that application developers can code
to. The IAM environment will need to support a number of APIs depending upon the
breadth of the application portfolio.

Note: APIs are required for the IAM environment to be able to provision into an
application that maintains its own identity repository for access entitlements.
Applications that utilize an external data store will use a standard interface
to query a central identity provider service whenever a user attempts to access
the app.
