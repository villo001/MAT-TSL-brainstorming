
# Vestiario

Hai detto:

In Godot ci sono asset gratuiti di vestiario post apocalittico in stile Fallout 4?

ChatGPT ha detto:

Sì - esistono asset gratuiti di vestiario post-apocalittico utilizzabili in Godot, ma non sono tantissimi e non sono "per Godot" in modo esclusivo. Devi importarli come GLTF/FBX/OBJ, cosa che Godot gestisce benissimo.

Qui sotto ti metto le migliori fonti + asset più adatti a un gioco stile Fallout 4, tutti con licenze free (CC0 / CC-BY / permissive).

## 1. OpenGameArt - Vestiario post apocalittico

[https://opengameart.org](https://opengameart.org)

È la fonte più ricca di asset gratuiti completamente free.

Cerca:

 "post apocalyptic clothing"
 "survivor"
 "wasteland"
 "armor"

Trovi:

Outfit da sopravvissuto
- giacche strappate
- pantaloni consumati
- stivali post-apo
- outfit modulari

Armature improvvisate
- protezioni in metallo
- piastre arrugginite
- giubbotti rinforzati artigianali

Outfit femminili/maschili
- in low poly e mid poly.

La qualità è variabile, ma è tutto gratuito.

## 2. Quaternius - Personaggi e outfit (CC0)

[https://quaternius.com](https://quaternius.com)

Non ha pack solo di vestiti, ma offre:

Pack "Survival" / "Post Apocalyptic Humans"

Contenenti:

- personaggi sopravvissuti
- outfit modulari
- accessori (zaini, maschere, gilet, cinture)
- molte texture già grunge/post-apo

Questi pack sono CC0, perfetti per il prototipo.

## 3. Kenney - Outfit low poly

[https://kenney.nl/assets](https://kenney.nl/assets)

Non ha veri vestiti "Fallout-like", ma ha:

- bandoliere
- cinture
- accessori
- backpack
- guanti, cappelli

Ottimi per un look post-apo leggero.

## 4. Mixamo - Modelli umani + vestiti (gratis)

[https://www.mixamo.com](https://www.mixamo.com)

Molti personaggi hanno outfit post-nucleare / military / survivor.

Puoi:

- scaricare come FBX
- togliere l’animazione
- estrarre vestiti dal modello
- re-riggare in Godot con Skeleton3D

Asset di tipo:

- giacche tattiche
- pantaloni cargo
- armature improvvisate
- maschere antigas
- outfit survival

## 5. Sketchfab - Filtra per CC0 / free

[https://sketchfab.com](https://sketchfab.com)

Scrivi:

- "post apocalyptic outfit free"
- "survivor clothing cc0"
- "wasteland armor"

Trovi:

- Outfits completi di alta qualità, spesso modulari.
- Protezioni artigianali (placche di metallo, tire armor, shoulder pads)
- Maschere e respiratori

perfetti per un gioco stile Fallout.

Molti modelli sono CC0 o CC-BY.

## 6. Poly Pizza - Outfit low poly

[https://poly.pizza](https://poly.pizza)

Non ha molti vestiti completi, ma:

- cappotti strappati
- outfit da sopravvissuto
- armature improvvisate
- caschi e maschere

E tutto in formato glTF.

## 7. BlenderKit (molte risorse gratis)

[https://www.blenderkit.com](https://www.blenderkit.com)

Filtra per:

    free models
    clothing
    post-apocalyptic

Trovi:

- giacche consumate
- pantaloni distrutti
- protezioni improvvisate
- elmetti, caschi, respiratori

Molto utile se usi Blender come intermediario.

### Pack specifici consigliati (tutti gratuiti)

1. "Post-Apocalyptic Survivor Character Set" (Outfit modulari + look stile Wasteland)

2. "Survivor Clothes Pack (CC0)" (Quaternius - texture grunge, modulari)

3. "Wasteland Armor Kitbash CC0" (Sketchfab - piastre metalliche, shoulder pads, knee pads)

4. "Gas Mask Pack - Free" (Sketchfab/OGA - perfetto per ambientazione radioattiva)

5. "Scavenger/raider outfit pack" (Su OpenGameArt - molto simile a "raider gear" di Fallout.


# Nota sulla modularità

Fallout 4 usa:

- vestiti interi
- parti modulari (torso, braccia, gambe)
- accessori (maschere, cappelli, zaini)

Puoi replicarlo così:

- usa Blender per separare mesh in "torso / legs / boots / armor / mask"
- gestisci i materiali in Godot via MeshInstance3D + skeleton
- assegna un "Equipment" script che sostituisce lo Slot del corpo

Se vuoi, posso fornirti:

- uno schema completo per un sistema di armature modulare stile Fallout 4
- uno script ready-made per equipaggiamento in Godot 4
- una lista curata con link diretti ai migliori asset di vestiario

Vuoi la lista con link?

