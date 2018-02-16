# A Schema-Maintenance Proposal from the Schema Subteam
## Proposal
We propose that future versions of EAD, EAC-CPF, and any other XML-based schemas provided by the Technical Subcommittee on Encoded Archival Standards (TS-EAS), be provided in two formats only: RELAX NG (RNG) and W3C XML Schema (XSD).

We also propose that any future releases of EAD3 exclude the undeprecated schemas that were provided with release 1.0 and 1.1.

Therefore, the Schema Subteam proposes that TS-EAS provide future updates to EAD3 in the following formats only:
* DTD (Document Type Definition)
* RNG
* XSD

And future updates and revisions to EAC-CPF will be provided as:
* RNG
* XSD

## Background:
EAD3 1.0 was released in a total of six schemata, or schemas, that are expressed in three different schema types:
* RNG: https://github.com/SAA-SDT/EAD3/blob/master/ead3.rng 
* XSD: https://github.com/SAA-SDT/EAD3/blob/master/ead3.xsd 
* DTD: https://github.com/SAA-SDT/EAD3/blob/master/ead3.dtd 
* RNG undeprecated: https://github.com/SAA-SDT/EAD3/blob/master/undeprecated/ead3_undeprecated.rng 
* XSD undeprecated: https://github.com/SAA-SDT/EAD3/blob/master/undeprecated/ead3_undeprecated.xsd 
* DTD undeprecated: https://github.com/SAA-SDT/EAD3/blob/master/undeprecated/ead3_undeprecated.dtd 

With EAD3 1.1, the Schema Subteam will once again provide six versions, despite the extra effort and costs that are involved with maintaining and testing six schemas in total. Further, it is not clear if any users are using the undeprecated EAD3 schemas, though it is clear that many archival management tools will not support more than one variety of EAD3 or EAC-CPF.

EAC-CPF 2010 was released in three different schema languages:
* RNG: http://eac.staatsbibliothek-berlin.de/schema/cpf.rng 
* RNG compact: http://eac.staatsbibliothek-berlin.de/schema/cpf.rnc 
* XSD: http://eac.staatsbibliothek-berlin.de/schema/cpf.xsd 

## Rationale:
The Schemas Subteam has developed EAD3 and EAC-CPF 2010 with the Relax NG (RNG) language. RNG has been selected as the source schema since it has proved to be easy to write, easy to maintain, and a good starting point for deriving other schemas. However, even when there are options to create another schema variant from RNG with freely-available tools, such as the Trang Schema Converter, there are costs involved with enacting those transformations, as well as additional costs with testing out and validating the results.

The XSD versions of both standards are provided to the community in addition to the RNG primarily because XSD schemas can be integrated easily with other standards, such as METS, the Metadata Encoding and Transmission Standard, which is maintained by the the Library of Congress.  For example, EAD was added as a as potential metadata schema to the METS’ MDTYPE enumeration list in version 1.1 of METS, and EAC-CPF was added as an option in version 1.9.1. Because of these integration points, the XSD versions of the schema must be provided in addition to the RNG.

For harmonization between EAC3 and EAC-CPF, it also makes sense to continue to provide both standards in RNG and XSD schemas. Since EAD3 was never provided in the RNG compact format, however, it would be less costly (and confusing for the community) to stop producing an RNG compact version with the next update to EAC-CPF, than it would be to start providing four different schema with EAD3. Further, there has been no plan or request to add RNG compact to the EAD3 1.1 release.

Last, the Schemas Subteam discussed whether or not EAD3 should continue to be provided as a DTD. If DTD support could be dropped, then we could use the exact same process for updating EAD and EAC-CPF.  However, we have agreed that it is best to continue to take on the maintenance costs with providing a DTD since:
* DTDs are still frequently used in the publishing industry, which aligns with the fact that EAD was created originally as standard way to encode printed documents;
* There is a large base of users who rely on the DTD schema;
* There are still a lot of tools that are only compatible with DTD schemas;
* The DTD schemas are the only option of the three that can be embedded as part of the EAD file itself, resulting in a single document.
