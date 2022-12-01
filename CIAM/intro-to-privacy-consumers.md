<div id="header">

</div>

By Clare Nelson

© 2022 IDPro, Clare Nelson

Updated by the IDPro Body of Knowledge Committee

*To comment on this article, please visit our [GitHub
repository](https://github.com/IDPros/bok) and [submit an
issue](https://docs.github.com/en/github/managing-your-work-on-github/opening-an-issue-from-code)
.*

<span id="_Toc42329703" class="anchor"> </span>

***Disclaimer***

*This article should not be considered legal advice. Identity programs
that support data protection and privacy as a fundamental human right
are complex and highly technical. Many of the data protection and
privacy laws in countries around the world are evolving and open to
interpretation. Please consult your organization's legal counsel for
specific advice appropriate to your jurisdiction*

Related Sections in the IDPro Body of Knowledge
===============================================

Please refer to other forthcoming sections of the *IDPro Body of
Knowledge*
<a href="#fn1" id="fnref1" class="footnoteRef"><sup>1</sup></a> for
supporting and complementary information, notably:

-   Andrew Cormack’s “An Introduction to the GDPR”
    <a href="#fn2" id="fnref2" class="footnoteRef"><sup>2</sup></a>

-   Andrew Hindle’s “Impact of GDPR on Identity and Access Management”
    <a href="#fn3" id="fnref3" class="footnoteRef"><sup>3</sup></a>

-   “Terminology in the IDPro Body of Knowledge”
    <a href="#fn4" id="fnref4" class="footnoteRef"><sup>4</sup></a>

Introduction to Privacy and Compliance for Consumers
====================================================

Identity professionals, including enterprise solution architects, data
scientists working in marketing, privacy professionals, product
managers, and strategists at data brokers, have an opportunity to
improve privacy plus compliance with data protection regulations and
laws for consumer-facing applications. Several critical issues drive the
need for improvement:

1.  Unique identification of a *natural person,* such as a consumer, is
    easier than ever before. The smallest shred of digital exhaust,
    physical actions, or attributes can be collected, correlated via
    machine learning, and analyzed to identify a unique consumer or
    household with sufficient probability.

2.  Consent is broken. The complexity of privacy notices, and the length
    of privacy policies that are rarely read, lead to a pattern of
    ineffectiveness, the illusion of choice, burden on the consumer, and
    the eventual agreement to broad terms which may not have limits or
    may be modified at any future date with only limited or obscure
    notice. As privacy and law expert Daniel Solove has stated, "Giving
    individuals more tasks for managing their privacy will not provide
    effective privacy protection."
    <a href="#fn5" id="fnref5" class="footnoteRef"><sup>5</sup></a>
    There is a growing realization that privacy laws should make
    stewardship of data the responsibility of the data controller and/or
    data processor, not the consumer.

3.  Data privacy laws are years behind technology innovations, and the
    gap is expanding. Privacy laws cannot keep pace with technological
    advancements and are years behind in catching up to the 4,000 data
    brokers and analytics companies that collect personal data across
    all touchpoints, many of which are adding muscle with machine
    learning. Many marketing companies, plus some of the world's largest
    organizations, are seeking alternatives to third-party cookies in
    order to be able to continue to identify consumers, all within the
    porous guidelines of current privacy law.

4.  Anonymity does not exist, and pseudonymization provides weak
    protection

    1.  For example, researchers have proved that based on geolocation
        alone, anonymity does not exist.
        <a href="#fn6" id="fnref6" class="footnoteRef"><sup>6</sup></a>

    2.  Similarly, researchers posit that it is becoming easier to
        re-identify a person:

        1.  Once released to the public, data cannot be taken back. As
            time passes, data analytic techniques improve, and
            additional datasets become public that can reveal
            information about the original data. It follows that
            released data will get increasingly vulnerable to
            re-identification—unless methods with provable privacy
            properties are used for the data release.
            <a href="#fn7" id="fnref7" class="footnoteRef"><sup>7</sup></a>

    3.  *Communications of the ACM* recently published an article on
        anonymity that confirms what many mathematicians have always
        known: there is still a pattern in the anonymous data and a way
        to de-anonymize it.
        <a href="#fn8" id="fnref8" class="footnoteRef"><sup>8</sup></a>

        1.  "Anonymized data can never be totally anonymous:
            anonymization is not sufficient for private companies to
            avoid conflicts with laws such as Europe's General Data
            Protection Regulation, and the California Consumer Privacy
            Act."
            <a href="#fn9" id="fnref9" class="footnoteRef"><sup>9</sup></a>

The scope of privacy for what the GDPR calls *natural persons* keeps
expanding because the ability to uniquely identify a human being with
the tiniest bit of digital exhaust or trace of online or offline
behavior keeps expanding. Where a person ate lunch, the way they moved
their mouse to find the cursor, what they said to a service
representative over the phone in light of the warning, "this call may be
recorded for quality purposes," what they bought online, their device
and all its related attributes, or where they bought gas may be
sufficient to uniquely identify a natural person. Long gone are the days
when name, address, social security number, and date of birth were the
only identifiers. Now, we need to protect massive collections of
personal and related data in order to provide privacy for consumers.

Terminology and Acronyms
------------------------

-   Consent - permission for something to happen or agreement to do
    something

-   GDPR – General Data Protection Regulation
    <a href="#fn10" id="fnref10" class="footnoteRef"><sup>10</sup></a>

-   CCPA – California Consumer Privacy Act
    <a href="#fn11" id="fnref11" class="footnoteRef"><sup>11</sup></a>

-   Natural Person – an individual human being

-   NY SHIELD Act – New York "Stop Hacks and Improve Electronic Data
    Security" Act
    <a href="#fn12" id="fnref12" class="footnoteRef"><sup>12</sup></a>

-   Privacy - an abstract concept with no single, common definition

Scope
=====

The lofty goal of this section on *Privacy and Compliance for Consumers*
is to present a global perspective. However, the initial release of this
section is more focused on the GDPR, CCPA, and NY SHIELD Act with a
light coverage of China and the rest of the world. As noted below in the
Resources section, the International Association of Privacy
Professionals (IAPP) is an excellent source of information for
immediate, current, comprehensive global coverage.

Requirements for data protection and associated privacy regulations are
increasing around the world. On March 21, 2020, the NY SHIELD Act went
into effect, and China is working on updated privacy law. Most are
familiar with the GDPR and CCPA.
<a href="#fn13" id="fnref13" class="footnoteRef"><sup>13</sup></a> The
figure below highlights global regulation and enforcement as heavy,
robust, moderate, or limited.

<img src="image1.png" width="624" height="308" alt="Geo-political map color coding the range of privacy regulation and enforcement within each country, from Heavy, to Robust, to Moderate, to Limited. Countries including the US, Canada, China, Australia, and most of Europe are coded as &quot;Heavy&quot;, where as Rusia, Turkey, Egypt, Mexico, and Brazil (among other) are marked as Moderate. " />

Figure 1 - Global Privacy Regulation Varies from Heavy to Limited
<a href="#fn14" id="fnref14" class="footnoteRef"><sup>14</sup></a>

In addition to a global scope, this section covers digital identities –
including online services and apps – as well as physical interactions
(e.g., customers entering a store or service establishment).

In this section, we consider personal data obtained, stored, or tracked
through a variety of mechanisms, including cookies, electronic
communications (Internet, email, messaging, apps), Wi-Fi, telephone, and
Internet-of-Things (IoT). All of this data can be used to identify a
unique individual and may be considered private, requiring protection as
a *fundamental human right* . The first recital of the GDPR states that
data protection is a *fundamental right* according to the [Charter of
Fundamental Rights of the European
Union](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:12012P/TXT)
and the [Treaty on the Functioning of the European Union
(TEFU)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A12012E%2FTXT)
. <a href="#fn15" id="fnref15" class="footnoteRef"><sup>15</sup></a>
<sup>,</sup>
<a href="#fn16" id="fnref16" class="footnoteRef"><sup>16</sup></a> The
United Nations adopted the [Universal Declaration of Human
Rights](https://www.un.org/en/universal-declaration-human-rights/) in
1948, a global mandate for privacy, as articulated in Article 17:
<a href="#fn17" id="fnref17" class="footnoteRef"><sup>17</sup></a>

> No one shall be subjected to arbitrary interference with his privacy,
> family, home or correspondence, nor to attacks upon his honour and
> reputation. Everyone has the right to the protection of the law
> against such interference or attacks.

|                  |                               |                                                                                           |                                          |                                                              |                                             |
|------------------|-------------------------------|-------------------------------------------------------------------------------------------|------------------------------------------|--------------------------------------------------------------|---------------------------------------------|
|                  | EU GDPR                       | EU ePrivacy Directive                                                                     | US CCPA, NY **SHIELD** , other           | California, Oregon IoT Security Law; Singapore, others       | Rest of the World                           |
| What is covered? | Personal data, cookie consent | Cookies, Internet, email, messaging, phone; tracking mechanisms, right of confidentiality | Personal data, household data under CCPA | Any connected device; has an IP address or Bluetooth address | China - none; APEC - Personal Information\* |

Table 1. Beyond GDPR: Personal Data Includes Cookies, Phone, and IoT

\*According to the [Asia-Pacific Economic Cooperation (APEC) Privacy
Framework](https://www.apec.org/Press/Features/2006/0101_APEC_Privacy_Framework_Facilitating_Business_and_Protecting_Consumers_Across_the_Asia-Pacific)
, Personal Information is any information about an identified or
identifiable individual.
<a href="#fn18" id="fnref18" class="footnoteRef"><sup>18</sup></a>

The GDPR is closely related to the ePrivacy Directive. The ePrivacy
Directive is soon to be replaced with the ePrivacy Regulation. The GDPR
and ePrivacy Regulation are both parts of the data protection reform in
the EU; where there is overlap, the ePrivacy Regulation overrides the
GDPR, notably for cookies and electronic communication.
<a href="#fn19" id="fnref19" class="footnoteRef"><sup>19</sup></a>

IoT law is covered below. Note that emerging laws seek first to get rid
of embedded or hardcoded passwords. When an IoT device ships with the
password already installed from the manufacturer, this makes it easy to
breach privacy as well as to create botnet malware.

Setting the Stage
=================

Scholars and privacy experts, including Hartzog, Zuboff, Schneier, and
Maler, set the stage for examining these topics and beyond.

Hartzog
-------

Woodrow Hartzog is a Professor of Law and Computer Science at
Northeastern University, and among other roles is an Affiliate Scholar
at Stanford Law School for Internet and Society. In April 2019, Hartzog
co-authored [**The Pathologies of Digital
Consent**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3370433)
with Neil Richards, where they discuss defects that consent models can
suffer, including:
<a href="#fn20" id="fnref20" class="footnoteRef"><sup>20</sup></a>

-   Unwitting consent

-   Coerced consent

-   Incapacitated consent

These consent defects are a far cry from the *gold standard of knowing
and voluntary consent* . Hartzog and Richards conclude:

The over-use of consent in the digital context, combined with limited
legal policing of the sufficiency of consent, has allowed great fortunes
to be created on the basis of personal data, but it has also exposed
consumers to data breaches, identity theft, and a surveillance economy
unprecedented in human history, one which stretches the very notion of
"consent" to say that it was ever actually agreed to.

More fundamentally, the manufacturing of consent by exploiting consent's
pathologies has diminished the trust in our digital environment that is
the key ingredient toward a better future. We can do better, but in
order to do so, we need to recognize the pathologies of consent and
limit consent to the contexts in which it is most justified. Going
forward, we must rely on strategies other than fictive, manufactured, or
coerced consent to minimize the risks and harms of our information
economy if we seek to take advantage of its benefits in a sustainable,
ethical, and progressive way.

These consent issues are discussed further in subsequent sections,
including a proposed solution or *theory of consumer trust* as an
alternative to an over-reliance on increasingly pathological models of
consent.

Zuboff
------

In her recent, award-winning book, *The Age of Surveillance Capitalism:
The Fight for a Human Future and the New Frontier of Power* , Harvard's
Shoshana Zuboff clearly articulates her well-researched assertion that
we live in a state of *surveillance capitalism.* Zuboff's message is
clear:

"Surveillance capitalism unilaterally claims human experience as free
raw material for translation into behavioural data.

-   Although some of these data are applied to service improvement, the
    rest are declared as a proprietary behavioural surplus, fed into
    advanced manufacturing processes known as 'machine intelligence',
    and fabricated into prediction products that anticipate what you
    will do now, soon, and later.

-   Finally, these prediction products are traded in a new kind of
    marketplace that I call behavioural futures markets.

-   Surveillance capitalists have grown immensely wealthy from these
    trading operations, for many companies are willing to lay bets on
    our future behaviour."
    <a href="#fn21" id="fnref21" class="footnoteRef"><sup>21</sup></a>

Schneier
--------

Zuboff's 2019 book on surveillance capitalism makes Bruce Schneier's
2015 book, *Data and Goliath: The Hidden Battles to Collect Your Data
and Control Your World,* pale in comparison. Consumers are left
wondering, "Why didn't you tell me it was so bad?" because Schneier does
not provide the chilling detail about how far surveillance and
collection of behavioral surplus have advanced. Zuboff's words are even
reflected in marketing messages of leading "data protection" vendors,
"Privacy is the right of an individual to be free from uninvited
surveillance."
<a href="#fn22" id="fnref22" class="footnoteRef"><sup>22</sup></a>

Maler
-----

In her 2018 Identiverse talk, [*Don't Pave Privacy Cow Paths: Retool
Consent*](https://www.youtube.com/watch?v=eP5U2sA6EFk) for the New
Mobility, ForgeRock CTO, then-VP Innovation and Emerging Technology, Eve
Maler describes why "Consent doesn't scale for the requirements of
email, laptops, and browsers, never mind mobile devices and
applications.

-   How much worse is the situation going to get as connected vehicles
    become an ever-bigger part of consumers' lives and an ever more
    significant integration point for every industry?" Maler establishes
    the "New Mobility as a critical scenario for examining consumer
    requirements for trust, regulatory requirements for privacy, how
    consent experiences and consent management must adapt, and how we
    can begin to meet these challenges."
    <a href="#fn23" id="fnref23" class="footnoteRef"><sup>23</sup></a>

Maler's words were prescient because, in the rush to implement consent
for GDPR compliance, many companies have simply paved cow paths. Her
talk describes how to refactor consent to accommodate today's
architectural requirements for asynchronicity, automation, and
abstraction.

What is Privacy?
================

Privacy is an abstract concept with many definitions and even more
potential threats when that concept is attacked. There are areas such as
handling of open-source intelligence (OSINT) that can have an enormous
impact on the individual, but where the legal parameters are poorly
specified (if they are specified at all).
<a href="#fn24" id="fnref24" class="footnoteRef"><sup>24</sup></a>
Concerns around the politicization and potential weaponization of
personal data also highlight the challenges introduced by having so many
perceptions of privacy.
<a href="#fn25" id="fnref25" class="footnoteRef"><sup>25</sup></a>

Privacy as a Fundamental Human Right
------------------------------------

The protection of personal data often refers to autonomy and control
over one's data. This level of autonomy and control varies depending on
the context. In general, the definition of privacy differs from country
to country or state by state. Even though the US is one of 48 United
Nations countries that voted to adopt the Universal Declaration of Human
Rights, the US does not share the EU's embrace of privacy as a
*fundamental human right.* For example, instead of a comprehensive,
federal law, it is building a patchwork of state-specific laws.

-   In the EU, human dignity is recognized as an absolute fundamental
    right.

-   In this notion of dignity, privacy, or the right to a private life,
    to be autonomous, in control of information about yourself, to be
    let alone, plays a pivotal role. Privacy is not only an individual
    right but also a social value.

-   The right to privacy or private life is enshrined in the Universal
    Declaration of Human Rights (Article 12), the European Convention of
    Human Rights (Article 8), and the European Charter of Fundamental
    Rights (Article 7).
    <a href="#fn26" id="fnref26" class="footnoteRef"><sup>26</sup></a>

**Westin** . In the 1960s, Privacy pioneer Alan Westin defined privacy
as "The claim of individuals, groups, or institutions to determine for
themselves when, how, and to what extent information about them is
communicated to others."
<a href="#fn27" id="fnref27" class="footnoteRef"><sup>27</sup></a>

**US Supreme Court.** In 1989, the US Supreme Court wrote, "Both the
common law and the literal understandings of privacy encompass the
individual's control of information concerning his or her person."
<a href="#fn28" id="fnref28" class="footnoteRef"><sup>28</sup></a>

**China** . In the People's Republic of China (PRC), a complex array of
laws govern personal data and privacy, due to be eclipsed by
comprehensive regulation in the future. The trend indicates "individuals
are gaining significant data protection rights in the private sectors
but cannot claim any remedies for the infringements of their privacy
carried out by the state government."
<a href="#fn29" id="fnref29" class="footnoteRef"><sup>29</sup></a>
Today, various laws apply, depending on the sector: financial services,
e-commerce, telecommunications, Internet services, content providers, or
healthcare.

**APEC** . The [*Asia Pacific Economic Cooperation (APEC) Privacy
Framework*](https://www.apec.org/Publications/2005/12/APEC-Privacy-Framework)
can be downloaded
[*here*](https://www.apec.org/Publications/2005/12/APEC-Privacy-Framework)
. The APEC Privacy Framework protects privacy within and beyond
economies and enables regional transfers of personal information that
benefits consumers, businesses, and governments. This framework is used
as a basis for the APEC Cross-Border Privacy Rules (CBPR) System. The
framework countries and participants include the countries in the map
below.

<img src="image2.png" width="624" height="358" alt="Geo-political map marking the countries participating in the APEC Cross-Border Privacy Rules System" />

Figure 2 - Map of the APEC Cross-Border Privacy Rules (CBPR) System
framework countries and participants
<a href="#fn30" id="fnref30" class="footnoteRef"><sup>30</sup></a>

Privacy Models
--------------

According to Samm Sacks, Senior Fellow Yale Law School, Paul Tsai China
Center, there are two basic privacy models: 1) China, and 2) GDPR. She
indicates that Viet Nam, Kenya, and India are more closely aligned with
China's model.
<a href="#fn31" id="fnref31" class="footnoteRef"><sup>31</sup></a> Even
though China's privacy laws are influenced by the GDPR, they are
markedly different both in detail (for example, China supports implied
consent, whereas the GDPR requires explicit consent) and in spirit (in
general, the rights of the state supersede individual rights). The
privacy dichotomy in China is evidenced by the increased protection of
consumers from technology companies such as Renren and other Chinese
Facebook counterparts, even as government surveillance intensifies.

Beyond privacy law, organizations approach privacy for consumers in a
variety of ways. The role of the identity professional is first to
understand the organization's posture with regards to privacy, security,
and risk.

Privacy Taxonomy
----------------

One of the world's leading experts on privacy law is Daniel Solove, the
John Marshall Harlan Research Professor of Law at the George Washington
University Law School. As depicted in Solove's [privacy
taxonomy](https://www.law.upenn.edu/journals/lawreview/articles/volume154/issue3/Solove154U.Pa.L.Rev.477(2006).pdf)
below, privacy has two main parties:

-   The Data Subject, or consumer

-   The Data Holders, or data processor and controller

The four main processes in the privacy taxonomy comprise:

-   Information Collection

-   Information Processing

-   Information Dissemination

-   Invasions

The four processes may be viewed in order, starting with Information
Collection and ending with Invasions. The Information Collection of data
about a Data Subject is done by the Data Holder, or data processor and
controller to put it in GDPR terms. The collection of data about a Data
Subject or individual may be done by another individual, business,
government, or external organization via surveillance or interrogation.
The Information Processing includes the storage of data and any
additional steps taken to apply something like a software algorithm to
further derive value. Insecurity refers to a lack of security.
Information Dissemination includes many harmful things that might result
if the information is part of a list of undesirable actions, including a
Breach of Confidentiality, Disclosure, Exposure, Blackmail, or
Distortion. Invasions include intrusion and decisional interference,
which Solove describes as "the government's incursion into the data
subject's decisions regarding her private affairs."
<a href="#fn32" id="fnref32" class="footnoteRef"><sup>32</sup></a>

<img src="image3.png" width="624" height="351" alt="Graphic of the Privacy Taxonomy as described by Daniel Solove, showing a path from Invasions to the Data Subject, through Information Collection and Information Processing (marked as the Data Holders) and on to Information Dissemination." />

Figure 3 - Privacy Taxonomy by Solove

*\[Permission received from author to use this graphic\]*

Privacy by Design
-----------------

Privacy by Design is the brainchild of Ann Cavoukian, one of the world's
leading privacy experts; former Information and Privacy Commissioner of
Ontario, Canada; former distinguished visiting professor at Ryerson
University, where she was also Executive Director of the Ryerson's
Privacy and Big Data Institute; and founder of [Global Privacy and
Security by Design Centre](https://gpsbydesign.org/) . Originally
published in 2009, the [Privacy by Design
Principles](https://www.ipc.on.ca/wp-content/uploads/Resources/7foundationalprinciples.pdf)
, depicted in the figure below, are an integral part of the GDPR and
subsequent GDPR-influenced privacy laws. Privacy by Design takes a
holistic, systems engineering approach and makes it clear that
compliance with regulations is not enough. Privacy by Design advances
the view that the future of privacy cannot be assured solely by
compliance with regulatory frameworks; rather, privacy assurance must
ideally become an organization's default mode of operation.
<a href="#fn33" id="fnref33" class="footnoteRef"><sup>33</sup></a>

In the Privacy by Design figure below, note that *privacy by default* is
one of the seven principles. The sharp contrast of cultural expectations
may come as a surprise to some. As a gross generalization, the EU
sensibility is to have privacy by default as the norm, whereas in the
US, privacy by default is the rare exception.

<img src="image4.png" width="523" height="510" alt="Graphic showing the seven foundational principles of Privacy by Design as described by Ann Coaoukian, including: Privacy Embedded into Design; Respect for User Privacy - Keep it User-Centric; Visibility and Transparency; Full Functionality - Positive-sum, not Zero-Sum; End-to-End Security - Full Lifecycle Protection; Privacy as the Default Setting; Proactive not REactive; Preventative not Remedial" />

Figure 4 - Privacy by Design, Seven Foundational Principles
<a href="#fn34" id="fnref34" class="footnoteRef"><sup>34</sup></a>

Cavoukian builds upon her initial Privacy by Design work in a subsequent
document, [*7 Laws of Identity, The Case for Privacy-Embedded Laws of
Identity in the Digital Age*
,](https://collections.ola.org/mon/15000/267376.pdf) where she maps
privacy fair information to the Privacy-by-Design principles, resulting
in "privacy-embedded Laws of Identity."
<a href="#fn35" id="fnref35" class="footnoteRef"><sup>35</sup></a> She
warns:

> A universal identity system will have profound impacts on privacy
> since the digital identities of people - and the devices associated
> with them - constitute personal information. Great care must be taken
> that an interoperable identity system does not become an
> infrastructure of universal surveillance.

Compliance is Necessary but not Sufficient
------------------------------------------

To a limited extent, privacy law enforces data protection. This section
applauds the advances of privacy law, plus it explores some of the
failings, flaws, and shortcomings of privacy law, including consent
issues, time lag, and reactive posture because the law cannot keep pace
with current innovations, and what Harvard's Shoshana Zuboff calls the
asymmetric power stranglehold of Google, Facebook and others that are
immune from the effective impact of privacy law because the law does not
cover much of what they do with the collection of behavioral surplus.

-   **Compliance ≠ Privacy or Security.** As an identity professional,
    remember that just because you are compliant does not mean you have
    achieved the appropriate level of privacy and security required by
    your organization (or expected by your customers), hopefully
    documented in its risk and privacy policies.

-   **Privacy Law' Gap Growth' is Exponential.** Distinguished Fellow at
    Harvard Law, Vivek Wadha explains, "The gaps in privacy laws have
    grown exponentially. These regulatory gaps exist because laws have
    not kept up with advances in technology. The gaps are getting wider
    as technology advances ever more rapidly."
    <a href="#fn36" id="fnref36" class="footnoteRef"><sup>36</sup></a>

Privacy and compliance capabilities are foundational for any Consumer
Identity & Access Management (CIAM) program because they protect the
personal data of consumers as well as safeguard organizations by
defining guidelines for compliance in alignment with the organization's
privacy, security, and risk management policies. If organizations do not
comply, there are many negative consequences, including:

-   Fines (for GDPR, up to €20 million or 4% of annual turnover,
    whichever is highest)

-   Reputational or brand damage

-   Loss of customers, loyalty erosion

-   Lawsuits

-   CEO may be held personally responsible

As an identity professional, you may be part of a team responsible for
some or all aspects of privacy and compliance for consumers. This
section will enable you to contribute and have a basic understanding of
jurisdiction, consent, and data protection across the entire
organization. For GDPR or CCPA compliance, you may interact with human
resources, product engineering, security, marketing, IT, legal, customer
support, procurement, and beyond, as shown in the figure below.

Figure 5 - How to Start Managing a Data Privacy Program, an Example
<a href="#fn37" id="fnref37" class="footnoteRef"><sup>37</sup></a>

Why Consumer Services Need Different Privacy and Compliance Strategies
----------------------------------------------------------------------

### CIAM and Workforce IAM

Privacy and compliance strategies for workforce IAM have some overlap
with CIAM, but CIAM differs in some key regards. For this reason, simply
applying workforce privacy and compliance to CIAM projects may not be
optimal. Below are some of the key differences between privacy and
compliance strategies for workforce versus CIAM projects:

-   SCALE: CIAM scale is often orders of magnitude greater to reflect a
    large consumer population versus a smaller, more predictable number
    of employees and workforce

-   CUSTOMER EXPERIENCE (CX): CX requirements for consumers are more
    demanding. For its members, IAPP provides a GDPR-centric document,
    *The UX Guide for Getting Consent:*

    -   *"Consent is at the very heart of data protection and privacy,"*
        and while it is important, it is not the be-all and end-all of a
        privacy program. For example, a layered or intelligent privacy
        notice strategy can help make privacy interactions less
        cumbersome.

    -   The data subject must have a say in how personal data is
        collected, used, shared, and destroyed.

    -   Even if a choice doesn't appear to be promoted, wording, widget,
        and sequence matter.
        <a href="#fn38" id="fnref38" class="footnoteRef"><sup>38</sup></a>

-   LAW: Depending on the jurisdiction, the privacy law may differ in
    some cases for IAM versus CIAM.

-   AUTOMATION: Appropriate levels of automation differ to meet spikey
    or unpredictable consumer demand.

-   ADVERTISING: Online behavioral advertising in particular, and any
    advertising in general, is typically aimed at consumers, not the
    workforce.

-   MACHINE LEARNING AND PROFILING: What the GDPR refers to as
    "automated processing", including profiling (automated processing of
    personal data to evaluate certain things about an individual); plus,
    machine learning is often applied to consumer data for different
    purposes for the workforce versus consumers.

### CIAM and Social Identity

CIAM often relies on integration with social media identity providers.
There are several benefits to this direction, including reducing
end-user friction during sign-up and self-service registration,
generating fewer usernames and passwords for the end-user to memorize,
and simplified business processes that allow for outsourcing user
account recovery processes. This integration is not without drawbacks,
however, as integration with social media identity providers may enable
cross-site tracking of users without their permission.

Security is Critical
--------------------

Identity professionals need to understand their organization's risk
management policies for security and privacy and work in concert with
their colleagues who create those policies, as well as those responsible
for the implementation of the policies. The security policy is a
necessary dependency for any successful privacy policy. There is a
saying, "You can have security without privacy, but you can't have
privacy without security."
<a href="#fn39" id="fnref39" class="footnoteRef"><sup>39</sup></a>
Security or cybersecurity may be used interchangeably. Some also use the
term information security. In the figure below from the NIST Privacy
Framework, the relationship between cybersecurity risks and privacy
risks makes it clear that managing cybersecurity risk may help mitigate
privacy risk, but it is not sufficient because privacy risk can result
from incidents outside the realm of cybersecurity incidents. For
example, smart meters or smart thermostats may collect and record
personal data and possibly represent a privacy risk even though they are
operating as intended.

<img src="image6.png" width="442" height="258" alt="Venn diagram of two circles: Cyber Risks (associated with cybersecurity incidents arising from loss of confidentiality, integrity, or availability) and Privacy Risks (associated with privacy events arising from data processing). In the overlap is Cyber security-related privacy events." />

Figure 6 - Relationship Between Cybersecurity Risks and Privacy Risks
<a href="#fn40" id="fnref40" class="footnoteRef"><sup>40</sup></a>

Privacy Policy is a Business Decision
-------------------------------------

An in-depth understanding of an organization's policies will provide
clarity for the identity professional's role in privacy and compliance
for consumers. For example, in some cases the marketing department may
need to collect extensive personal data, and the organization's privacy
policy may allow this. In other cases, the organization's business may
depend on trust and confidentiality of personal data; and there may be
ample budget to ensure data protection for consumers in a visible,
transparent, and robust manner.

<img src="image7.png" width="624" height="198" alt="Three-part image starting with the Problem arising from data processing, then to the Individual experiences direct impact (eg, embarassment, discrimination, economic loss), and finally to Organization reulting impact (e.g, customer abandonment, noncompliance costs, harm to reputation or internal culture)" />

Figure 7 - Relationship Between Privacy Risk and Organizational Risk
<a href="#fn41" id="fnref41" class="footnoteRef"><sup>41</sup></a>

How an organization deals with consumer privacy and any associated risk
is a business decision; the option to mitigate, transfer, avoid, or
accept risk may be made in concert with privacy policy formulation or at
a later time.

-   **Mitigate** . Mitigating the risk (e.g., organizations may be able
    to apply technical and/or policy measures to the systems, products,
    or services that minimize the risk to an acceptable degree);

-   **Transfer** . Transferring or sharing the risk (e.g., contracts are
    a means of sharing or transferring risk to other organizations,
    privacy notices, and consent mechanisms are a means of sharing risk
    with individuals);

-   **Avoid** . Avoiding the risk (e.g., organizations may determine
    that the risks outweigh the benefits, and forego or terminate the
    data processing); or

-   **Accept** . Accepting the risk (e.g., organizations may determine
    that problems for consumers are minimal or unlikely to occur;
    therefore, the benefits outweigh the risks, and it is not necessary
    to invest resources in mitigation).
    <a href="#fn42" id="fnref42" class="footnoteRef"><sup>42</sup></a>

Is Privacy a Competitive Advantage?
-----------------------------------

As noted above, laws and regulations typically lag innovative product
and service offerings. Compliance with current and upcoming privacy laws
is only the start. Privacy may be a competitive advantage or not. It
depends on your organization and its consumers. In 2010, data protection
pioneer and expert Alan Westin was paraphrased, "The idea that privacy
can be used as a business advantage is dead, privacy controls are too
complex for consumers to understand and a certification culture would be
more effective."
<a href="#fn43" id="fnref43" class="footnoteRef"><sup>43</sup></a>
Others take the counterargument. Organizations realize that many
consumers would enjoy greater control over their data. Privacy for
consumers is an opportunity to build trust. Among others, a GDPR and
CCPA paper from Akamai provides "tips to build customer trust through
regulatory compliance and identity governance."
<a href="#fn44" id="fnref44" class="footnoteRef"><sup>44</sup></a>

Beyond GDPR: ePrivacy and the New European Strategy for Data
------------------------------------------------------------

In February 2020, the EU published "A European Strategy for Data." The
continuous advancement and proven EU leadership in data protection is a
driving force for the rest of the world.

The European Strategy for Data is sector-specific, e.g., healthcare, and
provides for:

-   Data can flow within the EU and across sectors.

-   European rules and values, in particular personal data protection,
    consumer protection legislation, and competition law, are fully
    respected.

-   The rules for access to and use of data are fair, practical, and
    clear, and there are clear and trustworthy data governance
    mechanisms in place; there is an open but assertive approach to
    international data flows based on European values.
    <a href="#fn45" id="fnref45" class="footnoteRef"><sup>45</sup></a>

Through its focus on data sovereignty and supporting the privacy of
people in its constituency, the European Union provides model guidance
on newer technologies such as Decentralized Identity (DID) and
Verifiable Credentials. Captured in large part in the Regulation on
electronic identification and trust services (eIDAS Regulation), this
regulation:

-   ensures that people and businesses can use their own national
    electronic identification schemes (eIDs) to access public services
    available online in other EU countries;

-   creates a European internal market for trust services by ensuring
    that they will work across borders and have the same legal status as
    their traditional paper-based equivalents.
    <a href="#fn46" id="fnref46" class="footnoteRef"><sup>46</sup></a>

The eIDAS Regulation is under consideration for an amendment that will
further evolve the guidance available to include more information on
digital wallets and their use.
<a href="#fn47" id="fnref47" class="footnoteRef"><sup>47</sup></a>

**Blockchain.** The European Strategy for Data includes the evaluation
of blockchain technology.

-   New decentralised digital technologies such as blockchain offer a
    further possibility for both individuals and companies to manage
    data flows and usage, based on individual free choice and
    self-determination. Such technologies will make dynamic data
    portability in real-time possible for individuals and companies,
    along with various compensation models.
    <a href="#fn48" id="fnref48" class="footnoteRef"><sup>48</sup></a>

In addition, the French data protection authority, known as the
[National Commission on Informatics and Liberty
(CNIL)](https://www.cnil.fr/en/home) , has spearheaded work on
"responsible use of the blockchain in the context of personal data" plus
the potential privacy risks inherent in the technology.

The challenges raised by blockchains in terms of compliance with human
rights and fundamental freedoms necessarily call for a response at the
European level. The CNIL is one of the first authorities to officially
address the matter and **will work cooperatively with its European
counterparts to suggest a strong and harmonised approach.**
<a href="#fn49" id="fnref49" class="footnoteRef"><sup>49</sup></a>

Conclusion
==========

Although it may be difficult to define privacy, the fundamental
principles of Privacy by Design, depicted in Figure 5 above, create a
well-defined foundation for understanding and implementing *Privacy and
Compliance for Consumers* . This is why Privacy by Design is included in
the GDPR and CCPA, and has significantly influenced subsequent privacy
regulations and laws. By now, identity professionals have a clear
picture of the interlinked dependencies between identity, privacy, and
security. Security protects the data; how privacy is provided is based
on business and risk policies. The silver lining for the daunting task
of implementing privacy and compliance for consumers is that it may be
viewed as a competitive advantage and well worth the extra effort.

Author Bio
----------

<img src="image8.png" width="81" height="107" alt="Photo of the author" />
Clare Nelson, CISSP, CIPP/E, AWS Certified Cloud Practitioner; is the
CEO of ClearMark Consulting, specializing in business development and
product strategy. Prior to that, she was VP Technology Alliances &
Channel Sales for Identity Governance and Cloud Privileged Access
Management leader Saviynt, responsible for AWS and Google Cloud
partnerships. Clare's passion for cybersecurity includes her
specializations in identity and privacy comprising: MFA, IGA, PAM,
identity proofing, privacy-preserving authentication based on ZKP,
identity theft, AML/KYC, and GDPR. Clare has held leadership positions
at Novell, EMC2, Dell, and AllClear ID. She is a co-founder of
C1ph3r\_Qu33ns, an organization dedicated to cultivating and supporting
the careers of women in cybersecurity. Clare is a second-generation yogi
and technologist and has a degree in mathematics from Tufts University.

Change Log
==========

| Date       | Change                                                                                                                                                                   |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2020-06-17 | V1 published                                                                                                                                                             |
| 2021-09-30 | V2 published: Updated date of NY SHIELD act; added section on CIAM and Social Identity; added section title for CIAM and Workforce IAM; added Heather Flanagan as editor |
| 2022-12-18 | V3 published: Updated abstract; added notes re: threats to privacy in “What is Privacy?”; added information on eIDAS in “Beyond GDPR”                                    |

<div class="footnotes">

------------------------------------------------------------------------

1.  <div id="fn1">

    “IDPro Body of Knowledge,” IDPro,
    <https://www.idpro.org/body-of-knowledge/> . [↩](#fnref1)

    </div>

2.  <div id="fn2">

    Cormack, Andrew, “Introduction to the GDPR (v2),” IDPro Body of
    Knowledge, 30 June 2021, <https://bok.idpro.org/article/id/11/> .
    [↩](#fnref2)

    </div>

3.  <div id="fn3">

    Hindle, Andrew, “Impact of GDPR on Identity and Access Management,”
    IDPro Body of Knowledge, 31 March 2020,
    <https://bok.idpro.org/article/id/24/> . [↩](#fnref3)

    </div>

4.  <div id="fn4">

    “Terminology in the IDPro Body of Knowledge,” IDPro Body of
    Knowledge, 30 September 2021, <https://bok.idpro.org/article/id/41/>
    . [↩](#fnref4)

    </div>

5.  <div id="fn5">

    Solove, D., “The Myth of the Privacy Paradox,” SSRN e-Library, 24
    February 2020,
    <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3536265> .
    [↩](#fnref5)

    </div>

6.  <div id="fn6">

    Narayanan, Arvind, and Vitaly Shmatikov, “Robust De-anonymization of
    Large Sparse Datasets,” The University of Texas at Austin, n.d.,
    <https://www.cs.utexas.edu/~shmat/shmat_oak08netflix.pdf> *.*
    [↩](#fnref6)

    </div>

7.  <div id="fn7">

    Narayanan, Arvind, Joanna Huey, and Edward W. Felton, “A
    Precautionary Approach to Big Data Privacy,” 19 March 2015,
    <https://www.cs.princeton.edu/~arvindn/publications/precautionary.pdf>
    . [↩](#fnref7)

    </div>

8.  <div id="fn8">

    “’Anonymized’ Data Can Never Be Totally Anonymous, says Study,” The
    Guardian, 24 July 2019,
    <https://cacm.acm.org/news/238352-anonymized-data-can-never-be-totally-anonymous-says-study/fulltext>
    . [↩](#fnref8)

    </div>

9.  <div id="fn9">

    Ibid [↩](#fnref9)

    </div>

10. <div id="fn10">

    “Complete guide to GDPR compliance,” Horizon 2020 Framework
    Programme of the European Union, <https://gdpr.eu/> . [↩](#fnref10)

    </div>

11. <div id="fn11">

    “California Consumer Privacy Act (CCPA),” Office of the Attorney
    General, California Department of Justice,
    <https://oag.ca.gov/privacy/ccpa> . [↩](#fnref11)

    </div>

12. <div id="fn12">

    “An act to amend the general business law and the state technology
    law, in relation to notification of a security breach,” Senate Bill
    S5575B, The New York State Senate, 7 May 2019,
    <https://www.nysenate.gov/legislation/bills/2019/s5575> .
    [↩](#fnref12)

    </div>

13. <div id="fn13">

    “The California Consumer Privacy Act of 2018,” Assembly Bill No.
    375, Chapter 55, California State Legislature, 29 June 2018,
    <https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=201720180AB375>
    . [↩](#fnref13)

    </div>

14. <div id="fn14">

    “Data Protection Laws of the World,” map, DLA Piper Intelligence,
    [*https://www.dlapiperdataprotection.com/*](https://www.dlapiperdataprotection.com/)
    [↩](#fnref14)

    </div>

15. <div id="fn15">

    “Charter of Fundamental Rights of the European Union,” Official
    Journal of the European Union, C 392/391, 26 October 2012,
    <http://data.europa.eu/eli/treaty/char_2012/oj> . [↩](#fnref15)

    </div>

16. <div id="fn16">

    “Treaty on the Functioning of the European Union,” Official Journal
    of the European Union, C 326, 26 October 2012,
    [ttp://data.europa.eu/eli/treaty/tfeu\_2012/oj](http://data.europa.eu/eli/treaty/tfeu_2012/oj)
    . [↩](#fnref16)

    </div>

17. <div id="fn17">

    United Nations, “The Universal Declaration of Human Rights,” 1948,
    <https://www.un.org/en/universal-declaration-human-rights/> .
    [↩](#fnref17)

    </div>

18. <div id="fn18">

    “APEC Privacy Framework,” International Association of Privacy
    Professionals (IAPP), n.d.,
    <https://iapp.org/resources/article/apec-privacy-framework/> .
    [↩](#fnref18)

    </div>

19. <div id="fn19">

    “The new EU ePrivacy Regulation: what you need to know,” i-SCOOP,
    n.d., <https://www.i-scoop.eu/gdpr/eu-eprivacy-regulation/> .
    [↩](#fnref19)

    </div>

20. <div id="fn20">

    “Richards, Neil, and Woodrow Hartzog, “The Pathologies of Digital
    Consent,” SSRN e-Library, 11 November 2019,
    <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3370433> .
    [↩](#fnref20)

    </div>

21. <div id="fn21">

    Naughton, John, “’The goal is to automate us’: welcome to the age of
    surveillance capitalism,” The Guardian, 20 January 2020,
    <https://www.theguardian.com/technology/2019/jan/20/shoshana-zuboff-age-of-surveillance-capitalism-google-facebook>
    *.* [↩](#fnref21)

    </div>

22. <div id="fn22">

    Petters, Jeff, “Data Privacy Guide: Definitions, Explanations and
    Legislations,” Varonis, 29 March 2020,
    <https://www.varonis.com/blog/data-privacy/> *.* [↩](#fnref22)

    </div>

23. <div id="fn23">

    Maler, Eve, “Don’t Pave Privacy Cow Paths: Retool Consent for the
    New Mobility” (video), Identiverse 2018, 26 June 2018,
    <https://www.youtube.com/watch?v=eP5U2sA6EFk&t=254s> *.*
    [↩](#fnref23)

    </div>

24. <div id="fn24">

    Hulsen, L. Ten, “Open Sourcing Evidence from the Internet - The
    Protection of Privacy in Cvilian Criminal Investigations using OSINT
    (Open-Source Intelligence)”, Amsterdam Law Forum, vol 12.2, 2020,
    <https://heinonline.org/hol-cgi-bin/get_pdf.cgi?handle=hein.journals/amslawf12&section=9>
    . [↩](#fnref24)

    </div>

25. <div id="fn25">

    See for example Clausen, M.-L., 2021. Challenges of using biometrics
    in Yemen, DIIS: Dansk Institut for Internationale Studier. Retrieved
    from
    *https://policycommons.net/artifacts/1526658/challenges-of-using-biometrics-in-yemen/2214896/
    on 10 Nov 2022. CID: 20.500.12592/n9640f.* [↩](#fnref25)

    </div>

26. <div id="fn26">

    “Data Protection,” European Data Protection Supervisor, n.d.,
    <https://edps.europa.eu/data-protection/data-protection_en>
    [↩](#fnref26)

    </div>

27. <div id="fn27">

    Westin, Alan F. "Privacy and freedom." Washington and Lee Law Review
    25, no. 1 (1968): 166. [↩](#fnref27)

    </div>

28. <div id="fn28">

    Cate, Fred H., Beth E. Cate, “The Supreme Court and information
    privacy,” International Data Privacy Law, Volume 2, Issue 4,
    November 2012, p 255-267, <https://doi.org/10.1093/idpl/ips024> .
    [↩](#fnref28)

    </div>

29. <div id="fn29">

    Pernot-Leplay, Emmanuel, “Data Privacy Law in China: Comparison with
    the EU and U.S. Approaches,” (blog post), 27 March 2020,
    *<https://epernot.com/data-privacy-law-china-comparison-europe-usa/>
    .* [↩](#fnref29)

    </div>

30. <div id="fn30">

    Member Economies map, Asia-Pacific Economic Cooperation,
    <https://www.apec.org/About-Us/About-APEC/Member-Economies> .
    [↩](#fnref30)

    </div>

31. <div id="fn31">

    Sacks, Samm. "China’s Emerging Data Privacy System and GDPR."
    *Washington, DC: Center for Strategic and International Studies*
    (2018). [↩](#fnref31)

    </div>

32. <div id="fn32">

    Solove, Daniel J, “A Taxonomy of Privacy,” University of
    Pennsylvania Law Review, Vol. 154, No. 3, January 2006,
    <https://www.law.upenn.edu/journals/lawreview/articles/volume154/issue3/Solove154U.Pa.L.Rev.477(2006).pdf>
    . [↩](#fnref32)

    </div>

33. <div id="fn33">

    Cavoukian, Ann, “Privacy by Design: The 7 Foundational Principles,”
    [www.privacybydesign.ca](http://www.privacybydesign.ca) , n.d.,
    <https://www.ipc.on.ca/wp-content/uploads/Resources/7foundationalprinciples.pdf>
    . [↩](#fnref33)

    </div>

34. <div id="fn34">

    “Privacy By Design,” graphic, Aristi Ninja, n.d.,
    *<https://aristininja.com/privacy-by-design/> .* [↩](#fnref34)

    </div>

35. <div id="fn35">

    Cavoukian, Ann, “7 Laws of Identity: The Case for Privacy-Embedded
    Laws of Identity in the Digital Age,” Information and Privacy
    Commission of Ontario, n.d.,
    <https://collections.ola.org/mon/15000/267376.pdf> . [↩](#fnref35)

    </div>

36. <div id="fn36">

    Wadhwa, Vivek, “Laws and Ethics Can’t Keep Pace with Technology,”
    MIT Technology Review, 15 April 2014,
    *<https://www.technologyreview.com/s/526401/laws-and-ethics-cant-keep-pace-with-technology/>
    .* [↩](#fnref36)

    </div>

37. <div id="fn37">

    ISACA webinar, Robotic Process Automation (RPA) and Audit, March 19,
    2020,
    [*https://www.isaca.org/education/online-events/lms\_w031920*](https://www.isaca.org/education/online-events/lms_w031920)
    [↩](#fnref37)

    </div>

38. <div id="fn38">

    “The UX Guide for Getting Consent,” IAPP, n.d.,
    <https://iapp.org/store/books/a191a000002FUZKAA4/> . [↩](#fnref38)

    </div>

39. <div id="fn39">

    Schwartz, Karen D., “Data Privacy and Data Security: What’s the
    Difference?” ITPro Today, 2 May 2019,
    <https://www.itprotoday.com/security/data-privacy-and-data-security-what-s-difference>
    . [↩](#fnref39)

    </div>

40. <div id="fn40">

    “NIST Privacy Framework: A Tool for Improving Privacy Through
    Enterprise Risk Management, Version 1.0,” National Institute of
    Standards and Technology, U.S. Department of Commerce, 16 January
    2020,
    <https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.01162020.pdf> .
    [↩](#fnref40)

    </div>

41. <div id="fn41">

    Ibid [↩](#fnref41)

    </div>

42. <div id="fn42">

    “NIST Privacy Framework: A Tool For Improving Privacy Through
    Enterprise Risk Management,” Preliminary Draft, National Institute
    of Standards and Technology, U.S. Department of Commerce, 6
    September 2019,
    <https://www.nist.gov/system/files/documents/2019/09/09/nist_privacy_framework_preliminary_draft.pdf>
    *.* [↩](#fnref42)

    </div>

43. <div id="fn43">

    “The Privacy Advisor,” IAPP, Vol. 10, No. 10, December 2010,
    <https://iapp.org/media/pdf/publications/Advisor_12-10_print.pdf> .
    [↩](#fnref43)

    </div>

44. <div id="fn44">

    “White Paper: GDPR, CCPA, and Beyond: How to Comply with Data
    Privacy Laws and Improve Customer Trust,” Akamai, n.d.,
    <https://www.akamai.com/us/en/campaign/assets/whitepapers/gdpr-ccpa-and-beyond-wp.jsp>
    . [↩](#fnref44)

    </div>

45. <div id="fn45">

    “Communication from the Commission to the European Parliament, the
    Council, the European Economic and Social Committee and the
    Committee of the Regions,” European Commission, COM(2020) 66 final,
    19 February 2020

    <https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52020DC0066&from=EN>
    . [↩](#fnref45)

    </div>

46. <div id="fn46">

    European Commission, “eIDAS Regulation,” website, last updated 7
    June 2022,
    <https://digital-strategy.ec.europa.eu/en/policies/eidas-regulation>
    . [↩](#fnref46)

    </div>

47. <div id="fn47">

    European Commission, “Commission proposes a trusted and secure
    Digital Identity for all Europeans,” press release, 3 June 2021, ​​
    <https://ec.europa.eu/commission/presscorner/detail/en/IP_21_2663> .
    [↩](#fnref47)

    </div>

48. <div id="fn48">

    European Commission, COM(2020) 66 final, 19 February 2020.
    [↩](#fnref48)

    </div>

49. <div id="fn49">

    “Blockchain and the GDPR: Solutions for a responsible use of the
    blockchain in the context of personal data,” CNIL, 6 November 2018,

    <https://www.cnil.fr/en/blockchain-and-gdpr-solutions-responsible-use-blockchain-context-personal-data>
    . [↩](#fnref49)

    </div>

</div>
