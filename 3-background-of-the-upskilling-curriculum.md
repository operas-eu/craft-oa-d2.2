# 3 Background of the Upskilling Curriculum

The diversity of actors in the Open Access Diamond Journal (OADJ) landscape served both as a cause and a motivation for the creation of the Reusable Upskilling Curriculum, which presents a starting point for those involved in institutional Open Access (OA) publishing and wishing to expand their technical expertise. The curriculum was designed taking into account the current difficulties of the OADJ community in embracing the established technical standards. It provides a list of existing training material and offers general guidelines which may act as a first step for upskilling as well as inspiration for creating or delivering training.

The CRAFT-OA deliverable D3.1 “[Report on Standards for Best Publishing Practices and Basic Technical Requirements in the Light of FAIR Principles](https://zenodo.org/doi/10.5281/zenodo.8112661)” (Armengou et al. 2023a) conducted an extensive review of the variety of technical standards. In their analysis the authors systematically examined the following documents[^1]:

* the Directory of Open Access Journals (DOAJ) inclusion criteria[^2],
* the Plan S requirements for publication venues[^3],
* the OpenAIRE Guidelines for Literature Repository Managers v4[^4],
* the Extensible Quality Standard for Institutional Publishing (EQSIP) V1.0[^5]
* the EOSC Interoperability Framework Guidelines[^6].

Based on the standards outlined in the D3.1 report, the same working group published “[D3.2 Report on challenges and help measures faced by OA journals and platforms](https://zenodo.org/doi/10.5281/zenodo.10496593)” (Laakso et al. 2024). This document summarised the standards and requirements that the OADJ community has difficulties implementing in their publishing practices. The core components of the Reusable Upskilling Curriculum presented here are therefore based on the D3.2 study.

An additional resource that informed D3.2 were preliminary results of the 2023 DIAMAS survey (Armengou et al. 2023b) which was conducted between March and May 2023 and contains responses by 685 institutions involved in publishing within the European Research Area (ERA). In their synopsis of the report Arasteh and Blake (2024, p.5) fittingly dub the OADJ community “a largely fragmented archipelago”. Nevertheless, the authors provide a number of features that the community has in common: institutional publishers maintain high editorial standards and adhere to open science values; many are operating within a small budget and print a limited number of journals and publications; they dispose of restricted professionals hours and often rely on the work of volunteers (Arasteh & Blake, 2024, p. 7). This supports the findings of the Open Access Diamond Journal Study (OADJS) that showed a budget of below 10,000€ as the financial base for over 60% of the journals that were surveyed (Bosman et al., 2021, p. 110).

With the limited resources of OADJs in mind, the Reusable Upskilling Curriculum is conceptualised to group the variety of challenges faced by OADJs into manageable modules. In this way, the users - both trainers and trainees - can select a topic and the level of complexity in accordance with their needs and resources. The curriculum offers trainers a comprehensive framework to organise training; it also allows the trainees to identify their upskilling needs more precisely. Recommendations on how to use the Reusable Upskilling Curriculum are provided in chapter 4.

One overarching issue that influences the way in which OADJs work is the publishing software. Although no technical quality standard such as EQSIP or Plan S recommends a certain system, the use of a specifically designed software for journal publishing often enables OADJs to adhere to the standards in a fundamentally easier way. The DIAMAS survey responses to the question what software the institutional publishers utilise, show a gap in the implementation of specialised publishing systems, with 9.7% running on Wordpress and 7.5% unaware of the solution they use. (Laakso et al., 2024, p. 24). The compilation of standards supported by OJS, Janeway and Lodel carried out in D3.2 (Laakso et al. 2024) highlighted that many of the standards are covered by the respective publishing solutions. Hence, the upskilling curriculum is heralded by a section that specifically addresses publishing software solutions. It provides an introduction to the publishing systems and includes some of the topics for advanced use, such as the update and security features. The survey recently carried out in Task 4.4 of CRAFT-OA (“Simplification of installation and update procedures”) found out that two of the most frequently reported issues with OJS are updating (60%) and security concerns (46%). Further advanced topics offered within this block are XML publishing workflows, which can be useful for those IPs who provide not only submission workflow but also layout, typesetting and annotation services.

Both Laakso et al. (2024) and Armengou et al. (2023b) found additional challenges in the field of metadata. High quality metadata and its provisioning in established formats significantly influence a journal’s findability and accessibility. The DIAMAS survey (Armengou et al. 2023b, p. 139) made clear that next to a lack of human resources, missing expertise is seen as a major obstacle by IPSPs in delivering quality metadata. In the Reusable Upskilling Curriculum this aspect is approached from three perspectives:

* Metadata quality through standards
* Identifiers
* Licensing, OA and self-archiving policy

Within the block “Metadata I: quality through standards”, common metadata schemes are introduced along with methods and infrastructures for metadata harvesting, depositing and export. This mirrors the observation of the DIAMAS survey that „metadata export and sharing is not a standard practice among IPSPs” (Armengou et al., 2023b, p. 134), even though it is required under several quality standards (cf. e.g. Armengou et al. 2023a, p.30-31). This block also embraces the topic of the controlled vocabularies, which allow the systematic and homogeneous description of the resources.

Identifiers are regarded as crucial for successful indexation and attribution of authors, funders as well as journals. While some identifiers like DOIs already show a relatively high uptake, the Research Organization Registry (ROR) identifier needs more awareness even if it was recently adopted by Crossref (Laakso et al., 2024, p. 32). To allow for low-threshold first steps into the topic, the block “Metadata II: identifiers” suggests a general introduction to IDs and their digital pendants PIDs as well as their rendering in different metadata standards (DC, MARC, etc.). In the next step a more detailed explanation of each identifier system can be given (ISSN, DOI, ROR, etc).

At first glance, guidelines concerning copyright and licensing may appear as policy related topics rather than a technical challenge. However, the technical provisioning of metadata under CC0 licence or the registering of self-archiving policies, e.g. on the website, still pose challenges (Laakso et al., 2024, p. 55). The third thematic area “Metadata III: licensing, OA and self-archiving policy” therefore provides an introduction to licence types and open access models, used for publications but also for the accompanying datasets and software. Two further topics touch upon licences and open access status declared in metadata and in different output formats, such as XML, HTML and PDF. Finally, a further gap identified in D3.2 (§3.2.6) is outlined - the journal’s self-archiving policy.

The vast and intertwined field of content accessibility shapes the fifth block of the Reusable Upskilling Curriculum. It is devoted to the content provisioning, harvesting, indexing, depositing and archiving. The topic of content provisioning in different formats, especially the machine-readable ones, was added to the curriculum in response to several previous findings: OADJS reported that smaller journals in SSH cluster were experiencing difficulties with offering articles in XML or HTML format (Bosman et al., 2021, p. 63). Similarly, Laakso et al. (2024, p.67) conclude that in the DIAMAS survey only 19% of respondents indicated dissemination in an XML format, although all publishing software types that were examined supported the use of XML. Whether this software support refers to the production of XML files, e.g. through conversion from other formats, or solely to the ability to handle (i.e. to unload and publish) XML is not entirely clear. However, the apparent gap between OADJs practices and technical possibilities strongly indicates a need for upskilling training. Content provisioning also embraces the website's HTML features, introduced by the hands-on recommendations for the website’s search engine optimization for the aggregators (e.g. Google Scholar). Citations constitute an integral part of the open linked data and their proper delivery helps to raise the overall quality of the publication. The curriculum thus covers the Open Citations Standard, formalising the citations accessibility in metadata (e.g. by its publishing on Crossref) as well as proper referencing in other output formats such as PDF and HTML.

The OADJS underlines that “the biggest problem of small editors in OA is the lack of lobbying for the inclusion in important databases which could contribute to readings and impact increase of the journal.“ (Bosman et al., p. 84). From a technical point of view Bosman et al. (2021, p. 101) conclude that indexation is the main technical challenge for diamond journals. For the European Research Area (ERA) this finding is supported by the DIAMAS survey which asked about the satisfaction of participants with their indexing: 54% indicated that they would like it to be better (Armengou et al., 2023b, p. 144-143). In light of these challenges the section “Content harvesting and indexing” gives the overview of the existing indexing/aggregator services and their requirements, supplemented by the advice for indexing optimization. The technical set-up of the OAI-PMH infrastructure and protocol constitute the core of the training topic on content harvesting. Content depositing to the repositories via SWORD protocol and export in different formats suitable for data mining establish further training areas. Laakso et al. (2024, p.73) present challenges in the area of long-term preservation of content, with only half of the OADJs enrolled in a digital preservation service. Acknowledging the danger of potentially losing a large number of OADJs for the scholarly record, the Upskilling Curriculum contains a training topic on long-term archiving services.

In addition to the resources cited above, the following documents contributed to the creation of the Reusable Upskilling Curriculum:

* GoTriple Handbook[^7]
* TRIPLE Deliverable: D2.5 - Report on Data Enrichment[^8]
* Mapping the Landscape - Identifying categories of projects, axes on the map, and approaches and trends in OSS[^9]
* Overview of the technical standards (a working document for D3.1[^10] (Argmengou et al 2023a))
* Diamas D3.2 “Extensible Quality Standard in Institutional Publishing (EQSIP) V2.0 for Diamond Open Access[^11]”

[^1]: \[3] The synopsis of the report is available in the CRAFT-OA Blog: https://www.craft-oa.eu/2024/02/expanding-the-potential-of-doajs/

[^2]: \[4] https://doaj.org/apply/guide/

[^3]: \[5] https://www.coalition-s.org/addendum-to-the-coalition-s-guidance-on-the-implementation-of-plan-s/principles-and-implementation/

[^4]: \[6] https://openaire-guidelines-for-literature-repository-managers.readthedocs.io/en/v4.0.0/

[^5]: \[7] https://zenodo.org/records/7923916#.ZFy866DP02x; Note that V2.0 was published in February 2024 (Rico-Castro 2024): https://zenodo.org/doi/10.5281/zenodo.10726731.

[^6]: \[8] https://wiki.eoscfuture.eu/display/PUBLIC/EOSC+IF+Guidelines+overview

[^7]: \[12] https://gotriple.eu/docs/gotriple-handbook-v1\_0.pdf

[^8]: \[13] https://zenodo.org/records/7359654

[^9]: \[14] https://mindthegap.pubpub.org/pub/47c55bz4/release/2

[^10]: \[15] https://docs.google.com/spreadsheets/d/1uTm84TeW-rZ3ouKpZPjQOPQCQ9XwSGan9Q0SV86VJr8/edit#gid=258275937

[^11]: \[16] https://zenodo.org/records/10726732
