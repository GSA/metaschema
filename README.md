# Metaschema

Metaschema provides a common, format-agnostic modeling framework supporting schema, code, and documentation generation *all in one*.

Current modeling technologies (i.e. XML Schema, JSON Schema, Schematron) are:

- Uneven in their modeling expressiveness and validation capability;
- Unable to express a single model that applies to all supported formats;
- Bound to specific formats (i.e., XML, JSON, YAML); and
- Time-consuming and labor-intensive when maintaining multiple format-specific models.

In addition to these basic challenges, there is a need to:

- Express and validate cross-instance relationships;
- Generate parsing code in multiple programming languages;
- Support lossless content conversion between all supported formats; and
- Maintain format-specific documentation.

To address the challenges above, Metaschema supports automated:

- Code and documentation generation;
- Robust rules-based, format agnostic validation capabilities; and
- Content conversion between supported formats (i.e., XML, JSON, YAML).

Metaschema achieves this with:

- A modeling abstraction that unifies the modeling and validation capabilities of existing schema and validation technologies.
- Tools that automatically generate code, schemas, documentation, and format-appropriate content converters from Metaschema-based models.

## Relationship to usnistgov/metaschema

This fork is based on the Metaschema work from [usnistgov/metaschema](https://github.com/usnistgov/metaschema). This fork was established to support the design, implementation, and testing of new Metaschema features needed by GSA [FedRAMP](https://fedramp.gov) to support various data modeling and data validation initiatives.

This effort is intended to be complimentary to the NIST Metaschema efforts. Changes in this repository are intended to be backwards compatible with NIST Metaschema, adding new features and functionality. Changes here are periodically contributed back to the usnistgov/metaschema repository to maintain alignment.

 We accept [contributions here](https://github.com/GSA/metaschema/blob/main/CONTRIBUTING.md) or you can [contribute to the NIST upstream](https://github.com/usnistgov/metaschema/blob/main/CONTRIBUTING.md).

## Resources

- [Metaschema Specification](https://pages.nist.gov/metaschema/specification/)
- [Getting Started with Metaschema](https://pages.nist.gov/metaschema/tutorials/)
- [Metaschema Use Cases](https://pages.nist.gov/metaschema/use/)
- [Metaschema XML Schema and XML and JSON Data Type Schemas](https://github.com/usnistgov/metaschema/tree/main/schema)

## Related work

- A [Java implementation](https://github.com/usnistgov/metaschema-java) provides Metaschema parsing, data instance validation and parsing, content conversion, Java code generation, and XSD and JSON schema generation capabilities.
- An [XSLT implementation](https://github.com/usnistgov/metaschema-java) provides data instance validation, content conversion, documentation generation, and XSD and JSON schema generation capabilities.

## Contact us

Fork Maintainer: [David Waltermire](https://github.com/david-waltermire)

Email FedRAMP: [oscal@fedramp.gov](mailto:oscal@fedramp.gov)

Chat with us: [Gitter OSCAL/metaschema](https://gitter.im/usnistgov-OSCAL/metaschema)
