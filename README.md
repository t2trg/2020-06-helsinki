# 2020-06-helsinki

IRTF T2TRG/W3C WoT work meeting, 2020-06-08
(originally to take place in Helsinki)

In the Internet of Things (IoT), billions of new devices are being connected to the Internet.  At this scale, manual configuration is no longer affordable.  Devices need to make available self-descriptive information, and the systems using them need to discover and make use of this information, without the need for extensive human intervention.

A first set of standards for self-description and discovery has been completed by IETF and W3C.  How can these specifications best be used?  What are the gaps that still need to be addressed?  How can discovery be made secure and private, so that it doesn't disclose too much information and isn't susceptible to attacks?  How can the semantic information that guides discovery be structured in a way that maximizes interoperability, in particular where usage needs to cross different IoT ecosystems?  How can self-description and discovery be used to actually enhance security?

The Internet Research Task Force (IRTF) Thing to Thing Research group (T2TRG), and the Worldwide Web Consortium (W3C) Interest Group (IG) on the Web of Things (WoT) are meeting online for a workshop on self-description and discovery on Monday, June 08, 2020.  The meeting was originally scheduled to take place physically in Helsinki, with the date chosen to coordinate with a number of other events, in particular the 20th International Conference on Web Engineering (ICWE 2020), which also was to take place in Helsinki, on Tuesday, June 09, to Friday, June 12.  It is now taking place online, on the originally planned day, from 1200Z (12:00 UTC) to 1500Z.

Participation in the workshop is open to IoT developers and
researchers free of charge, but we ask you to register by Monday June 1st, to help
planning with the logistics: <https://forms.gle/R33E7J3qM6nYLfQD8>

# Approximate Agenda

Webex: https://ietf.webex.com/ietf/j.php?MTID=m16cc27a1b70c01d7d0bad4ed65b637db

| Time (UTC) | Subject                           | Who                                 |
|------------|-----------------------------------|-------------------------------------|
| 1200Z      | Welcome, Logistics                | Chairs                              |
| 1210Z      | WoT Update                        |                                     |
|            | Use Case Process and Overview     | Michael Lagally                     |
|            | New Work Items                    | Michael McCool/Sebastian Kaebisch   |
| 1220Z      | Lifecycle                         | Michael Lagally                     |
|            | Discussion                        |                                     |
| 1250Z      | WoT Discovery                     | Michael McCool                      |
|            | Discussion                        |                                     |
| 1320Z      | --- Break ---                     |                                     |
| 1340Z      | WoT PoC Progress                  |                                     |
|            | Retail                            | Michael McCool/David Ezell          |
|            | Smart City                        | Michael McCool/Jennifer Lin         |
| 1400Z      | OneDM/TD Integration              | Michael Koster/Sebastian Kaebisch   |
|            | TD Templates; Modularity          |                                     |
|            | Discussion                        |                                     |
| 1430Z      | Hypermedia Controls in TDs and beyond; RESTful design | Victor Charpenay/Ege Korkan |
|            | Actions and Events, Handling URLs |                                     |
|            | Discussion                        |                                     |
| 1500Z      | Wrapup, end of meeting            | Chairs                              |

[View workshop time in various timezones](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20200608T12&msg=Helsinki%20workshop&ah=3&am=00&sort=2)

[Obtain calendar invitation file (.ics)](https://rawcdn.githack.com/t2trg/2020-06-helsinki/414a8b584eeca3212c012b68092594e3ef89c5e7/t2trg-wot-20200608.ics)

# Freezer

Some topics will not fit into the 3-hour format necessitated by the
online nature (which is already bursting at the seams).
So we are likely to set up another joint meeting in the future.

Specifically, we would like to discuss formats and languages for data
definition ("schema languages"), as they are used in various emerging
IoT specifications where JSON-like generic data models are employed.
We plan to invite authors of the relevant proposals and standards.

# Collecting current and future T2TRG/WoT Workshop Topics

* Discovery
    *  State, information, and metadata being discovered
    *  Preserving privacy
        *  Issues, i.e. Avoidance of fingerprinting in web browser
        *  Two-phase protocol WoT proposal
        *  Multiple actors, secret-handshake problem, authentication, authorization
    *  Use of existing directory services, i.e.
        *  CoRE RD/CoRAL
        *  WoT Thing Directory/SPARQL/Keyword/Templates
    *  Use of existing introduction mechanisms, i.e.
        *  Eddystone beacons
        *  mDNS/DNS-SD/Zeroconf
        *  DHCP
        *  QR/Barcodes/NFC (GS1)
    *  New standards needed
        *  Location-based DNS
    *  Semantic discovery
        *  ODM and other semantic schematics
        *  Query languages (SPARQL, GRAPHQL, JSONPath (LinkSmart), XPath 3.1)
        *  Data Modeling
            *  Whither JSON Schema?
            *  ODM
* Lifecycle
    *  Onboarding
        *  State and information being managed
        *  Access control and authentication management
        *  Interaction with existing ecosystems
        *  Registration with directories for discovery
        *  Relationship to discovery, mutual authorization problem
    *  Information and Device states
        *  RFC8576
        *  WoT Architecture
    *  Offboarding/decomissioning
        *  How to deal with non-responsive devices?
        *  Non-retrievable decommissioning vs. factory reset vs. maintenance updates
