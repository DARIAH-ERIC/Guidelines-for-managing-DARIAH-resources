---
layout: default
title: SSH Open Marketplace
nav_enabled: true
parent: Services used for managing DARIAH resources
nav_order: 1
---

The SSH Open Marketplace is a discovery portal which pools and contextualises resources for Social Sciences and Humanities research communities: **tools, services, training materials, datasets, publications and workflows**.

In the DARIAH context, the SSH Open Marketplace is used to collect the DARIAH Tools & Services featured in the catalogue: [https://www.dariah.eu/tools-services/tools-and-services/](https://www.dariah.eu/tools-services/tools-and-services/). Registering your resources in the SSH Open Marketplace will help you to describe your resource, thanks to the recommended metadata fields you need to fill in and support your dissemination efforts.

Training materials should be published to DARIAH-Campus in the first instance, and from there they will be ingested as part of an automated process into the SSH Open Marketplace. Some exceptions may apply, see details in section 3.3.

The present section provides recommendations/insights on:

* How to set an automated pipeline between your national catalogue and the SSH Open Marketplace (section 3.1.1)
* How to manually add/enrich individual records in the SSH Open Marketplace (section 3.1.2)

  1. ### Automated pipeline between the SSH Open Marketplace and national catalogues of software and services

It is possible to set up an automated pipeline to exchange metadata between a national catalogue and the SSH Open Marketplace. Both directions can be considered:

* **Reusing data exposed in the SSH Open Marketplace** to populate your national catalogue, via the API (i.e. the [DARIAH service catalogue](https://www.dariah.eu/tools-services/tools-and-services/) is built following this approach).
* **Using your existing national catalogue as a source** for the Marketplace, setting up an aggregation and ingestion pipeline between your catalogue and the SSH Open Marketplace (i.e. option used by the DARIAH-PL node and its DARIAH-LAB catalogue). If you decide to go in this direction, you should use the [contact form](https://marketplace.sshopencloud.eu/contact) to get in touch with DARIAH & SSH Open Marketplace staff. The decision to include a new source, such as your national catalogue, has to be made based on the [source inclusion criteria](https://marketplace.sshopencloud.eu/about/data-population#inclusion-criteria-for-adding-resources-4-questions-to-ask) and on a consensual basis within the Editorial team, though of course DARIAH staff will accompany you in this process. Once approved, a mapping between source and marketplace data will be created. Based on this mapping, the source data can be ingested. For more information, see [https://marketplace.sshopencloud.eu/contribute/overview](https://marketplace.sshopencloud.eu/contribute/overview)

If you would like to implement such a technical solution, please contact the SSH Open Marketplace ingest team (Laure Barbot, [laure.barbot@dariah.eu](mailto:laure.barbot@dariah.eu) and Michael Kurzmeier, [michael.kurzmeier@dariah.eu](mailto:michael.kurzmeier@dariah.eu))

2. ### Manual additions/enrichment (of individual software or service)

How to add resources in the SSH Open Marketplace is explained in the [user documentation](https://marketplace.sshopencloud.eu/contribute/create-an-individual-item)[^7].

Specific rules apply for registering a DARIAH resource. An overview of the metadata recommendations for adding or enriching DARIAH resources to the SSH Open Marketplace is available in the *Guidelines for adding DARIAH Resources to the SSH Open Marketplace v 1.0* [https://doi.org/10.5281/zenodo.15720022](https://doi.org/10.5281/zenodo.15720022).

The most important points to highlight are:

* Adding a "DARIAH Resource" keyword to your resource
* Add (at least) 2 actors following the convention:
  * An actor with a **Reviewer** role for your DARIAH national node (e.g. DARIAH-DE), Working Group, or Cooperating Partner
  * An actor with a **Curator** role for DARIAH-EU
* Specify the resource type using the resource category vocabulary

[^7]:  [https://marketplace.sshopencloud.eu/contribute/create-an-individual-item](https://marketplace.sshopencloud.eu/contribute/create-an-individual-item)
