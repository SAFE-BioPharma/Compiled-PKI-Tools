# SAFE-BioPharma Pre-Compiled Tools

1. PKIUtilsTool
	- This tool can be used for various PKI certificate file conversions including: bundles (.p7b, .p7c), PEM, certificates (.der, .cer, .crt), password-protected certificate files (.jks, .p12, .pfx) and  the tool can convert an EU trust list into a bundle or a folder of certs.

2. TL-Manager-SAFE-Biopharma-Concept
	- This tool can be used to build US trust lists in an EU compliant xml schema. This requires intimate knowledge of how the EU schema is architected because error checking has been disabled in order to accomodate some US identifiers. The tool can also digitally sign the XML file with an enveloped XAdES digital signature
