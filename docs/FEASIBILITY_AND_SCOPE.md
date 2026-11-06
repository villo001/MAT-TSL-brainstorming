# Breadcrumb

[Home](/README.md) > [Docs](/docs/README.md) > [Feasibility & Scope]

---

# FEASIBILITY AND SCOPE — Mediterranean Atomic Tales: The Sunken Lands

**Stato:** Bozza critica.  
**Obiettivo:** Analisi critica dei rischi, piano di prototipazione graybox e definizione di cosa è **Out of Scope** per un progetto open source in Godot 4.7.2.

---

## 1. Rischi & Criticità

| Rischio | Descrizione | Mitigazione |
|---|---|---|
| **Scope creep** | Aggiunta di troppe fazioni/meccaniche oltre il core. | Mantenere 4 pilastri fissi; nuove idee finiscono in BRAINSTORMING_ARCHIVE.md. |
| **Plugin Godot 4.7.2** | Terrain3D, Phantom Camera, framework RPG potrebbero non essere compatibili. | Verificare subito; se incompatibili, semplificare terrain (mesh piatte) o usare plugin legacy. |
| **Single‑resource bottleneck** | Eliobionti/unica risorsa energia → gameplay ripetitivo. | Diversificare risorse: acqua, materiali crafting, influenza fazione. |
| **IP Safety** | Rischio involontario di usare termini protetti. | Checklist terminologia (già in HIGH_CONCEPT.md/WORLD_AND_LORE.md). |
| **Prototipazione gameplay** | Servire mesi per costruire mondo 4×4 km. | MVP: mappa ridotta a 1×1 km con 2 fazioni + tutorial breve. |

---

## 2. Piano di Prototipazione Graybox

**Sprint 1 (2 settimane):**
- Mappa base 1×1 km: costa occidentale + piccola parte di deserto.
- Protagonista sintetico con movimento FPS base.
- Due banchi da lavoro (crafting base: biopannelli + biocelle).
- Fazione minima: Porto Corsini (sparsi 2 insediamenti).

**Sprint 2 (2 settimane):**
- Aggiunta sistema energia bioelettrica (carica/scarica al sole).
- Prima fazione nemica (Venezia milizie).
- Primo “objetivo secondario” (raccolta Eliobionti per energia).
- Bug‑test e bilanciamento difficoltà.

**Sprint 3 (2 settimane):**
- Mappa estesa a 2×2 km (arrivo a 4×4 km finale).
- Tutte e 8 le fazioni (solo “point of interest”, non logiche complete).
- Primo build giocabile (from spawn a obiettivo finale).

**Sprint 4 (2 settimane):**
- Integrazione GDD, bilanciamento finale.
- Documentazione FEASIBILITY_AND_SCOPE.md fissata.
- Decisioni “Out of Scope” ufficiali.

---

## 3. Out of Scope (escluso deliberatamente)

- Costruzione insediamenti da parte del player (come in Fallout 4).
- Sistema di guida/VATS-like.
- Mondo open‑world esteso oltre i 4×4 km.
- Modalità multiplayer o cooperativa.
- Sistema di guida veicoli completi.
- Monetizzazione o asset store (progetto CC0, open source).
- Integrazione di plugin a pagamento non presenti in repo.

---

## 4. Checklist Godot 4.7.2

- [ ] Engine versione 4.7.2 stabile o patch minore.
- [ ] Plugin terrain: verifica compatibilità (in caso negativo, usare MeshInstance + shader sabbia).
- [ ] Fisica character: CharacterBody3D + collisione semplice (no RAGDOLPH complesso).
- [ ] Audio: OpenAL integrato, effetti ambiente dune/vento.
- [ ] Illuminazione: GI baked per interni, outdoor con sky+sun directional.
- [ ] Build test: esport PC (Windows/macOS) e verifica prestazioni.

---
<small>Breadcrumb aggiunta in alto. File vivo: aggiornare al termine di ogni sprint.</small>