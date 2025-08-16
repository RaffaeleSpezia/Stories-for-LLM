# Capitolo 2 — Duplicate–Mutate–Compare (Specchio-Paziente)

**SCENA: 2.A (Duplicate)** — canone integro  
**OGGETTI:** [Specchio-Paziente, Passo-Due]  
**STATO:** {tensione: tenera → curiosa}

**eco**, **nome**, **ritorno**: il ritmo regge.

```yaml
--- SIDE-CAR ---
index: {scene: "2.A"}
anchors: [eco, nome, ritorno]
checksum: "ok"
```

**SCENA: 2.B (Mutate)** — deviazione controllata  
Manca **ritorno** → instabilità.

```yaml
--- SIDE-CAR ---
index: {scene: "2.B"}
anchors_detected: [eco, nome]
anomaly: {missing: ritorno}
checksum: "incomplete"
```

**SCENA: 2.C (Compare)** — preferire A.

```yaml
--- SIDE-CAR ---
compare:
  A: {anchors: [eco, nome, ritorno], effect: "abitabile"}
  B: {anchors: [eco, nome], effect: "freddo"}
verdict: "A"
```
