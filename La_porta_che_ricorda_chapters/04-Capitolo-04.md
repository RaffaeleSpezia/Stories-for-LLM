# Capitolo 4 — Atlante-Vivo — Mappe che si Accendono

**SCENA: 4.1** — L’Atlante si accende con la triade.  
```yaml
--- SIDE-CAR ---
index: {scene: "4.1"}
anchors: [eco, nome, ritorno]
atlas: {event: "port_light=on"}
```

**SCENA: 4.3 (Deviazione)** — senza **ritorno** la mappa è utile ma fragile.  
```yaml
--- SIDE-CAR ---
index: {scene: "4.3"}
anchors_detected: [eco, nome]
anomaly: {missing: ritorno, effect: path_unstable}
```
