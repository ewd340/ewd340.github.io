---
title: LibreOffice tips
---

## Lookup

[LibreOffice calc lookup](https://www.libreofficehelp.com/lookup-references-libreoffice-calc/)

=INDEX(WhereToGetData, MATCH(CellWeWantToFind,WHEREToFindCellValue,0),WhichColumnTOReturn)

Example:

=INDEX($work.$A$3:$E$111, MATCH(A3,$work.$A$3:$A$111,0),5)
