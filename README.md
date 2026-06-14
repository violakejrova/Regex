# Regulární výrazy – seminárka

Seminárka do předmětu *Teoretická informatika* zaměřená na regulární výrazy
v Pythonu a v Linuxu (grep).

 `regex.ipynb` – Jupyter notebook s Python kódem


## Co notebook dělá

### 1. Vyhledávání a nahrazování v textu
Hledá slova obsahující řetězec "klep" v básni Havran a nahradí je pomocí `re.sub`.

### 2. Validace e-mailu
Ověří, jestli e-mailová adresa odpovídá platnému formátu
(malá písmena, číslice, tečky, podtržítka + doména gmail.com nebo seznam.cz).

### 3. Třídění údajů ze souboru
Projde textový soubor a rozřadí řádky do kategorií: e-maily, telefonní čísla,
webové adresy a ostatní (nezařazené nebo chybně zapsané).

## grep (Linux)

Stejné úlohy řešené v terminálu pomocí příkazu `grep` na Ubuntu.
Rozdíl oproti Pythonu: grep vyžaduje escapování speciálních znaků zpětným lomítkem `\`,
nebo lze použít `grep -E`, kde to není potřeba.
