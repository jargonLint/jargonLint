# Licenses.yml

## Motivation

Licenses, such as those from [Creative Commons](https://creativecommons.org/licenses/), are often miswritten and mismatches between version statements (2.0 or v2) are not easy to track.
The Licenses.yml rule aims to comprehensively solve these problems.

We preferred to adopt the list of Debian-compatible licenses due to the fact that Debian, as a reliable organization, is also relatively selective in the licenses it accepts.
Furthermore, the information provided with the [Debian Free Software Guidelines](https://wiki.debian.org/DebianFreeSoftwareGuidelines) (DFSG) is accessible and permissively licensed.
You can review a comparison of Debian-compatible licenses with the list of licenses approved by other organizations in this [table](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses#Approvals).

We also reviewed the [SPDX](https://spdx.dev/) which is developed under the Linux Foundation to develop open standards in SBOM (software bill of materials) documents.
In particular, we relied on the [SPDX licenses list](https://spdx.org/licenses/) to avoid overcorrections and in deciding which versions of licenses to include.

## Methodology

1. Created a basic and regex capable list of phrases from the DFSG-compatible Licenses
2. Reviewed primary sources and Wikipedia articles to find the appropriate form to reference the licenses
3. Separated licences from GNU and Creative Commons under their own headings
4. Removed items from the list:
    - Licenses where the abbraviations are too short or use common words: Artistic License 1.0
    - Superseded licenses: IBM Public License 1.0
5. Made additions to the list:
    - Other BSD licenses
    - [International Creative Commons licenses](https://creativecommons.org/licenses/list.en#international-40)
    - License for Creative Commons Public Domain: CC0 1.0
    - License versions that were approved by both the OSI (Open Source Initiative) and FSF (Free Software), as listed by the SPDX
6. Created an exceptions section to prevent correcting SPDX short identifiers.

## Notes

We added the [GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.html) (GFDL), which Debian explicitly [rejects](https://people.debian.org/~srivasta/Position_Statement.xhtml).
The reason for this addition is that many documents we can use, such as the [SUSE style guide](https://documentation.suse.com/style/current/single-html/docu_styleguide/), are licensed under GFDL.

We added the [European Union Public Licence](https://commission.europa.eu/content/european-union-public-licence_en) (EUPL) since the EU endorses it.

We can add the Apache license when the appropriate correction mentioned in issue #42 is added for the Apache web server.

## Sources

1. Debian-Compatible Licenses
    - Link: [The DFSG and Software Licenses](https://wiki.debian.org/DFSGLicenses)
    - License: [MIT (Expat)](https://salsa.debian.org/webmaster-team/webwml/-/blob/master/english/legal/licenses/mit.wml?ref_type=heads)
    - Retrieved at: 2024-07-05

2. Creative Commons Licenses
    - Link: [Licenses List](https://creativecommons.org/licenses)
    - License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
    - Retrieved at: 2024-07-05

3. SPDX License List
    - Link: [License List]([https://github.com/spdx/license-list-data/blob/main/licenses.md?plain=1](https://github.com/spdx/license-list-data/blob/41edd7ee3a28604391226c7472299c7f600c6cae/licenses.md))
    - License: [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0)
    - Retrieved at: 2024-07-14
