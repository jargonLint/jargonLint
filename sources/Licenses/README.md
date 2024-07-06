## Motivation

Licenses, such as those from [Creative Commons](https://creativecommons.org/licenses/), are often miswritten and mismatches between version statements (2.0 or v2) are not easy to track. The Licenses.yml rule aims to comprehensively solve these problems.

We preferred to adopt the list of Debian-compatible licenses due to the fact that Debian, as a reliable organization, is also relatively selective in the licenses it accepts. Furthermore, the information provided with the [Debian Free Software Guidelines](https://wiki.debian.org/DebianFreeSoftwareGuidelines) (DFSG) is accessible and permissively licensed.

## Methodology

1. We create a basic and regex capable list of phrases from the DFSG-compatible Licenses
2. Separated licences from GNU and Creative Commons under their own headings
3. Added other BSD and Creative Commons licenses
4. Removed licenses that are too short or use common words, such as Artistic License 1.0
5. Removed superseded licenses, such as IBM Public License 1.0
6. Added versions specified within the DFSG-compatible Licenses page
7. Added updated versions for old licenses, such as Eclipse Public License 2.0
8. Added corrections for licenses where versions are significant or emphasized, such as GPLv2

## Notes

We added the [GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.html) (GFDL), which Debian explicitly [rejects](https://people.debian.org/~srivasta/Position_Statement.xhtml). The reason for this addition is that many documents we can use, such as the [SUSE style guide](https://documentation.suse.com/style/current/single-html/docu_styleguide/), are licensed under GFDL.

We added the [European Union Public Licence](https://commission.europa.eu/content/european-union-public-licence_en) (EUPL) since the EU endorses it.

We can add the Apache license when the appropriate correction is complete for the Apache web server.

## Sources

1. Debian Compatible Licenses
    - Link: [The DFSG and Software Licenses](https://wiki.debian.org/DFSGLicenses)
    - License: [MIT (Expat)](https://salsa.debian.org/webmaster-team/webwml/-/blob/master/english/legal/licenses/mit.wml?ref_type=heads)
    - Retrieved at: 2024-07-05
