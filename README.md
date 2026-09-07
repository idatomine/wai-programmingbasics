# WAI — Programmering fra bunnen 🏠

Workshop-materiell for **Women in AI NTNU**: fra matte til kode, med et ekte boligdatasett.

Studentene jobber to og to gjennom seks bolker — fra Python-basics til gradient descent — og møter et rotete datasett med 2930 hus (Ames Housing).

## Filer

| Fil | Beskrivelse |
|-----|-------------|
| `opplaering_oppgaver.ipynb` | **Oppgavesett** — deles ut til studentene. Hull å fylle ut. |
| `AmesHousing.csv` | Datasettet (2930 hus × 82 kolonner, komma-separert). |

## Bolker

1. **Python basics** — variabler, datatyper, lister, løkker, funksjoner, dictionaries, NumPy (leilighetstall fra forelesningen)
2. **Bli kjent med dataene** — form, datatyper, snitt vs. median, histogram
3. **Finn feilene** — manglende verdier, umulige årstall, uteliggere, kolonner uten variasjon
4. **Korrelasjon** — hva henger sammen med prisen, og hva `.corr()` ikke ser
5. **Gradient descent** — hvorfor den eksploderer, og hvordan normalisering redder den
6. **Avslutning** — refleksjon før man slipper en modell løs på dataene

## Kjøre lokalt

Krever Python 3.10+.

```bash
pip install -r requirements.txt
jupyter lab opplaering_oppgaver.ipynb
```

Sørg for at `AmesHousing.csv` ligger i samme mappe som notebooken.

Bruker du VSCode i stedet? Installer «Python»- og «Jupyter»-utvidelsene, åpne `.ipynb`-fila og velg en kjerne (trenger `ipykernel` i miljøet).
