# JSON Schema for Requirements of EUROCONTROL SWIM Specifications
This repository hosts JSON Schema(s) - and the actual JSON data files - used to represent the requirements that can be found in EUROCONTROL SWIM Specifications.
The Schema allows to represent the requirements included in:
 - EUROCONTROL Specification for SWIM Service Definition
 - EUROCONTROL Specification for SWIM Service Description
 - EUROCONTROL SWIM Information for SWIM Information Definition
 - EUROCONTROL SWIM for SWIM Technical Infrastructure (TI) Yellow Profile

Nevertheless, JSON data files are currently being produced only for SWIM Technical Infrastructure Yellow Profile Specification.  

The JSON Schema is using JSON Schema draft 2020-12.
The repository is organized in folders organized as follows:
+ JSONschema2020-12 (i.e. A folder indicating the JSON Schema draft version used)
--- + 1.0.0 (i.e. A folder indicating the version - according to Semantic Versioning 2.0 principles - of the JSON Schema. If the Schema will evolve during time, new folders will be created according to the version)

**Branching Strategy**

During the development of a new version, a dedicated Branch to host the development of that version will be created (e.g. "dev/1.0.0"). Once it is concluded, the new version will be merged in the main branch. 
