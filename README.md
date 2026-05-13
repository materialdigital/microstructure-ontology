# Microstructure Ontology

Description: PMD Core application ontology generated via ODK Template.


More information can be found at http://obofoundry.org/ontology/microstructure

Active development is on [MiroBoard](https://miro.com/welcomeonboard/VFlwdGlCQ2pVWG13WEQyTk52WEYxa00rV0dSeHFXYXRMWEdiRDdSMW9lVHZkOGY0MUNhUXNlK28vajVXY2VnYStPVitWKytYUTBpQStPMGRsZjhTT2YrWE1sRGRtb2MxSU41MTJVd1VHcDFldExUZ3FoQWM1d2FXUjZKOEM5RTZBS2NFMDFkcUNFSnM0d3FEN050ekl3PT0hdjE=?share_link_id=457927824819)

## Versions

### Stable release versions

The latest version of the ontology can always be found at:

https://w3id.org/pmd/microstructure.owl

(note this will not show up until the request has been approved by obofoundry.org)

### Editors' version

Editors of this ontology should use the edit version, [src/ontology/microstructure-edit.owl](src/ontology/microstructure-edit.owl)

## Contact

Please use this GitHub repository's [Issue tracker](https://github.com/materialdigital/materialdigital/microstructure-ontology/issues) to request new terms/classes or report errors or specific concerns related to the ontology.

## Acknowledgements

This ontology repository was created using the [Ontology Development Kit (ODK)](https://github.com/INCATools/ontology-development-kit).
## Development

This ontology is developed using OWL and managed with the [Ontology Development Kit (ODK)](https://github.com/INCATools/ontology-development-kit).
To contribute or edit:

- Open  in [Protege](https://protege.stanford.edu/) or your preferred OWL editor.
- Create new entities within the namespace .
  Example IRI: 
  (the prefix portion is always uppercase).
- Use the  for automation:
  -  : Run quality control (reasoner checks, syntax validation).
  -  : Update imported ontologies via SLME extraction.
  -  : Build all release artifacts (TTL, OWL, JSON formats).
  -  : Sync repo structure after editing .

## Import Architecture

The modular import structure used by this ontology:



## Repository Structure

| Path | Description |
|------|-------------|
|  | GitHub Actions CI/CD workflows |
|  | Ontology source files (edit here) |
|  | Modular OWL component files |
|  | Extracted import modules (SLME) |
|  | ROBOT template TSV files for components |
|  | External ontology imports configuration |
|  | Creator names for ID range allocation |

## Contribution

We welcome contributions to the DiStEL Microstructure Ontology ontology!

- **Issue tracker**: [github.com/materialdigital/microstructure-ontology/issues](https://github.com/materialdigital/microstructure-ontology/issues)
  Report errors, request new terms, or flag modeling concerns.
- **Discussion forum**: [github.com/materialdigital/microstructure-ontology/discussions](https://github.com/materialdigital/microstructure-ontology/discussions)
  Discuss modeling decisions with the community.
- **Application ontology template**:
  [application-ontology-template](https://github.com/materialdigital/application-ontology-template/)
  The framework used here; mirrors pmdco with all its modules.
- **PMD Playground Meetings**: Every second Friday, 1-2 pm CET.
  [Register via mailing list](https://www.lists.kit.edu/sympa/subscribe/ontology-playground?previous_action=info)
- **Contact**: [info@material-digital.de](mailto:info@material-digital.de)
