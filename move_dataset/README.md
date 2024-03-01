### Script per Moure Conjunts de Dades

**Nota:** No modifiqueu aquest document. Si cal realitzar modificacions, feu-ne una còpia. Per a qualsevol consulta sobre el codi, contacteu amb rdr-contacte@csuc.cat.

## Objectiu del Script

Aquest script facilita el moviment d'un conjunt de dades d'una instància a una altra instància.

## Descripció

El script mou un conjunt de dades a una instància diferent utilitzant el DOI, el token API i l'alias del dataverse de destinació proporcionats. Es comunica amb l'API de Dataverse per recuperar la informació del conjunt de dades i realitzar l'operació de moviment. En acabar, proporciona feedback sobre l'èxit o el fracàs de l'operació.

## Requeriments

Assegureu-vos que estan instal·lades les següents llibreries:
- pyDataverse
- requests

## Ús

1. **Valors d'Entrada:**
    - DOI: Introduïu el DOI del conjunt de dades.
    - Token: Proporcioneu el token API per a l'autenticació.
    - Alias: Especifiqueu l'alias del dataverse de destinació.

2. **Execució:**
    - Executeu el script després de proporcionar els valors d'entrada necessaris.
    - El script intentarà moure el conjunt de dades al dataverse especificat.
    - Mostrarà un missatge d'èxit o de fracàs segons el resultat de l'operació.

