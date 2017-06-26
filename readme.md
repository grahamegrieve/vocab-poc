HL7 Vocbulary Repository

This repository contains the master content for the vocabulary 
content for HL7 v2, v3, CDA, CIMI and FHIR.

For documentation around working with the vocabulary content,
see http://wiki.hl7.org/index.php?title=Vocabulary_Maintenance_Process

This repository contains the following content:

* v2: table definitions for v2 content
* v3: code systems, value sets, and concept domains defined by v3
* cda: value sets defined by CDA implementation guides (e.g. CCDA)
* fhir: code systems, value set, and concept maps defined by FHIR 
* other: other miscellaineous terminology definitions managed by HL7
* tools: files used by the build tooling. Toolsmiths only
* cache: analysic content managed by the tools, but checked into Git for performance reasons. Do not edit
* build.sh/build.bat: run the build (check all content is ok)

= Build Process =

The build process performs the following tasks:
- load and validate all the content - technical and policy verification
- produce output for v2, v3, cda, and fhir build processes
- produce formal change proposals, delta files


