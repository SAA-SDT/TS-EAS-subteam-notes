# TS EAS all-member meeting, 2022-10-27

Notetaker: Sarah C.

Slide deck: TS EAS slide deck 2022-10-27.pdf


## Participants


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Present (Y/N)</strong>
   </td>
  </tr>
  <tr>
   <td>Mark Custer (Co-chair)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Karin Bredenberg (Co-chair)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Silke Jagodzinski (EAC-CPF team lead)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Cory Nimer (Outreach team lead)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Alexander Duryee
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Kerstin Arnold (EAD team lead)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Ailie Smith
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Glen Gardner (EAD Web liaison)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Anna-Maria Underhill (EAC Web liaison)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Lara Michels (Standards liaison)
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Iris Lee
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Anna McCormick
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Ricardo Eito Brun
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Andrew Janes
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Ypapanti Kytta
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Mpho Ngoepe
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Venkat Srinivasan
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Elizabeth Russey-Roke
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Mary Samouelian
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Lori Lindberg
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Marie Elia
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Sarah Cruz (Early-Career member)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Martin Critelli
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>李彦霖 Yanlin Li (Ellen)
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Irene Gates (EAS Section liaison 22-23)
   </td>
   <td>Y
   </td>
  </tr>
  <tr>
   <td>Lydia Tang (Council liaison)
   </td>
   <td>N
   </td>
  </tr>
  <tr>
   <td>Florence Clavaud (EGAD liaison, EAD team)
   </td>
   <td>Y
   </td>
  </tr>
</table>



# Agenda with Notes 27th of October 2022



* Welcome! (Karin and Mark)
    * Start recording 
        * Thursday 27th: 6.00 am PDT / 7.00 am MDT / 8.00 am CDT / 9.00 am EDT / 1.00 pm GMT / 2.00pm BST / 3.00 pm CEST / 4.00 pm EEST / 6.30 pm IST / 9.00 pm CST / 11.00 pm AEST
    * Appointment letter for 2023-24 released. Mark and Karin are contacting members whose term ends in 2023. Call open until 12/15
* From Standards (Karin on behalf of Lara)
    * EAC-CPF approved
    * Process of updating or suggesting a standard to be made
    * Proposal for TS EAS and DACs Chairs schedule annual or bi-annual meetings
* EAS Section updates (Irene)
    * Bo stepped down as Sr. Co-chair and Irene stepped in as Sr. Co-chair; two new members, Kelly as Jr. Co-Chair and James
    * Met in September - intro for new members & reviewing previous year’s activities
    * Next meeting in November
    * Kelly and James will write post for Description Section’s blog on EAC-CPF webinar
    * Reviewing on-going work with developing webinar tutorials (i.e. EAD on a shoestring; Intro to XML editing)
    * 2019-20 survey results that informed direction of webinar tutorials added to SAA Dataverse in early September
* EAC-CPF (Marie)
    * EAC-CPF webinar on November 14th & 15th
    * Request to add additional time zone for Brazil 
    * EAC-CPF 2.0 released August 3rd 2022!
* EAD (Kerstin)
    * Welcome back to returning members w/ two new members, Martin and Yanlin (Ellen)
    * Meets every 3rd Friday each month
    * Multi-day hybrid meetings in August and September
    * Boston meeting update
        * &lt;control>
            * Will be aligned with &lt;control> in EAC-CPF 2.0
            * Suggestion to open up value lists for the new attributes @maintenanceStatus, @publicationStatus, @maintenanceEventType, and @agentType
            * Suggestion to add new attribute @ agentRole to &lt;agent> in &lt;maintenanceEvent>
            * Remove &lt;localControl> in first draft EAD 4.0
            * Move &lt;filedDesc> out of &lt;control>
        * Variations of EAD 4.0
            * Should we create and provide different flavours to better meet diverse needs of the community
                * Simple or extended version
                * “Text-only” vs “LOD-heavy” that incorporates URIs vs “Print-enabled”
        * &lt;relations>
            * U-turn from removing from EAD to keeping and emphasizing
            * Remove respectively transform “relations-like” existing elements in order to not continue having two ways to (mostly) do the same thing
    * Hague meeting update
        * Discussed sibling elements of &lt;did>, e.g. &lt;scopeContent>, &lt;biogHist> etc
            * Remove nesting,  but look into option to have repeated - and possibly hierarchically-related - &lt;head> elements
            * Move &lt;abstract> out of &lt;did> and add it to all sibling elements of &lt;did> instead (same as &lt;biogHist> in EAC-CPF)
            * Turn &lt;otherFindAid>, &lt;relatedMaterial>, &lt;separatedMaterial>, &lt;controlAcess>, &lt;index>, and &lt;bibliography> into &lt;relation>-s
            * Review &lt;altFormAvail> and &lt;originalsLoc> as well as &lt;accessRestrict>, &lt;legalStatus>, &lt;preferCite>, and &lt;useRestrict> for their potential to be turned into &lt;relation>-s
        * &lt;fileDesc> (pending finalisation)
            * Keep element; move it out of &lt;control>; broaden the scope; rename the element (To be decided)
            * Create an optional, not repeatable plural wrapper for the renamed element
            * Move &lt;controlNote> into &lt;control> and turn &lt;edition> and &lt;p> of &lt;editionstmt> into &lt;eventDescription>-s
            * Use only &lt;title>, &lt;agent>, &lt;eventDateTime>, &lt;place>, and &lt;div> as sub-elements
            * Add option to include a link to an online resource
        * EAD’s relation to other standards I.e. general  interoperability (adapting to underlying model, including specific elements to support crosswalks, mainly referencing to information encoded in other standards and potentially in other locations)
        * PREMIS and RiC -  representation from PREMIS and instantiation from RiC
            * Suggestion to rethink how levels of description are identified in EAD
            * Planned: mapping from RiC to EAD and vice versa
        * Other topics include, Reviewing &lt;accessRestrict> and &lt;useRestrict>, Continue collaboration with NAFAN, Multilinguality, and use cases development
    * 2022-23 plans
        * Continuing major revision of EAD
        * Prepare initial draft of EAD 4.0 to reflect changes from alignment of EAC-CPF and EAD
        * Cooperate with Outreach team for webinars
            * One topic-specific one (e.g. controlled access1, relations, access and use restrictions, born-digital and digitised archival objects)
            * One audience-specific one (aggregators)
