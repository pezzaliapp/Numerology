# Numerology (Pitagorico) — Single-folder Web App

App web in **HTML/CSS/JS** (nessuna dipendenza esterna) per calcolare rapidamente:
- Percorso di Vita (Life Path)
- Numero di Espressione (nome completo)
- Numero dell’Anima (vocali)
- Numero di Personalità (consonanti)
- Matrice pitagorica 3×3 dalla data di nascita
- Anno personale per un anno target

## Come usare
Apri `index.html` in qualsiasi browser moderno (desktop o smartphone). Tutto gira **in locale**.

## Scelte di calcolo
- **Mappatura lettere → numeri**: metodo pitagorico ciclico (A=1 … I=9; J=1 … R=9; S=1 … Z=8).
- **Riduzione**: somma delle cifre fino a un singolo numero; se l’opzione è attiva, i **numeri maestri 11/22/33** vengono preservati dove ha senso (nome, percorso, ecc.).
- **Anno personale**: somma ridotta di (giorno + mese + anno target).

## Struttura repository
Tutti i file sono nella cartella principale (niente sottocartelle):
- `index.html` — UI + logica JS inline (una sola pagina)
- `README.md`

## Licenza
MIT
