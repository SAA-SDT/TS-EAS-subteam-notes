##Subject: Update of Encoded Archival Context – Corporate Bodies, Persons, Families – Call for Comments

[Apologies for cross-posting.]

In 2017 the Technical Subcommittee on Encoded Archival Description (TS-EAS) of the Society of American Archivists agreed to undertake a revision of the standard EAC-CPF.

The revision follows a two-tier strategy, starting with a technical update that includes minor enhancements and a general clean-up. This will be followed by a major overhaul of the standard and a reconciliation with EAD3. The updated schema will be backwards compatible as long as the attribute @accuracy isn’t used and values of @xml:id attributes are unique.

The TS-EAS is calling for comments on the first set of changes, which are reflected in the [updated schema files](https://github.com/SAA-SDT/eac-cpf-schema/releases/tag/v2010_revision-beta), cpf.xsd & cpf.rng, available at GitHub. Please send feedback and comments by e-mail to Silke Jagodzinski (s.jagodzinski@bundesarchiv.de). Particularly, feedback on the usage of the attribute @accuracy and the usage of the provided RNG schema file is very welcome. To ensure that the revision process is as open as possible, all comments must be attributable to named individuals and affiliated organisations where appropriate. Anonymous responses will not be considered. All change proposals will be made publicly available, with attribution, through the GitHub Portal as established during the EAD revision process. E-mail addresses are requested so that we may contact respondents for clarification, but will not be shared.

This update solves 16 issues, which can be viewed in full in [GitHub](https://github.com/SAA-SDT/eac-cpf-schema/labels/implement). The changes include:
- relaxed data types for the elements `<preferredForm>` and `<otherAgencyCode>`
- made the elements `<languageDeclaration>`, `<agencyName>`, `<eventDescription>`, `<sourceEntry>`, `<placeEntry>` within `<relations>`-Elements repeatable
- added the value ‘unknown’ to the attributes @eventType and @agentType
- added restricted content to the elements `<publicationStatus>` and `<maintenanceStatus>`
- added the new optional element `<rightsdeclaration>` with child elements to `<control>`, as in EAD 3
- added the optional attribute @localType to the elements `<fromDate>` and `<toDate>`
- removed maximum year 2999 from the attributes @standardDate and @standardDateTime
- corrected the typo in the attribute @accuracy
- corrected data type for xml:id in eac.rng schema file

This call for comments is open for 2 month, and ends on 31 October 2018.

Silke Jagodzinski (Bundesarchiv), EAC-CPF Team Lead 
Kathy Wisser (Simmons College), TS-EAS Co-chair
