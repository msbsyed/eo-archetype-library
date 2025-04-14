# eo-archetype-library
A reference model for sensor-based environmental observation data, built on OGC’s SWE O&M standards. Supports archetype-based two-level modelling, LinkEHR workflows, and semantic enrichment for improved data quality, interoperability, and reuse in Earth Informatics.

🌍 EO Archetype Library — Reference Model for Sensor-Based Environmental Observations
Welcome to the EO Archetype Library, an open reference model designed to support the two-level information modelling of sensor-based environmental observation data, focusing on air quality monitoring within the Earth Observation (EO) domain.

📘 About This Reference Model
This reference model provides a stable, semantic-friendly foundation for representing environmental monitoring data — particularly from sensor-based observations — in a reusable, interoperable, and extensible way. It follows the principles of two-level modelling, where a consistent reference model defines core structures, and domain-specific archetypes represent detailed, context-rich semantics tailored for reuse.

🔹 Foundation and Alignment
This model builds upon the base reference model proposed by Dr. Paul Stacey (Towards People Oriented Technology (tPOT) Research Centre, TU Dublin), originally designed to support the translation of two-level models from e-Health into Earth Informatics. The original model is available at:
🔗 github.com/pstacey/geo-archetype-library

Expanding on that, this version adapts and extends the core reference model using standards from the Open Geospatial Consortium (OGC) — especially the Observations & Measurements (O&M) model and the Sensor Web Enablement Common Data Model (SWE-CDM). It introduces flattened and harmonised data types suitable for:

1) Sensor-based air quality monitoring
2) Environmental and geospatial observation data
3) Archetype-driven two-level information modelling

The schema is designed to be standalone and LinkEHR-compatible, enabling archetyping and knowledge formalisation without relying on external schema imports. This makes it highly suitable for modelling observational Earth Science data while supporting semantic interoperability, data quality assurance, and reuse across distributed environmental data systems.

🧩 Use Case [Not comprehensive, can be extended to multiple subdomains]
This reference model underpins the development of domain-specific archetypes, for instance:

1) Air quality parameters (e.g., PM2.5, NO₂, O₃, SO₂, CO)
2) O&M elements like observed properties, Features of interest, etc.

🔧 Modular Archetype Support
This reference model is designed to support modular archetype development — enabling the separation of key metadata components such as:

1) Sensor calibration information
2) Sensor specifications
3) Deployment context
4) Sensor operational characteristics
5) Aggregated observational values (e.g., hourly means, Air Quality Index calculations)

These modular archetypes can be independently defined and linked together within higher-level archetypes (e.g., an air quality observation) to create a cohesive, semantically rich metadata model. This allows for the creation of high-quality, standards-aligned information structures that accompany observation data, improving:

1) Documentation quality
2) Semantic clarity
3) Reusability across systems and domains
4) Support for automated reasoning and validation

This compositional structure encourages reuse, refinement, and community participation, aligning with two-level modelling best practices for Earth Informatics.

🔧 Technical Highlights

Modular and Maintainable Structure:
Built using a set of well-structured, modular XSD schema files, with consistent and carefully managed namespace definitions. This facilitates clean reuse and extensibility across projects and modelling layers.

LinkEHR-Compatible Design:
Structured to fully support archetype-slot references in LinkEHR workflows, allowing for flexible, compositional archetype development using familiar tooling. This is essential for enabling collaborative and distributed model refinement.

Semantic Integration Ready:
Designed with semantic interoperability in mind, the reference model facilitates the integration of controlled vocabularies, code lists, and external ontologies. This makes it suitable for high-quality metadata modelling and semantic enrichment of observation data.

👤 Author
This reference model is developed by M.S.B. Syed, PhD candidate at Technological University Dublin and Taighde Éireann – Research Ireland Centre for Research Training in Advanced Networks for Sustainable Societies, with the financial support from Taighde Éireann – Research Ireland under Grant No. 18/CRT/6222. The work is part of an ongoing research project titled: "Using Archetype-Based Two-Level Information Modelling to Enhance Data Quality in SDG 11 Sustainable Cities and Communities Implementation Monitoring".
