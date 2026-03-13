# Binary Subnet
## Conversione Binario Decimale: Regole, Tabella e 100 Esercizi con Soluzione

[Conversione Binario Decimale: Regole, Tabella e 100 Esercizi con Soluzione](https://salvatorecapolupo.github.io/binary-subnet)

Snippet HTML da inserire in `modulo_3.html` del corso *Sistemi e Reti*.
Aggiunge una sezione FAQ autonoma sulla conversione binario ↔ decimale,
con regole mnemoniche, trattazione della subnet mask e 100 esercizi interattivi.

## Contenuto

**Regola generale** — tabella posizioni/esponenti (2⁰…2⁷) con strategia
di conversione in entrambe le direzioni e 6 esempi guidati.

**Subnet mask: tre casi**
- Caso 1: ottetti fissi 255 e 0, nessun calcolo
- Caso 2: uni iniziali + zeri finali → formula `256 − 2ⁿ` con tabella completa
- Caso 3: bit misti → non valido come subnet mask, test di validità istantaneo

**100 esercizi interattivi** — 50 bin→dec + 50 dec→bin generati con seed fisso,
tutti verificati programmaticamente. La soluzione si rivela al click e si
nasconde al secondo click.

## Font

Tutta la sezione usa `Courier New` (monospace). Nessuna dipendenza esterna.

## Requisiti

Nessuno. HTML + CSS + JS vanilla inline, nessuna libreria.
