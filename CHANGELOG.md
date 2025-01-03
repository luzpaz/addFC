# addFC - additional tools for FreeCAD

## Release notes

#### 2024.05.12 (**0.1.0**):
* Initial release.

#### 2024.05.17 (**0.1.1**):
* Fixed: AddFCProperties - selection.
* Fixed: Explode - animation.

#### 2024.05.22 (**0.2.0**):
* Refactoring.
* Added: Explode - export animation to video file.
* Added: New example - belt roller support assembly.
* A new optional dependency: FFmpeg.

#### 2024.05.25 (**0.3.0**):
* Fixes.
* BOM (Specification): Export settings.
* BOM (Specification): Export to spreadsheet.
* BOM (Specification): Export to CSV.

#### 2024.06.02 (**0.3.1**):
* Fixes.

#### 2024.06.29 (**0.4.2**):
* Minor changes.
* The "Code" property has been renamed to "Index".
* Added: Sheet metal settings: radius, k-factor calculation.
* Added: Sheet metal part settings: color and density.
* HotFix.

#### 2024.07.17 (**0.4.4**):
* Minor changes and fixes.
* Refactoring.
* Documentation on main functions is available in English and Russian.

#### 2024.08.02 (**0.6.1**):
* Updating standard properties (added: Code, Format, Note, Section).
* Preferences: Ability to change FreeCAD font.
* Specification: Automatic indexing of element positions.
* Specification: Updating enumerations properties in objects.
* Unified System for Design Documentation, USDD - Russia:
    + Possibility of exporting specifications according to the standard.
    + New function: Create a drawing based on a template.
    + Automatic filling of the template stamp.
    + Additional files added: [templates and font](/repo/add/stdRU)
    + Added a special example of work and design: stdRU.
* Updating documentation and fixes.
* Fixes.

#### 2024.08.04 (**0.6.3**):
* Fixes: explode, pipe, templates.
* Readme update.

#### 2024.08.25 (**0.7.0**):
* Documentation completed.
* Template updates (USDD - Russia).
* Various fixes and updates.

#### 2024.10.13 (**0.7.3**):
* Additions: processing and display in preferences.
* Changes to the preferences interface.
* Fixes: unfold and metal thickness.
* Improvement: OpenRecentFile.

#### 2024.10.19 (**0.7.4**):
* Fix unfold and auto indexing.

#### 2024.10.28 (**0.7.5**):
* Fixes: unfold and specification.

#### 2024.12.27 (**1.0.0**):
* The name for the property group is now standard ("Add") and unchangeable.
* The properties "Weight" and "Price" have been moved to the basic group.
* Added basic property "Node" to separate bill of materials.
* Added materials for automatic calculation of mass and cost of objects.
* Increased stability in batch processing of sheet metal parts.
* Added an experimental version of the library of elements and nodes.
* A standard library has been created as part of the workbench.
* Many other changes, fixes and improvements.
* Backward compatibility may be broken...
