# CycloneDX VEX Use Cases

These examples provide a wide variety of possible VEX use cases and scenarios.

| Case # | Description |
|------|------|
| [Case-1](Case-1) | <table><thead><tr><th>Single Product</th><th>Single Version</th><th>Single Vulnerability</th><th>Not Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is not exploitable in Acme Product version 2.4.0, even though it’s listed in the NVD as a vulnerability of X, and X is a component of Acme Product v2.4.0 |
| [Case-2](Case-2) | <table><thead><tr><th>Single Product</th><th>Single Version</th><th>Single Vulnerability</th><th>Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is exploitable in Acme Product version 2.4.0. |
| [Case-3](Case-3) | <table><thead><tr><th>Single Product</th><th>Single Version</th><th>Single Vulnerability</th><th>Under Investigation</th></tr></thead></table>A VEX states that the exploitability of CVE-2020-25649 in Acme Product versions 2.4.0 is under investigation. |
| [Case-4](Case-4) | <table><thead><tr><th>Single Product</th><th>Multiple Versions</th><th>Single Vulnerability</th><th>Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is not exploitable in Acme Product versions 2.2.0 through 2.4.0. |
| [Case-5](Case-5) | <table><thead><tr><th>Single Product</th><th>Multiple Versions</th><th>Single Vulnerability</th><th>Affected and Not Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is not exploitable in the current version (e.g. 7.0) of a software product, but it was exploitable in all previous versions after v1.5 |
| [Case-6](Case-6) | <table><thead><tr><th>Multiple Products</th><th>All Versions</th><th>Single Vulnerability</th><th>Not Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is not exploitable in any current version of a family of products made by a particular manufacturer. |
| [Case-7](Case-7) | <table><thead><tr><th>All Products</th><th>All Versions</th><th>Single Vulnerability</th><th>Not Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is not exploitable in any current version of any product made by a particular software developer. |
| [Case-8](Case-8) | <table><thead><tr><th>Single Product</th><th>Multiple Versions</th><th>Single Vulnerability</th><th>Affected and Not Affected</th></tr></thead></table>A VEX states that CVE-2020-25649 is not exploitable in versions 2.0.0-2.7.0, 3.0.0-3.2.0, 3.8.0-4.1.0, and 5.9 of product X. It should be assumed to be exploitable in all other versions. |
| [Case-9](Case-9) | <table><thead><tr><th>Multiple Products</th><th>All Versions</th><th>Multiple Vulnerabilities</th><th>Not Affected</th></tr></thead></table>A VEX states that none of the collection of vulnerabilities known as Ripple20 is exploitable in any of a supplier’s current product versions. |

### Credits

Long-time NTIA SBOM participant Tom Alrich, provided use cases for VEX which have come out of the
NTIA VEX subgroup (now under CISA). This section of the repo contains those cases and examples of how CycloneDX addresses them.