* Schema team updates (Mark)
    * Next schema meeting is Friday, November 11th at 9:30 a.m. EST
    * Committee wide decision needed
        * Suggestion to remove control value lists for @maintenanceStatus, @publicationStatus, @agentType, and @maintenanceEventType in control section
            * Feedback needed by November 11th meeting
            * Prescribed values to be left open, or is there a need for the community to have a standard around
            * Can easily be removed from EAD4. After conversation from Boston meeting, leaning towards removing these values
            * Opens up possibility to remove other values, since values provided may not work for everyone
            * If removed, need re-release 
            * Do we actually know all of the possible values that can be used for attributes (i.e. audience - external / internal). Might not know all of terminology that can be used in one context to another (Kerstin)
            * Without controlled list, will need to be managed at local level since not managed at a global level (Mark)
            * Useful to do - suggest vocabularies in areas (e.g. with agent types build LC vocabulary like what PREMIS has done) for community or mint in vocabulary, especially when archives specific to aid interoperability (Elizabeth). Can work into best practices; more work on our part but advantage for community engagement (Mark)
        * ISO 639-2b (or not 2b)
            * Came from use of controlled value lists of value provided for which language codes to associate 
            * 2b (b=bibliographic) which does restrict with values from ISO 639-2 that can be used, though does not affect all language codes
            * Use 2b or restrict -t (t=terminology) terms or just change value in examples to those in ISO 639-2, and allow -t and b terms to live side by side
            * Mark suggests to change value code ISO 639-2 and allow b and -t terms to be valid 
            * Option to open for b and others or keep ISO 639-2b and not allow -t codes to be valid
            * Why not allow it if people define it so we know what it is (Anna-Maria)
            * What do we do with ISO 639-3 has only -t values (Kerstin)
            * Check other codes and see if they need to be aligned between EAC and EAD 
        * User-assigned codes in ISO
            * Should Schematron tell that user-assigned values are valid or invalid? Allow local values (qaa to qtz) in globally used schematron to show as being valid or invalid according to standard? What about deprecated codes? 
                * Making qab invalid, but we could also say it’s valid and provide warning; user needs to specify what you mean
                * Provide warning or flag local values (Kerstin)
                * Not saying they’re invalid
        * Schematron update due to change in IETF - new language tag
        * EAD4 has camelCasing of primary elements, but not much else yet.- don’t start testing until December
* EAC-F (Karin)
    * Testing findings and creating mockups where they are looking into which elements of EAC-CPF can be reused 
        * Kerstin is composing article, won’t publish until they know if people want this
        * Notes in GitHub repository
        * Desire of a testable schema? (Mark) No
* Outreach (Cory)
    * Rita Johnston incoming representative (Collection Management Section liaison)
    * Coordination for upcoming webinars
        * EAC-CPF announcements for November webinar
        * Currently distributing EAD minor update announcement
    * Tutorials and webinars development
        * Planned development of EAD on a Shoestring
        * Scheduled meeting with Description Section for controlled vocabulary webinar 
            * Kerstin to attend and determine overlap
        * Reach out to Cory or Sarah with any upcoming webinars 
* RiC
    * RiC-Conceptual Model 1.0 and RiC-Ontology 1.0 to be released by February or March 2023, as an ICA official recommendation; then RiC-Application Guidelines
    * Committee wide decision needed
        * Cooperation with EGAD
            * Report from EGAD meeting (Silke)
            * Suggestion to share a folder in order to cooperate e.g. on crosswalks and examples?
            * Other?
            * Subteam not needed, all team participation in this group needed
            * Silke acting as official chair of EGAD
        * Own team as suggested on TS EAS 18th of August?
        * Affects all subteams - comment on document in Drive, as opposed to creating an additional subteam (Kerstin) or GitHub? (Florence)
            * How to record and do mapping? (Mark)
            * Need to promote RiC standard, esp. in the US where there may be confusion. Utilise as communication and learning tool for larger community (Elizabeth)
            * Guidelines should include mappings, use cases, and examples… (Florence)
            * Standards and other groups would be interested. Provide access to Drive… (Mark)
* Any other business (time permitting)
    * N/A
* Meetings take place:
    * February (aim: time better for members in the timezones with more 
    * than +5 from GMT)
    * May
    * SAA Annual Meeting
    * October

Thanks to all who attended!
