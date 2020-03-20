## Short Manual for Safeguarding Good Research Software Development 
### Background Analysis
Careful software development is an essential part of modern research practice. The German Research Foundation's (DFG) [Guidelines for Safeguarding Good Research Practice](https://www.dfg.de/en/research_funding/principles_dfg_funding/good_scientific_practice/index.html) therefore also refer to research software and establish minimum standards and practices which we further specify for ourselves.
The following table shows the most important software-specific aspects of the [Code of Conduct](https://www.dfg.de/download/pdf/foerderung/rechtliche_rahmenbedingungen/gute_wissenschaftliche_praxis/kodex_gwp_en.pdf).


|<center> Quote from the DFG's Code of Conduct| <center> Remark
:--------------------------------------------:|:------:
_As a rule, researchers make all results available as part of scientific/academic discourse_ | Exceptions must be justified by a clear statement of conflicting rights.
_Software programmed by researchers themselves is made publicly available along with the source code._ |	An appropriate embargo period may be used.
_The source code of publicly available software must be persistent, citable and documented._    |   Anything else is not a properly executed publication.  
_Where research software is being developed, the source code is documented._  | Documentation as part of good scientific practice is independent of any publication plans.
  
### How-To

Research software includes a minimum of functional scope and intellectual level of creation. If this is fulfilled, the DFG guidelines mentioned above apply. Research software is then a result that is introduced into scientific discourse within an appropriate time and in an appropriate form.

##### Versioning

If a scientific result is generated with software, the version used is named and archived. For self-written software the development stage should be marked appropriately, since application scenarios in an active research environment can expand rapidly beyond the intended scope.

| <center> Suitable Version&#160;Number|<center> Example Scope 
:---:|:---:
| 0.0.x|An (inefficient) "proof-of-principle prototype" that is not intended to become stable, professionally tested and generally usable, because the software has fulfilled its (unique) task.  
  | &ge; 0.1  and &lt; 1.0 | Perhaps the final range of functionality has not been reached yet, but the software is supposed to work stable beyond the initial application examples and the program structure is suitable for further development.
| &ge; 1.0| There are some extensive test examples and an own documentation for the software. A productive operation is possible. 
  
##### Documentation

Software should be appropriately commented and documented, even if no public release is planned. Research software must be documented in a way that is understandable to the reader. For the sake of scientific progress, a level of documentation matching the usefulness of the software should be provided.
  
Documentation&#160;Level	| <center>Definition 
:--:|:--:
Minimal | Program or function names and other notes capture the intention of each part of the program in such a way that it can be decided locally whether a part is functioning correctly or not.
Standard | Best practices are taken into account (e.g. c++ core guidelines or pythons pep8).
Comprehensive | Software in productive operation should have a technical documentation and a short manual for users.
  
The standard documentation level is appropriate if a software is expected to be relevant for more than one publication or if it is worked on in a team. It is recommended to use [lint software](https://en.wikipedia.org/wiki/Lint_(software)) like pylint, checkstyle or splint that verify that good coding standards prevail. 
    
##### Publication

A scientific publication must contain the information necessary for the scientific discourse. In the case of self-written research software, this usually includes a persistent link to the source code of the software version used. If free access to the source code is not possible in time, at least the algorithms used must be explained. In such cases the option of a temporary embargo must be considered. Any inaccessibility must be explained transparently, stating the reason or an embargo time. One possible reason is, for example, to protect the (intellectual) property of (non-scientifically) exploitable components from being published.
  
##### Small Components
  
Research software in a broader sense also includes commands. For example, in order to enable good traceability of work processes, a command for controlling software can contain valuable implicit knowledge that is worth being made explicit (by publishing).
  
##### Bearable Re-use
  
Publishing software prototypes with very narrow functionality and a very minimal documentation may not always correspond to the performance requirements and quality responsibility of science. Publishing cannot be a goal for itself. The research interest and usefulness for the scientific discourse must always guide the action.  
  
##### Checklist

* Lint software is ready for use
* The purpose of the software is concisely formulated
* The quality assurance and documentation (processes) correspond to the intended maturity level of the software
* Attended a software quality course
* The intention of each function is readily apparent (self-explanatory names or comments)
* Licences clarified
  
