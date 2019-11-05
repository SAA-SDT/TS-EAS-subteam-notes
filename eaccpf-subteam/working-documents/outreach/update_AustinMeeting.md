(document is currently in draft status)

# EAC-CPF revision half-way into stage 2 
After a successful release of the technical update of the Encoded Archival Context - Corporate Bodies, Persons, and Families (EAC-CPF) in December 2018, the EAC-CPF team of the Technical Subcommittee on Encoded Archival Standards (TS-EAS) is now half-way into the second stage of the standard's major revision. While all current issues are discussed on GitHub  [https://github.com/SAA-SDT/eac-cpf-schema/issues] and during the monthly team meetings, a few general topics emerged from these conversations that seemed to qualify for more in-depth analysis. 
## One day dedicated to EAC-CPF
Hence TS-EAS decided to have a one-day meeting only on selected topics from the EAC-CPF revision, when meeting in the context of the Annual Meeting of the Society of American Archivists (SAA) in Austin in August 2019. The topics on the table were  "Dates", "Names", "Identifiers" and the new addition of "Assertion Description". It should be noted that some of the updates, which are detailed below, are still in flux and will require further conversations during the next few months. The final result of the team's considerations will then be presented as part of the first draft publication for community feedback during the second half of 2020.
### Dates
EAC-CPF uses a variety of elements to encode date information, but only to some extent is it possible to express uncertainty about dates or even to classify part(s) of a given date range as unknown. EAC-CPF team has been looking at implementation of such uncertainty in other standards, including the Encoded Archival Description (EAD 2002 and EAD3), the Extended Date/Time Format (EDTF) Specification, the Text Encoding Initiative (TEI) and the Metadata Object Description Schema (MODS). Based on this comparison, the suggested changes include:
- Adding the attribute @certainty (from EAD3) to the elements &lt;date>, &lt;fromDate> and &lt;toDate>;
- Recommending the use of values inspired by EDTF such as "uncertain", "approximate" and "uncertain and approximate" with the newly added attribute @certainty;
- Introducing a new attribute @status for the elements &lt;date>, &lt;fromDate> and &lt;toDate> to indicate their status as being "unknown" or "open" (e.g. for persons who are still alive).
### Names
...
### Identifiers
...
### Assertion Description
...
## Next steps
The EAC-CPF team will tackle pending questions with regard to these topics as well as others, which still require further consideration, in the context of its monthly meetings between December 2019 and March 2020, culminating in a three-day meeting from 9 to 12 March 2020 in Berlin, Germany. During this time, you are welcome to follow our conversations on GitHub [https://github.com/SAA-SDT/eac-cpf-schema/issues] to stay up-to-date with the EAC-CPF revision.
