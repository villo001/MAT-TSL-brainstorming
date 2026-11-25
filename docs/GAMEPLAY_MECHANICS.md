# Breadcrumb

[Home](../README.md) > [Docs](README.md) > [Gameplay Mechanics](GAMEPLAY_MECHANICS.md)

---

# GAMEPLAY MECHANICS — Mediterranean Atomic Tales: The Sunken Lands

**Ultimo aggiornamento:** 2026-11-25  
**Stato:** bozza

## Scopo del documento

Questo documento specifica i sistemi di gioco core: core loop, crafting, combattimento FPS, progressione del personaggio (classi sintetiche, perk), Player Home ed economia/risorse. È la guida tecnica per chi prototipa e implementa le meccaniche, e deve rimanere coerente con HIGH_CONCEPT e WORLD_AND_LORE.

---

## 1. Core Loop

1. **Esplora** il Deserto Adriatico (dune, rovine, micro‑ambienti).  
2. **Raccogli** risorse: plastica, alluminio, legno, viti, adesivo, ingranaggi, Eliobionti.  
3. **Crafta** al Player Home o nei banchi da lavoro: armi, moduli energia, equipaggiamento.  
4. **Gestisci** energia bioelettrica (biopannelli, bionuclei, biocelle) e approvvigionamento idrico.  
5. **Scegli** alleanze con fazioni locali (Venezia, Abbazia di Pomposa, Porto Garibaldi, Porto Corsini, Ravenna, Popolo del Deserto) o avamposti limitati.  
6. **Procedi nella storia**: l'obiettivo apparente è controllare la costa; dopo il "finto finale", scopri gradualmente che il protagonista è un sintetico Mk.3 e prendi la decisione finale (tornare a Bologna, allearsi con Ferrara, o rimanere neutro).

---

## 2. Sistema di Crafting

- **Materiali base:** plastica, alluminio, legno, viti, adesivo, ingranaggi (raccoglibili nell'ambiente).
- **Materiali speciali:** Eliobionti (microorganismi mutati → bioelettricità).
- **Output crafting:**
  - **Biopannelli** – generano energia esposti al sole; durata limitata, ricarica al sole.
  - **Bionuclei** – contenitori ceramici scaricabili; ricarica esponendoli al sole.
  - **Biocelle** – munizioni ad energia istantanea per armi.
  - **Armi modificate** – aggiunta di moduli bioelettrici a armi da fuoco corpo a corpo.
  - **Equipaggiamento** – tute di protezione, antitossine, contenitori acqua.

---

## 3. Combattimento (FPS)

- **Sistema:** Primo persona, simile a Fallout 4 ma senza VATS.
- **Armi:** Armi da fuoco (pistole, fucili), armi corpo a corpo (asce, machete), armi ad energia (pistole bioelettriche).
- **Pericolosità:** Il Deserto Adriatico è ostile: calore, fatica, mutanti tossici/mutageni.
- **Danno:** I sistemi bioelettrici hanno cariche limitate; quando scariche, l'arma diventa "a caricamento meccanico" fino a ricarica successiva.

---

## 4. Progressione del Personaggio

- **Classe sintetica:** All'inizio il protagonista non conosce la propria classe: viene scoperta gradualmente durante il gioco in base alle scelte e alle situazioni affrontate. Sono disponibili tre classi: Bioelettrica, Tossica, Mutageno. Ogni classe sblocca abilità specifiche.
- **Albero abilità:** Punti esperienza guadagnati da scelte narrative, raccolta risorse, completamento missioni fazione.
- **Perk esempio:**
  - *Carica Solare* – biopannelli ricaricano più velocemente.
  - *Resistenza Tossica* – riduzione danni da zone inquinate.
  - *Mutazione Controllata* – accesso a abilità mutageno (adattamento ambientale).

---

## 5. Player Home (senza insediamenti costruibili)

- **Posizione:** Rifugio fisso (es. rovina costiera, cave sotterranee).  
- **Funzioni:**
  - Salvataggio e checkpoint.
  - Conservazione risorse e equipaggiamento.
  - Accesso a banchi da lavoro.
  - Dialoghi con NPC di fazione.
- **Non buildable:** Il giocatore non può modificare la struttura, ma può scegliere quali upgrade acquistare (es. nuovo banco crafting, ampliamento magazzino).

---

## 6. Economia & Risorse

- **Moneta principale:** Energia bioelettrica (carica dei biopannelli/bionuclei).
- **Risorse secondarie:** Acqua (scarsa), Eliobionti (per crafting energetico), materiali da crafting.
- **Commercio:** Con le fazioni (Venezia, Porto Corsini, Ravenna, ecc.) per risorse scarse o chiave.
- **Ruolo di Bologna:** Bologna è un avamposto limitato nel terreno di gioco (un punto di partenza per la missione del protagonista). Non è una fazione giocabile completa come le altre, ma un luogo dove il protagonista può ricevere supporto o missioni legate alla sua identità di sintetico Mk.3.

---
<small>Breadcrumb aggiunta in alto. File vivo: espandere con dettagli bilanciamento, tipi di nemici, sistema VATS-alternativo.</small>