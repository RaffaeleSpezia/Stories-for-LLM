# Capitolo 9 — Compito Reale — Il Canale delle Parole Quietate

**SCENA: 9.3** — Rotte A/B/C; scelta AMS.  
**SCENA: 9.4** — Apro di un dito dopo **eco**, **nome**, **ritorno**.  
**SCENA: 9.5** — Tacca quieta raggiunta.

```yaml
--- SIDE-CAR ---
compare_routes:
  decision: "A → (se serve B) → (se serve C)"
action: {AMS: true}
verification: {outcome: "tacca_quieta"}
```
