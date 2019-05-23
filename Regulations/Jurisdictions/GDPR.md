Abstract
========

The General Data Protection Regulation (GDPR) applies to any processing
(including collection, storage or sharing) of data relating to
identifiable (including by serial numbers, IP addresses, etc.)
individuals who are physically in Europe. This may well cover
international or on-line IDM activities as well as those actually
conducted in Europe. All such processing must conform to seven
principles: lawfulness, fairness & transparency; purpose limitation;
data minimisation; accuracy; storage limitation; integrity &
confidentiality; accountability. Individuals have rights of information;
subject access; rectification, erasure & restriction. Processing must be
for one of six legal bases: contract, legal obligation, vital interests,
public interests, legitimate interests, or consent. Each basis has its
own requirements; some confer additional rights on individuals. These
requirements are broadly compatible with well-designed IDM systems; and
the use of IDM may well make it easier for other activities to be done
in accordance with the GDPR's requirements.

Introduction
============

The *General Data Protection Regulation (GDPR)*, which came into force
in all EU member states on 25^th^ May 2018, applies when processing 'any
information relating to an identified or identifiable natural
person'.[^1] The inclusion of 'identifiable' makes it much broader than
most privacy laws: IP addresses, MAC addresses of personal devices,
account numbers, and even unique combinations of attributes may be
sufficient to bring an activity within its scope. The range of
activities covered is similarly wide: including 'collection, recording,
organisation, structuring, storage, adaptation or alteration, retrieval,
consultation, use, disclosure by transmission, dissemination or
otherwise making available, alignment or combination, restriction,
erasure or deletion'.[^2] Since the GDPR covers all individuals
physically in Europe -- there is no citizenship or similar requirement
-- it may well apply to the international or on-line activities
operations of organisations elsewhere in the world.

IDM activities are likely to be regulated by the GDPR, however effective
IDM may make it easier for organisations to comply with the law's
requirements. The behaviour it prescribes is increasingly expected, not
only in Europe, but in the increasing number of countries subscribing to
the Council of Europe's Convention 108.[^3] Within Europe there are
significant fines for contravention of the GDPR, but following its
principles should have benefits for the reputation and efficient
operation of organisations anywhere in the world.

This \#chapter\# is not a complete guide to the GDPR, but covers those
aspects most relevant to IDM. It first describes the general principles
and obligations that apply to all personal data processing; then
examines the permitted legal bases for processing and the specific
obligations and rights associated with them.

Terminology
===========

**General Data Protection Act (GDPR).** Formally, Regulation 2016/679 of
the European Union, in force 25^th^ May 2018. Available at
<https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32016R0679>

**Personal Data.** Defined in Article 4(1) of the GDPR: "'personal data'
means any information relating to an identified or identifiable natural
person ('data subject'); an identifiable natural person is one who can
be identified, directly or indirectly, in particular by reference to an
identifier such as a name, an identification number, location data, an
online identifier or to one or more factors specific to the physical,
physiological, genetic, mental, economic, cultural or social identity of
that natural person;". Note: "natural person" (human) is used to
distinguish from companies and other corporate entities that are "legal
persons".

**Processing.** Defined in Article 4(2) of the GDPR: "'processing' means
any operation or set of operations which is performed on personal data
or on sets of personal data, whether or not by automated means, such as
collection, recording, organisation, structuring, storage, adaptation or
alteration, retrieval, consultation, use, disclosure by transmission,
dissemination or otherwise making available, alignment or combination,
restriction, erasure or destruction". Note that even this long list of
activities is not exhaustive: other activities may also fall within the
definition of "processing".

**Special Category Data (SCD).** Categories of data that are regarded as
particularly sensitive, so subject to additional regulation. Defined in
Article 9(1) of the GDPR as "personal data revealing racial or ethnic
origin, political opinions, religious or philosophical beliefs, or trade
union membership, and the processing of genetic data, biometric data for
the purpose of uniquely identifying a natural person, data concerning
health or data concerning a natural person's sex life or sexual
orientation"; Article 10's "personal data relating to criminal
convictions and offences" requires similar treatment, so is normally
considered as another category of SCD.

