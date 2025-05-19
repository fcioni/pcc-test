# NACO 024 Best Practices Guidelines  

## Principles  
The PCC URIs in MARC Pilot recognizes that there are valid use cases for including URIs in NACO records, in order to:  
- Enhance discovery and identification for all users  
- Incorporate the LC/NACO Authority File into the identity management environment  
- Move the LC/NACO Authority File away from the single-silo environment of authority control.  

However, the following is equally true:  
- The NACO authority records is not a hub to record all of the possible URIs that can be found  
- The LC/NACO Authority File is not intended to be a reconciliation service for URIs  
- Large numbers of 024s in a NACO record create visual clutter for many users and often duplicate information which is not necessary  
- Large numbers of 024s in a NACO record created unnecessary maintenance of authorities in local systems.  

With these considerations in mind, the PCC URIs in MARC Pilot proposes these best practice recommendations when adding URIs in the 024 field of NACO authority records.  

The recommendations are not prescriptive and should be considered as best practices to facilitate the exchange of information in a shared databased environment. Catalogers are expected to use judgement and common sense, concentrating on need and usefulness to the overall library community when adding 024s.  

## Best Practice Recommendations  
- As a general rule, limit the maximum number of 024s in a NACO authority record to five (5)  
- 024 fields may be added in any order, adding new ones after existing ones, according to the needs of the community or institution  
- Do not routinely delete or change existing 024 fields when adding new 024 fields. If an authority record already contains five or more 024 fields, and the cataloger wishes to add one of the “Core” vocabularies identified below, an exception is made in this case for the maximum number of 024 fields in the record, and the “Core” vocabulary may be added  
- Record URIs from vocabularies that provide additional information rather than repeating information that is already present in other 024 fields whenever possible  
- Generally, if a $1 contains a URI known to be mapped in a widely used external service (e.g. VIAF, Wikidata), additional URI(s) that are also found in those services need not be added  
- If both an authority URI and a RWO URI are given from one source, include both subfield $0 and subfield $1 in the same 024 field  
- When there is an “equivalence” conflict, exercise cataloger's judgment in deciding which NACO record(s) should include an 024 field to the vocabulary  
  - For example, a vocabulary does not treat a new name for a corporate body as a new entity; the vocabulary considers linear name changes as variant terms, not as separately-established terms. NACO creates a new authority record when a corporate entity changes its name.  
- MARC allows a source to be specified in subfield $2 of the 024 field (first indicator = 7), and an unspecified type of standard or code to be recorded with no subfield $2 (first indicator = 8). The examples below show both options. Cataloger’s judgment determines the choice; there is a preference for the source to be specified in subfield $2 (first indicator = 7) for ease of identification.  
- Keep in mind what happens when duplicate records are merged in other systems. When that happens, NACO 024 URIs may not resolve any longer. For this reason, when evaluating a source for use in a NACO 024 field, take into account how duplicates are resolved in the source itself.
- **Here I am adding something - I am part of a group who are working on more Best Practice Recommendations for this document, and here is one of them.**

The PCC URIs in MARC Pilot recommends that catalogers use the following sources, considering them a "Core" group of PCC-sanctioned vocabularies. The "Core" group will be evaluated over time and new vocabularies may be added, based on PCC needs and use.  


