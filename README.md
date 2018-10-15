# UMLSpecificationReportMD

This is a MagicDraw report (written in Velocity) that will produce output similar to the built in *UML Specification Report* in GitHub Flavored Markdown (GFM).

## Features

- Produces Documentation for Classes and Enumerations
- Converts mdel:// style hyperlinks into navigable bookmarks

The markdown report does not support HTML tags other than the aforementioned bookmark links. All markup will be stripped prior to conversion to Markdown.

## Prerequisites

- [Hilton Roscoe Report Extensions for MagicDraw VTL](https://github.com/HiltonRoscoe/MDReportExtensions)

## Using the report

In order to use this report with MagicDraw (v18.5 at the time of this writing), you must follow these steps:

1. Open the [repository site](https://github.com/HiltonRoscoe/UMLSpecificationReportMD) for `UMLSpecificationReportMD`.
2. Click the `report.txt` link, then click the `Raw` option.
3. Save the file to disk.
4. Open MagicDraw.
5. Open the project you want to report on.
6. Click Tools -> Report Wizard
7. Click New
8. Give the report a name. Click the ellipsis (...) next to `Template file` and navigate to the file you saved in step (3).
9. Click Create
10. Make sure the report is selected in the report wizard tree, then click next.
11. Click next again.
12. Under selected objects, move the packages you want to report on to the right, then click next.
13. Given the report file a name and click generate.

To rerun the report, you will only need to perform steps 10-13 again.