**Data Controller.** Defined in Article 4(7) of the GDPR: "'controller'
means the natural or legal person, public authority, agency or other
body which, alone or jointly with others, determines the purposes and
means of the processing of personal data;". This \#chapter\# uses the
term "organisation" as a synonym for "data controller", since
organisations involved in IDM will normally be data controllers.

**Data Subject.** Defined in Article 4(1) of the GDPR (see "Personal
Data" above) as the formal term for the human to whom personal data
relates. This \#chapter\# uses the term "individual" as a synonym for
"data subject".

Rules for Personal Data
=======================

The GDPR places most of its obligations on organisations that
"determine\[\] the purposes and means of the processing of personal
data" (Art 4(7)): these organisations are referred to as *Data
Controllers*. Some organisations may process data solely on behalf of
others -- not determining the purposes and means -- these are known as
data processors, and have fewer obligations. Since IDM systems are
likely to act as data controllers, their main obligations are described
here. The fundamental obligations on all data controllers are to act in
accordance with seven principles, and to satisfy obligations to, and
rights of, individuals ("*data subjects*") whose information they
process.

Principles (Art 5)
------------------

According to GDPR Article 5, the following principles apply to all
processing of personal data:

-   **Lawfulness, Fairness, Transparency**: all processing must be
    covered by one of the six legal bases set out in the GDPR (see
    below) and must not breach other laws; it should not be deceptive,
    any activities that individuals might be surprised by should be
    explained and justified as must any adverse effects on individuals;
    organisations should be open about their processing, in particular
    through the rights to information and subject access described
    below.

-   **Purpose Limitation**: the purposes for which information is
    processed must be clearly stated; existing information may only be
    used for new purposes if, either, the new purpose is compatible with
    the existing ones (roughly summarised as 'not surprisingly
    different'), or it is required by law, or each individual has given
    consent to the new purpose.

-   **Data Minimisation**: the data and processing must be relevant to
    the purpose, sufficient to achieve it ("adequate"), but not
    excessive. Well-defined IAM systems should contribute to data
    minimisation: for example federated systems can reduce disclosure by
    using opaque identifiers ("pseudonyms") that allow an individual to
    be recognised when they return to a system, without identifying
    them.

-   **Accuracy**: personal data must be accurate and up to date.
    Although individuals have the right to correct errors in their data
    (see "right of rectification" below) organisations should not rely
    on them doing so as the sole, or even principal, way to ensure
    accuracy. IAM systems that act as a single source of truth for their
    organisations should make accuracy significantly easier to achieve.

-   **Storage \[time\] Limitation**: personal data must not be kept for
    longer than needed for the stated purpose(s). Before collecting
    personal data, organisations should know, and declare, how long they
    will keep it for, either in relation to a fixed time period (e.g.
    'six months'), or a known event (e.g. 'until you leave').
    Organisations should have processes to ensure their stated retention
    periods are implemented; at the end of them data should be deleted
    or anonymised. The purposes of archiving, research and statistics
    may allow personal data to be kept for longer, but subject to
    specific conditions in both European and national laws.

-   **Integrity and Confidentiality**: organisations must use
    appropriate technical and organisational controls to protect the
    security of personal data. What is appropriate will depend on the
    sensitivity of the data and the purpose: it is likely to change both
    as new protective technologies and approaches become available and
    as new threats and risks become apparent. The GDPR imposes specific
    obligations if there is a breach of security, which are described
    below. IDM systems should help both by holding their own personal
    data securely, and by providing a tool that can be used to protect
    authorised access to other personal data in the organisation.

-   **Accountability**: organisations must be able to demonstrate that
    they are complying with the principles and other requirements of the
    Regulation.

Obligations and Rights
----------------------

Three groups of "rights" apply to all processing of personal data,
except where limited exceptions apply. Two need to be exercised by
individuals; the first is in fact an obligation on organisations:

-   **Rights to Information**: two articles support the above principles
    by stating the minimum information that must be provided to all
    those whose personal data are processed by the organisation. Article
    13 applies when data are collected directly from the individual;
    Article 14 when an organisation obtains personal data from another
    source (including public sources). In each case, the required
    information includes who the organisation is, what data are being
    processed, why, for how long, whether automated decisions are
    involved; any additional organisations or further processing; how to
    exercise your rights.

-   **Subject Access Right**: individuals have a general right, under
    Article 15, to ask and be told whether their data are being
    processed, what data, why, for how long, whether automated decisions
    are involved; the source of the data and any recipients; how to
    exercise their rights. In addition, if this can be done without
    affecting the rights of others, the individual has a right to
    receive a copy of their own data.

-   **Rights of Rectification/Erasure/Restriction**: Article 16
    ("rectification") entitles individuals to correct inaccurate
    personal data, including to add additional information. Article 17
    ("erasure") entitles individuals to have their personal data deleted
    if there is no lawful basis for it to be kept. This might arise, for
    example, when excessive information is held, if it has been kept
    beyond its retention time, or, if it was being processed on the
    basis of consent (see below) when that consent has been withdrawn.
    Article 18 ("restriction") entitles an individual to block further
    processing of their data (including deletion) while a rectification
    or objection right is being processed, or as an alternative to
    erasure if the individual needs the data for a legal claim. IDM
    systems, by providing a single point of truth and control, should
    make it easier to implement these rights.

Legal Bases for Processing
==========================

To be lawful, any activity that involves processing personal data must
be covered by one of the six legal bases set out in Article 6 of the
GDPR. Note that the basis applies to a particular processing activity,
not to a dataset. As illustrated in the example below, an IDM system may
involve several different legal bases.

Various types of personal data -- including race, ethnicity and health
-- are considered higher risk and processing must be for one of the
purposes set out in Article 9, as well as having an Article 6 basis. The
requirements on processing these types -- known as *Special Category
Data* -- are often set in national, rather than European, legislation.
IDM systems that process them should therefore consult lawyers familiar
with the relevant national schemes. Similarly, although the GDPR
highlights the extra risks involved in children's personal data, the
specific requirements -- including the age below which someone is
considered a child -- are largely set at national level, so are not
covered here.

Each of the Article 6 bases imposes additional conditions on processing,
both by its definition and, in some cases, by explicit additions.
Several of the bases also create additional obligations for
organisations processing personal data and/or rights for individuals
whose personal data are processed. The following sections describe these
legal bases; here they are set out in the likely order of preference for
organisations, rather than that in which they are listed in the
legislation; those at the bottom of the list are significantly more
onerous.

Necessary for the Performance of a Contract
-------------------------------------------

Five of the legal bases begin "necessary for...". Regulators have
confirmed that this means there must be no less intrusive way to achieve
the purpose.

The inclusion of "performance of" indicates that there must be a
particularly close link between the processing and the subject of the
contract; the individual whose data are processed must also be a party
to the contract. However the term "contract" is likely to be widely
interpreted, covering many situations where parties have made an
agreement, even without a formal contract document. If stopping
processing would make that agreement impossible to fulfil, then
"necessary for contract" may well be an appropriate basis. This is
likely to apply to many IDM systems, for example those provided by an
employer or educator. Even for stand-alone IDM systems -- so long as
there is a direct relationship between the individual and the IDM
provider -- using "necessary for contract" may be a useful way to
distinguish the minimum data and processing without which the service
cannot function from optional data that the system can use but does not
need. The latter should use the basis of "consent" described below.

Where personal data are processed on this basis, the GDPR introduced a
Right to Portability (Art.20) covering data "which \[the individual\]
has provided". This right may therefore cover only a subset of the
information available under the general Subject Access Right, though the
information must be provided "in a structured, commonly used and machine
readable format". So far, Regulators have only provided high-level
guidance on this right,[^4] including suggesting that CSV might fulfil
the format requirements, so further developments are likely.

Necessary for Compliance with a Legal Obligation
------------------------------------------------

Where a European or Member State law requires an organisation to process
personal data, this is likely to be the appropriate legal basis. It is
possible that this might apply to some national IDM schemes, but
otherwise it is unlikely to be relevant.

Necessary in Order to Protect Vital Interests
---------------------------------------------

This legal basis may apply when there is a threat to life or serious
injury. We should hope that it is not relevant to our IDM systems!

Necessary for the Performance of a Task Carried out in the Public Interest
--------------------------------------------------------------------------

This legal basis is typically used where a law permits processing for a
public interest task, but does not require it. Since national IDM
schemes will normally be subject to a legal requirement (see "legal
obligation" above), rather than a permission, it seems unlikely to be
relevant to IDM systems.

This basis gives individuals the Right to Object to processing, as
described under "legitimate interests" below.

Necessary for the Legitimate Interests of the Controller or a Third Party
-------------------------------------------------------------------------

Whereas the first four bases cover specific situations defined in law
the last two ("legitimate interest" and "consent") are more flexible,
and are therefore subject to more onerous requirements to protect
individuals. This Legitimate Interests basis requires not just that the
processing be necessary to achieve a specific purpose (the "interest")
but also that that interest be "legitimate" and, uniquely, that the
benefits of processing not be overridden by its risks to individuals. A
processing activity may be necessary for a legitimate interest, but
still be unlawful if it cannot satisfy this balancing test.

Legitimate interest will, however, often be the most appropriate legal
basis for multi-party IDM. Organisations participating in federations --
whether as identity providers, service providers, attribute authorities,
or otherwise -- are unlikely to know enough about the user's reason for
making a particular request to know whether it is necessary for a
contract or, conversely, a situation where the individual is able to
give free consent. Rather than trying to communicate that information
among multiple parties or establishing a mesh of contracts among them,
it is often simpler to consider the interest of each individual
organisation in providing the service that the individual -- by
initiating an authentication or authorisation process -- has requested
of them.

This basis can only be used if "such interests are not overridden by the
interests or fundamental rights and freedoms of the \[individual\] which
require protection of personal data" (Art 6(1)(f)). Before an IDM
organisation considers releasing (or requesting) information on this
basis, it must therefore consider what risks might arise to the
individual as a result of that disclosure. The mention of "fundamental
rights and freedoms" indicates that risks beyond just data protection
should be considered. Although this might appear onerous, the process
can often be simplified, and implemented in the form of attribute
release policies, by considering the types of data involved and what is
known about the entities that will receive the information. Releasing a
low-risk attribute to an organisation that has committed (or is required
by its own applicable laws) to only use such data for service provision
might be considered an acceptable risk, given that the individual must
first have chosen to request federated authentication to that
organisation's services.

When using the legitimate interests basis, each individual has a "Right
to Object" under Art.21. The legal requirement is to consider whether
the organisation has "compelling legitimate grounds" for continuing the
processing, in which case it may do so. In practice, since IDM systems
should in any case only be processing the minimum information necessary
to provide their service to users, an objection is effectively a request
to stop using those parts of the service that rely on Legitimate
Interests. An organisation might, therefore, respond to such a request
by checking that that is, indeed, the individual's intention.

Consent
-------

The only legal basis that does not contain the word "necessary" is that
the individual has given consent to processing. However this is subject
to significant conditions -- in Article 7 and Recitals 32, 42 & 43 --
which are likely to make consent inappropriate for much of the
processing involved in IDM. Consent must be indicated by "a clear
affirmative act establishing a freely given, specific, informed and
unambiguous indication of the \[individual's\] agreement"; it must be
possible to withdraw consent at any time, as easily as it was given;
consent will not be valid "if the \[individual\] has no genuine or free
choice or is unable to refuse or withdraw consent without detriment".
Consent sought by an employer, public authority or other organisation
with similar power over the individual is presumed not to be free.
Consent must not be sought as a condition of providing a service.
Organisations relying on consent must be able to demonstrate that it was
obtained in accordance with these conditions. As for "contract" above,
the Right to Portability applies to information obtained using consent.

Summary
-------

The "necessary" bases -- usually either contract, legitimate interest or
legal obligation -- are more suitable for the information necessary to
maintain the relationship between the individual and the IDM system.
With these the organisation does not have to worry whether lawful
consent was obtained, nor that it might be withdrawn on a whim. Consent
should be reserved for information that the IDM system can handle but
does not need: circumstances that are much more likely to satisfy the
requirements for it to be valid. Consent, according to the UK's Data
Protection Regulator, should be an offer to the individual to enter into
a deeper, more trusting, relationship.

The same legal mechanisms can also be used to satisfy the GDPR's rules
on exporting personal data from Europe. Regular transfers of personal
data (for example between a customer organisation and a non-European IDM
supplier) should normally be covered by a contract including one of the
sets of Standard Contract Clauses;[^5] occasional, ad hoc, low-risk
transfers should be able to use the legitimate interests basis; consent
may be used where the individual is free to choose whether or not their
personal information are transferred.

Security
========

As well as requiring organisations to take proactive measures to protect
the security of personal data, Article 33 of the GDPR introduces a
requirement to report some breaches to the relevant national Regulator.
When an organisation detects a "breach of security leading to the
accidental or unlawful destruction, loss, alteration, unauthorised
disclosure of, or access to, personal data transmitted, stored or
otherwise processed" it must report this to the Regulator unless the
breach is "unlikely to result in a risk to rights and freedoms of
natural persons". Loss of an encrypted memory stick, while the
decryption key remains secure, is often given as an example of a breach
that does not need to be reported. The expectation is that such reports
will be sent within 72 hours: if not then an explanation for the delay
must be included. Where a breach is likely to involve a "high risk" to
individuals' rights and freedoms, then notification to affected
individuals is required under Article 34.

The GDPR recognises in Recital 49 that the ability to detect, contain
and remedy security breaches is an important part of keeping data
secure. Processing of personal data such as access and activity logs
required for those purposes is recognised as a legitimate interest (so
permitted, subject to the balancing test). IDM can play a significant
role in mitigating security breaches, by disabling compromised accounts
quickly and effectively; its logs may also provide early warning when an
organisation is under attack.

IDM Example
===========

The following example shows one way that IDM systems can support the
GDPR.

Janet is a professor at the University of Erewhon. The university has a
central IDM system containing the details of all staff required for them
to do their jobs. This information is stored and processed on the legal
basis that it is necessary for Janet's contract of employment with the
university: without doing so, it would be impossible to perform that
contract. The IDM system acts as a single point of truth, so ensuring
that information is up to date throughout the university and that any
correction requests can be easily implemented.

The IDM system also allows Janet to store optional information, such as
her personal interests, that will appear on her staff webpage. Since she
can add, change or remove these at any time, without affecting her work,
the appropriate legal basis is consent.

The university is also a member of an AAI Federation. When Janet
accesses a website of another Federation member (for example a journal
publisher) she can choose to log in with her university credentials. A
wide variety of organisations are Federation members: Janet needs to
access some of these for her work, but others may be just for personal
interest. Since neither the University nor the sites wish to work out
which sites are necessary for contract and which accessed with free
consent (where Janet needs to access a site for work, her consent cannot
be free) they both use the legal basis that the processing is necessary
in their legitimate interest in helping Janet access the information she
wants.

The legitimate interests basis requires the university to balance the
risks of releasing information against the benefits. Since the
federation agreement requires members only to use authentication and
other attributes for the purposes of service provision and
personalisation, the university assesses that there is very little risk
in releasing a unique opaque identifier and Janet's status as a member
of staff to any Federation member; it has therefore configured its
systems to release that information by default when a user requests a
federated login. This is sufficient both for Janet to access online
journals, and to verify her entitlement to a staff discount at the local
health club.

The Federation has defined a class of services that are specifically
designed for Research and Education use, and that require a name and
email address in addition to the opaque identifier and status. Although
this disclosure involves a slightly higher risk, the university is
satisfied that this is justified by the greater benefit; such services
will therefore receive the additional information by default. This
allows Janet to use discussion groups and virtual research environments
in her field.

Where services ask for more information, the university will perform an
individual assessment of the benefit and risk. This may indicate that
additional measures, such as a bilateral contract or the free consent of
each individual, are required to reduce the risk of the disclosure.

Author Bio
==========

Andrew Cormack is Chief Regulatory Adviser at Jisc. He has been involved
in the technical and policy development of federated identity systems in
the UK, Europe, and globally for more than fifteen years. He has spoken
and written extensively on how digital technologies can be used to
improve privacy and data protection and, more recently, on the
application of the GDPR to them. His publications can be found at
<https://orcid.org/0000-0002-8448-2881> and his blogs at
<https://community.jisc.ac.uk/blogs/regulatory-developments>.

Endnotes
========

[^1]: \#GDPR Art.4(1)

[^2]: \#GDPR Art.4(2)

[^3]: \#https://www.coe.int/en/web/data-protection/home

[^4]: \#https://ec.europa.eu/newsroom/article29/item-detail.cfm?item\_id=611233

[^5]: \#https://ec.europa.eu/info/law/law-topic/data-protection/data-transfers-outside-eu/model-contracts-transfer-personal-data-third-countries\_en
