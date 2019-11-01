# TS-EAS - EAC-CPF team

**Place**: Virtual meeting, Zoom  
**Date**: Friday, 1 November 2019, 7am Boston/11am London/12pm Berlin/10pm Melbourne 

**Connection**: 
Join from PC, Mac, Linux, iOS or Android: https://yalelibrary.zoom.us/j/109550628   
Or iPhone one-tap: US: +16465588656, 109550628#  or +16699006833, 109550628#   
Or Telephone: Dial (for higher quality, dial a number based on your current location): 
US: +1 646 558 8656  or +1 669 900 6833  or +1 855 880 1246 (Toll Free) or +1 877 853 5257 (Toll Free)
Meeting ID: 109 550 628  
International numbers available: https://zoom.us/u/em7KBSS8T

**Apologies**: Karin, Kathy, Mark, Wim

## Agenda

### 1. Organisationl Matters
- Kathy sends her apologies, but she will draw out of the virtual meetings and also won't be able to contribute with regard to preparing any documents ahead of meetings (including the meeting in Berlin); she is trying to come to Berlin, however
- Wim sends his apologies, but he will have to draw out of the virtual meetings, as he can't do Mondays and Fridays
- Silke will check with Karin and Mark to possibly get more TS-EAS members involved in the EAC-CPF team
- Preparing Berlin meeting: official invites will be sent after Standards Committee meeting in November/December; if anyone needs the invite earlier, please contact Silke
- Use of GitHub in connection with TS-EAS Google Drive: keep GitHub as public/official space, but make use of Google Drive for notes taking during the meetings and working documents in progress

### 2. Minutes for Austin meeting
- Minutes updated according to feedback received
- Currently missing: GitHub issue for @certainty; Silke will add this
- Silke will add the minutes on GitHub and then send notification to EAC-CPF team and TS-EAS as a whole
- Use as basis for text on website
  - Include details as far as possible, but not to encoding level
  - Kerstin to prepare draft until 15 November and ask for feedback until 22 November; no reaction, means approval
  - Ailie to then review text and forward to Gerhard for publication
- Ailie's part on dates is essentially done
- Silke and Mark's parts on names and assertion description will be updated; Silke's part is already done, Mark's part is in progress and will be discussed during the next meeting on 22 November   
- Aaron and Gerhard are preparing a paper on relations for late 2019 / early 2020, ideally allowing at least two months for review ahead of the Berlin meeting
- Currently open question around topic of identifiers and picking up on this in preparation for Berlin; Silke looking at this in the context of getting new members involved in the work

### 3. EAD Reconciliation
- Next steps: question about how to best group existing issues on GitHub; we've done the "easy vs complex" grouping, but need to tackle the "complex" ones now
  - Pending topics from Austin meeting
  - EAD Reconciliation as additional topic to keep in mind
    - For EAC-CPF, agree to work based on the assumption that we will move towards a joint TS-EAS and that this will lead to a shared naming convention of having everything in small letters
    - Question of whether or not to create a separate branch for all EAD Reconciliation issues? - Silke to check with Karin
    - Potential next steps: start with shared elements that differ in the question of being mandatory/optional, i.e. &lt;citation>, &lt;dateRange> / &lt;daterange>, &lt;dateSet> / &lt;dateset>, &lt;event>, &lt;fromDate> / &lt;fromdate>, &lt;item>, &lt;toDate> / &lt;todate> - Ailie to look at all date related elements, Silke to look at remaining ones - both for meeting on 22 November
    - Potential next steps: Kerstin to look at shared elements that differ in content model, i.e. &lt;abstract>, &lt;biogHist> / &lt;bioghist>, &lt;chronItem> / &lt;chronitem>, &lt;chronList> / &lt;chronlist>, &lt;citation>, &lt;control>, &lt;date>, &lt;event>, &lt;fromDate> / &lt;fromdate>, &lt;function>, &lt;item>, &lt;legalStatus> / &lt;legalstatus>, &lt;list>, &lt;occupation>, &lt;p>, &lt;part>, &lt;recordId> / &lt;recordid>, &lt;relations>, &lt;source>, &lt;toDate> / &lt;todate>, to see whether there are "easier" ones to start with - aim at taking these decisions in virtual meetings and concentrating on more complex ones during Berlin meeting
- For information: 
  - Shared elements - https://docs.google.com/document/d/18I7C9UiK8OYJ2ASQqAecRcP4fH92rvXV3yp924WZkD0/edit#
  - Similar elements - https://docs.google.com/document/d/19iKmg4KkBwBBjmfo9AfG78fk4ltuvtpdpklBQcczkK4/edit#
  - Comparison table - https://docs.google.com/spreadsheets/d/13XT1lHfhEJiZ06KVeYtRu0f3ke20_9vZKoRuzKM-Ll0/edit#

### 4. Topic: Names
Confirmed decisions
- Rename &lt;nameEntryParallel>, see issue https://github.com/SAA-SDT/eac-cpf-schema/issues/66
  - Use &lt;nameentryset> as a more general term for the wrapper element
  - Have &lt;nameentryset> as optional and repeatable
- Indicate the &lt;nameentryset> as being used for parallel name entries (as per the US usage) via `@localType`
  - As `@localType` already exists and is not used with a fixed values list, this would mean no schema change is required, but mainly changes in the tag library, examples and other documentation
  - Silke to ask Kathy for real-life example for usage of "parallel" in the US; ideally we'd want to have an example for other uses of `@localType` in &lt;nameentryset>
  - Silke to create a GitHub issue and label as "Documentation"
- Recommend use of values "translation", "former", "previous" etc. with `@localType` of &lt;nameentry>
  - Silke to create a GitHub issue and label as "Documentation"
- Add new attribute `@status` with pre-defined / closed list of values - "authorized" and "alternative", see issue https://github.com/SAA-SDT/eac-cpf-schema/issues/70 
- Decline the suggestion to add attribute `@normal` from EAD3 (m.access elements group), see issue https://github.com/SAA-SDT/eac-cpf-schema/issues/72

### 5. AOB
- Ailie had introduction to Tag Library with Alex
- Next steps for issue https://github.com/SAA-SDT/eac-cpf-schema/issues/62 - TEI updated, pull request done by Alex, Ailie to pick up on creating HTML / PDF and send to Gerhard

### 6. next meetings
- Friday, 22 November 2019, 7am Boston/12pm London/1pm Berlin/11pm Melbourne  
  - Apologies from Kerstin, potentially Karin as well
  - Final approval of minutes, pick up on remaining aspects around names, potentially also start further conversation on assertion description
- Friday, 20 December 2019, 7am Boston/12pm London/1pm Berlin/11pm Melbourne 
- Friday, 31 January 2020, 7am Boston/12pm London/1pm Berlin/11pm Melbourne 
- Friday, 28 February 2020, 7am Boston/12pm London/1pm Berlin/11pm Melbourne 
