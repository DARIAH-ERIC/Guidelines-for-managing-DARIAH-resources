---
layout: default
title: SSH Open Marketplace
nav_enabled: true
parent: Services used for managing DARIAH resources
---

The SSH Open Marketplace is a discovery portal which pools and contextualises resources for Social Sciences and Humanities research communities: **tools, services, training materials, datasets, publications and workflows**.

In the DARIAH context, the SSH Open Marketplace is used to collect the DARIAH Tools & Services featured in the catalogue: [https://www.dariah.eu/tools-services/tools-and-services/](https://www.dariah.eu/tools-services/tools-and-services/) . Registering your resources in the SSH Open Marketplace will help you to describe your resource, thanks to the recommended metadata fields you need to fill in and support your dissemination efforts.

The present section provides recommendations/insights on:

* How to set an automated pipeline between your national catalogue and the SSH Open Marketplace (section 3.1.1)  
* How to manually add/enrich individual records in the SSH Open Marketplace (section 3.1.2)

  1. ### Automated pipeline between the SSH Open Marketplace and national catalogues of software and services

It is possible to set up an automated pipeline to exchange metadata between a national catalogue and the SSH Open Marketplace. Both directions can be considered:

* **Reusing data exposed in the SSH Open Marketplace** to populate your national catalogue, via the API (i.e. the [DARIAH service catalogue](https://www.dariah.eu/tools-services/tools-and-services/) is built following this approach) .   
* **Using your existing national catalogue as a source** for the Marketplace, setting up an aggregation and ingestion pipeline between your catalogue and the SSH Open Marketplace (i.e. option used by the DARIAH-PL node and its DARIAH-LAB catalogue). If you decide to go in this direction,  you should use  the [contact form](https://marketplace.sshopencloud.eu/contact) to get in touch with DARIAH & SSH Open Marketplace staff. The decision to include a new source, such as your national catalogue, has to be made based on the [source inclusion criteria](https://marketplace.sshopencloud.eu/about/data-population#inclusion-criteria-for-adding-resources-4-questions-to-ask) and on a consensual basis within the Editorial team, though of course DARIAH staff will accompany you in this process. Once approved, a mapping between source and marketplace data will be created. Based on this mapping, the source data can be ingested. For more information, see [https://marketplace.sshopencloud.eu/contribute/overview](https://marketplace.sshopencloud.eu/contribute/overview)	

If you would like to implement such a technical solution, please contact the SSH Open Marketplace ingest team (Laure Barbot, [laure.barbot@dariah.eu](mailto:laure.barbot@dariah.eu) and Michael Kurzmeier, [michael.kurzmeier@dariah.eu](mailto:michael.kurzmeier@dariah.eu))

2. ### Manual additions/enrichment (of individual software or service)

How to add resources in the SSH Open Marketplace is explained in the [user documentation](https://marketplace.sshopencloud.eu/contribute/create-an-individual-item)[^6]. 

Specific rules apply for registering a DARIAH resource, and an overview of the metadata recommendations for adding or enriching DARIAH resources to the SSH Open Marketplace is available in the t[able below[^7]. For National DARIAH Resources in the SSH Open Marketplace, refer to these recommendations](https://docs.google.com/presentation/d/1vjG2JDztx4htlkQ4aYqVGYZ1Ge5i6ZfBKJqb8KmohLM/edit?slide=id.g37941ae11d7_0_179#slide=id.g37941ae11d7_0_179).

| Actor/Property Field | How to fill it? | Explanation/commentary |
| :---- | :---- | :---- |
| Label | Name of the resource | Where possible use *DARIAH* in the label (e.g. DARIAH-DE Geo-Browser) |
| Description | Brief description of the resource | English description is mandatory, descriptions in other languages can be added as appropriate |
| Accessible at | Link/URL to the resource  | Landing page of the resource which could be the persistent identifier. Ideally, only one URL should be added as “accessible at”. For other URLs, see “external ID” |
| External IDs | External identifiers, such as Wikidata, Github or DOIs identifiers  | In addition to the link/URL to the resource, external identifiers should be added when possible. They link Marketplace items to other authoritative sources and contribute to increase the (meta)data quality.  |
| Reviewer (Actor) | Name your DARIAH National node (e.g. DARIAH-DE) | Use the name of your national node according to [https://www.dariah.eu/network/members-and-partners/](https://www.dariah.eu/network/members-and-partners/)  |
| Curator (Actor) | DARIAH-EU | Curator of the DARIAH entries in the Marketplace |
| Provider (Actor) | Name the institution responsible for and providing the tool/service.  | Can be more than one provider. For joint resources this field might be confusing for the user \- and you can decide to skip it. In general it makes the resources more trustworthy if provider information is given. |
| Activity  | Choose at least one activity  | Similar to Keyword, this is based on the [TaDIRAH taxonomy](https://vocabs.dariah.eu/tadirah/en/) \- and is thus a controlled vocabulary. To be preferred over Keyword for activity description. |
| Keyword | DARIAH Resource | Similar to Activity, this is a non-controlled vocabulary that allows you to enter a topical keyword related to the entry.  ALSO: You must select the “DARIAH Resource” keyword, in addition to any others. This will allow it to be picked up by our automated checks. You can also add another keyword field to make the resource findable for your national system (e.g. Text+) |
| License | If applicable | Important information for the user\! Based on a closed vocabulary. If the license is unknown, fill in the *Terms of Use* textbox. |
| Authentication  | If applicable | There is only a “yes” or “no” option, further information in Terms of Use or elsewhere is necessary. |
| Terms of Use URL | If applicable | If you are not able to provide a link to a terms of use url you can either use the license (see above) or the Term of Use textbox |
| Language | Name the language(s) of the resource  | Based on a closed vocabulary. Important information if reasonable in context of the service. Language options of the user interface (multiple languages or add another field for each language) |
| Helpdesk URL  | If applicable | If your tool or service is supported by a helpdesk it is always useful information  |
| User Manual URL | If applicable | If you provide a User Manual online it is always useful information  |
| Resource category | Choose at least one category if applicable | Based on the [EOSC vocabulary](https://vocabs.sshopencloud.eu/vocabularies/eosc-resource-category/eoscResourceCategoryScheme) \- to be preferred over Tool Family. These categories allow a quick identification of the type of tools/services. Ex: “repository”, “software”, “training platform”. This is an important field, as it is also used as a filter in the DARIAH catalogue.  |
| Technicality Readiness Level | If applicable  | If you want to align with the EOSC marketplace, consider the Technicality Readiness Level indications [here](https://eosc-portal.eu/providers-documentation/eosc-provider-portal-resource-maturity-classification) \- to be preferred over Life Cycle Status |
| Discipline | If relevant | If your service is for a specific discipline you might want to indicate it / you can alternatively use the Intended Audience field if you want to address a specific group (e.g. researchers, providers, data managers) |
| Thumbnails and other media |  | This can be used for screenshots or videos showing the software or service. |
| Related Items | If relevant | Relevant to link related items here, especially training materials and publications, as these item types are seen as contextualising information in the SSHOMP. Related items must be created in the MP and approved before they can be added. |
| See also  | If relevant | Links to non-MP materials that are relevant |
| Input Format | If relevant | The file format(s) used for input \- this is especially relevant for tools and services. Uses the [sshomp-format vocabulary](https://vocabs.sshopencloud.eu/browse/sshomp-format/en/).  |
| Output Format | If relevant | The file format(s) used for output \- this is especially relevant for tools and services. Uses the [sshomp-format vocabulary](https://vocabs.sshopencloud.eu/browse/sshomp-format/en/).  |
