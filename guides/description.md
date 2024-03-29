# Description of born-digital archives  

Once the processing plan is set and the overall arrangement of the accession(s) being processed has been finalized, it is time to think in greater detail about the second half of processing: description. This guide describes CCA's standards for description of born-digital records in spreadsheets and The Museum System (TMS), and includes:

* [Principles and practical guidelines for description of born-digital archives](#descriptionprincipleandpractice)  
* [Fonds-, series-, and project-level description](#higherlevel)
* [File ("groupe")-level description](#groupdesc)
    * [Entering file-level description in processing spreadsheets](#spreadsheetentry)  
    * [Entering file-level description in TMS](#tmsentry)  
       * [Internal management information](#internalmanagement)  
       * [Elements of archival description](#archivalelements)  
* [Item ("pièce")-level description](#itemdesc)

<a name="#descriptionprincipleandpractice"></a>  
## Principles and practical guidelines for description of born-digital archives  

* "Choose to guide, not to map": Let the researcher do their own research, but give them a good enough sense of the content and context of records to know where to focus their energies. Consider the following passage from Maureen Callahan's ["The Value of Archival Description, Considered"](https://icantiemyownshoes.wordpress.com/2014/04/04/the-value-of-archival-description-considered/):  

> When I teach description, I urge workers to evaluate rather than represent records. For instance, does a correspondence series include long, juicy, hand-written letters wherein the writer pours his heart out? Or are they dictated carbon copies based on forms? A title of “Letter from John Doe to Jane Smith” doesn’t tell us this, but an archivist’s scope and content note can. It takes a lot of time to type “Correspondence” and the date a zillion times. Wouldn’t researchers prefer an aggregate description and date range with a nice, full note about what kinds of correspondence with what kinds of information she can expect therein? This is a choice to guide rather than map. 

* "Let the bits describe themselves": Machine-actionable information such as extent, file formats, and filesystem metadata should be captured automatically, never calculated by hand, and rarely transcribed.  
* Born-digital records may not reflect traditional Stage and Purpose architectural terminology/practice - don't force terminology where it doesn't fit.  
* Description will be entered and updated in processing spreadsheets. Entering this data in TMS will require some fields to be manually entered, but you should copy and paste from your processing spreadsheet when possible. Make sure that any revisions to your description are completed prior to entering data into TMS.  
* Don't spend excessive time at the file level. File-level descriptions are largely automated by CCA Disk Image Processor and CCA Folder Processor. In many cases, quickly surveying the included files and adding a title will suffice. Resist the temptation to open and investigate each digital file in a given directory/disk image.  

<a name="higherlevel"></a>  
## Fonds-, series-, and project-level description  

Your higher level (fonds-, series-, and project-level) descriptions should follow the guidelines set out for these levels of description in the overall CCA Archives Processing Manual.  

Fonds, series, and project records must be entered directly into TMS, but should be written and reviewed in a plain text document and/or a spreadsheet first.

Lines about digital materials in Collation statements in fonds-, series-, and dossier-level records should take the following form: "x digital files (y KB/MB/GB)", e.g. "760 digital files (18 GB)".  

<a name="groupdesc"></a>  
## File ("groupe")-level description  

File ("groupe")-level description is the lowest level of description done during typical processing projects, and should follow the guidelines set out in the overall CCA Archives Processing Manual. Description will happen first in spreadsheets. Do not enter any file-level information into TMS until that spreadsheet has gone through the review and approval process with the Digital Archivist.  

Note that all directories of digital content should be described as files ("groupes"), even if they contain only one digital file.

<a name="spreadsheetentry"></a>  
### Entering file-level description in processing spreadsheets  

File-level description should be entered and reviewed in spreadsheets (one spreadsheet per series or project, depending on volume).

| Column | ISAD element | Required? | Value |
| :----: | :------------: | :---------: | :---- |
| Parent | n/a | Yes | Identifier of immediate parent (e.g. series or project) |
| Identifier | 3.1.1 | Yes | Identifier of file (groupe). This should be an archival number composed of the fonds, series, subseries, dossier, and group numbers, as applicable (e.g. "AP500.S1.1996.PR1.001" or "AP174.S2.001") |
| Title | 3.1.2 | Yes | Supplied or original title, according to standard titling procedures. Do not use a file or directory name as a title unless you are unable to provide a better succinct title. |
| Archive creator | 3.2.1 | No | Enter the standard form of name for the fonds creator |
| Date expression | 3.1.3 | Yes | Years only. This information will be pre-populated in description spreadsheets. Revise only when necessary (e.g., if value in file system is clearly false). |
| Date start, Date end | 3.1.3 | Yes | This information will be pre-populated in description spreadsheets. Revise only when necessary (e.g., if value in file system is clearly false). All dates must be in ISO8601 format. Acceptable date formats: YYYY-MM-DD, YYYY-MM, YYYY. If the file has only a single date (e.g. 1990 or 1990-01-20), this should be entered in both Date start and Date end. |
| Level of description | 3.1.4 | Yes | "File" |
| Extent and medium | 3.1.5 | Yes | This information will be pre-populated in description spreadsheets, in the form "x digital files (y bytes/KB/MB/GB/TB)". Unless value is "EMPTY", do not modify except when discussed with Digital Archivist. |
| Scope and content | 3.3.1 | Yes | Add a Scope and Content note if title information needs to be supplemented (e.g., with information about the storage media that files are from), content falls outside scope of your higher level description, or to call attention to records of note. Because groupes of born-digital records are often voluminous and internally complex, detailed scope and content notes will be more common for this material than for other formats. For files from digital media such as floppy disks or CDs, begin note with "Complete contents of ..." or "Partial contents of ..." and the identifier/type of media, as well as any annotations on the media. For groups of born-digital records, the scope and content note field in your processing spreadsheet will be pre-populated with some script-generated information on processing history and common file formats. This information should be retained at the end of the note. *Example scope and content note for Folder Processor-generated SIP*: "Contains 3D computer-aided design files central to the development process of Carbon Tower. The bulk of the design files are in Rhinoceros and are arranged in folders by year. Also includes some Maya renders as well as design and image files resulting from early attempts to model the Carbon Tower in CATIA. Original directory name: "3D CATIA MAYA RHINO". Most common file formats: 3DM, Plain Text File, Initial Graphics Exchange Specification (IGES), Maya Binary File Format, DS_store file (MAC)" |
| Arrangement | 3.3.4 | No | Not necessary at file level but can be used to indicate manual re-arrangement when it has been done for some files but not others within the same series. |
| Accession number | n/a | Yes | Versement number |
| Conditions governing access | 3.4.1 | No | Only enter at file-level when conditions governing access differ from general conditions set at higher level. |
| Conditions governing reproduction | 3.4.2 | No | Only enter at file-level when conditions governing reproduction differ from general conditions set at higher level. |
| Language | 3.4.3 | No | Do not enter at file level except under rare circumstances and when discussed with an Archivist. |
| Finding aids | 3.4.5 | No | Do not enter at file level except under rare circumstances and when discussed with an Archivist. |
| Related units of description | 3.5.3 | No | Do not enter at file level except under rare circumstances and when discussed with an Archivist. |
| Note | 3.6.1 | No | Do not enter at file level except under rare circumstances and when discussed with an Archivist. |
| Folder number | n/a | No | n/a |
| Box number | n/a | No | n/a |
| Subject access points | n/a | Yes | "born-digital" (and, optionally, another object type from the list in the File Descriptive Standards - e.g. for a directory of videos, you may enter both "born-digital" and "moving images". When you input multiple values, be sure they are separated with a pipe) |
| Name access points | n/a | No | Optionally, enter name access points (and roles) of people or corporate bodies associated with or resposible for the creation of the file. Do not enter at file level except under rare circumstances and when discussed with an Archivist. |  
| Description status | n/a | No | Leave blank |
| Level of detail | n/a | No | Leave blank |

<a name="tmsentry"></a>  
### Entering file-level description in TMS  

Once your processing spreadsheet is reviewed and approved by the Digital Archivist, use the following instructions to enter the information into TMS, copying and pasting from the spreadsheet when possible. This can be done most efficiently by making use of Models. Models exist for file-level description of various types of material already; for most efficient work, create a custom version of the "Archives - Files - Born Digital" model for your archive, containing the following information:  

* Archives creator  
* Fonds number  
* Credit Line

Especially for high-volume collections, using an archive- and type-specific model for data entry will greatly speed up the process.

The only types of information you should enter into TMS that will not be found in your processing spreadsheet are associations and the elements in [Internal management information](#internalmanagement) below (note that many of these are already entered in the existing Archives data entry models).

<a name="internalmanagement"></a>
#### Internal management information  

| TMS field | Value |
| :-----: | :-----: |
| Department/Département| "Archives" |
| Virtual Object/Objet virtuel | No (unchecked) |  
| Status flags/Indicateurs du status de l'objet | "traitement en cours" (to be batched changed to "inventaire" when finding aid is published) |
| Credit line/Ligne de credit | Enter as usual |  
| Alternate number | Enter fonds number (AP###) as an alternate number for all records within an archive, using description "fonds number". |  
| Object count/Nombre de l'objet | "1" |  
| Object name/Nom de l'objet | "File" |  
| "Object type" attribute | "born-digital"/"né numérique" (and, optionally, another object type) |  

<a name="archivalelements"></a>
#### Elements of archival description  

| Column in spreadsheet | TMS field | Instructions |
| :-----: | :-----: | :------ |
| Parent | Elements reliés | Link object to versement via "Est inclus dans" association type |
| Identifier | Object number/Numéro de l'objet | Copy and paste from spreadsheet |
| Title | Title/Titre | Copy and paste from spreadsheet |
| Creators | Personne(s) et institution(s) | Enter creator as a constituent with role "archive creator" |
| Dates | Dates | Enter the date values within "Désignation date" |
| Level of description | Classification | "groupe" |
| Extent and medium | "Collation" text entry | Copy and paste from spreadsheet |
| Scope and content | Content description/Description du contenu | Copy and paste from spreadsheet |
| Arrangement | "1.8B13-classement" text entry | Copy and paste from spreadsheet (if applicable) |
| Accession number | Elements reliés | Link object to versement via "Provient de" association type |
| Conditions governing access | "1.8B16a-restrictions à la consultation" text entry | Copy and paste from spreadsheet (if applicable) |
| Conditions governing reproduction | "1.8B16c-restric. à l'utilis. et repro." text entry | Copy and paste from spreadsheet (if applicable) |
| Language | "1.8B14-langue" text entry | Copy and paste from spreadsheet (if applicable) |
| Finding aids | "1.8B17-instruments de recherche" text entry | Copy and paste from spreadsheet (if applicable) |
| Related units of description | "1.8B20a-docs reliés meme fonds" text entry | Copy and paste from spreadsheet (if applicable) |
| Note | "1.8B21-générale" text entry | Copy and paste from spreadsheet (if applicable) |  
| Name access points | Personne(s) et institution(s) | Enter as constituents with appropriate roles (if applicable) |  

<a name="itemdesc"></a>  
## Item ("pièce")-level description  

At CCA, we typically do not process digital files at the item-level. Item-level metadata is instead automatically generated by Archivematica and saved into an `amdSec` in the AIP METS file for each digital file within a SIP.  
