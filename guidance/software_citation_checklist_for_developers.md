# Software Citation Checklist for Developers

Produced by the FORCE11 Software Citation Implementation Working Group

Editor: Neil Chue Hong (ORCID: 0000-0002-8876-7606). 

Contributors: Alice Allen (ORCID: 0000-0003-3477-2845), Alejandra Gonzalez-Beltran (ORCID: 0000-0003-3499-8262), Anita de Waard (ORCID: 0000-0002-9034-4119), Arfon M. Smith (ORCID: 0000-0002-3957-2474), Carly Robinson (ORCID: 0000-0002-8523-1478), Catherine Jones (ORCID: 0000-0002-5112-835X), Daina Bouquin (ORCID: 0000-0003-2626-3688) , Daniel S. Katz (ORCID: 0000-0001-5934-7525), David Kennedy (ORCID: 0000-0002-9377-0797), Gerry Ryder (ORCID: 0000-0001-7444-4489), Jessica Hausman (ORCID: 0000-0002-1861-1526), Lorraine Hwang (ORCID: 0000-0002-1021-3101), Matthew B. Jones (ORCID: 0000-0003-0077-4738), Melissa Harrison (ORCID: 0000-0003-3523-4408), Mercè Crosas (ORCID: 0000-0003-1304-1939), Mingfang Wu (ORCID: 0000-0003-1206-3431), Peter Löwe (ORCID: 0000-0003-2257-0517), Robert Haines (ORCID: 0000-0002-9538-7919), Scott Edmunds (ORCID: 0000-0001-6444-1436), Shelley Stall (ORCID: 0000-0003-2926-8353), Sowmya Swaminathan (ORCID: 0000-0002-0285-4910), Stephan Druskat (ORCID: 0000-0003-4925-7248), Tom Crick (ORCID: 0000-0001-5196-9389), Tom Morrell (ORCID: 0000-0001-9266-5146), Tom Pollard (ORCID: 0000-0002-5676-7898). 

DOI: 10.5281/zenodo.3482769

## Background

This document provides a minimal, generic checklist that developers of software (either open or closed source) used in research can use to ensure they are following good practice around software citation. This will help developers get credit for the software they create, and improve transparency, reproducibility, and reuse.

## Checklist for making a release of your software citable

- Have I assigned an appropriate license to my software?
- Have I described my software properly, using an appropriate metadata format, and included this metadata file with my software?
  - Have I given my software a clear version number?
  - Have I determined the authors to be credited for this release of my software, and included this in my metadata file?
- Have I procured a persistent identifier for this release of my software?
- Have I added my recommended citation to the documentation for my software?

There are other things that we consider as good practice for research software development which are not directly related to making software citable - these are described in the Additional Guidancee below.

## License

This guidance is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license. You are free to share and adapt this material for any purpose, including commercially, as long as you give [appropriate credit](https://wiki.creativecommons.org/wiki/License_Versions#Detailed_attribution_comparison_chart), provide a [link to the license](https://creativecommons.org/licenses/by-sa/4.0/), indicate if [changes were made](https://wiki.creativecommons.org/wiki/License_Versions#Modifications_and_adaptations_must_be_marked_as_such), and you distribute your contributions under the same license as the original. More information: https://creativecommons.org/licenses/by-sa/4.0/

## Additional Guidance on Software Citation for Developers

### Why is software citation important?

Software is part of the research process, across a wide range of disciplines and domains, and it is therefore important that pieces of software that have contributed to the research are cited. 

Software citation is vital in the acknowledgment of the crucial role of software in research, as it allows researchers publishing software rather than papers to participate in the academic credit system.

The scholarly communications system that underpins research relies on accurate citations to ensure research integrity, give appropriate credit and show dependencies with other works. As one step towards reproducing a computational procedure, researchers need to be able to access all inputs to the procedure including the specific version of software packages used to produce the original results. Research software should be as open as possible to enable traceability and reproducibility of research results.

Members of the FORCE11 community, representing authors, developers, researchers, publishers and funders, have published the Software Citation Guidelines [1] to encourage broad adoption of a consistent policy for software citation across disciplines and venues. This checklist aims to provide guidance to make it easier to implement these principles as a developer.
