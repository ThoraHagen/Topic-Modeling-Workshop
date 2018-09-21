## Inhaltliche Analyse von Plenarprotokollen des deutschen Bundestages durch Topic Modeling
Hier sind die im Workshop verwendeten Korpora zur Verfügung gestellt. Die Plenarprotokolle wurden von der [offiziellen Webseite des Deutschen Bundestages](https://www.bundestag.de/dokumente/protokolle/plenarprotokolle/plenarprotokolle) heruntergeladen und für den Workshop aufbereitet. Fehlerhafte Dateien (z.B. wg. fehlendem Sitzungsdatum) wurden nicht in die Korpora aufgenommen.

Hier befinden sich außerdem die Links zum [TopicsExplorer](https://github.com/DARIAH-DE/TopicsExplorer) und zu der dazugehörigen [Topic Modeling Bibliothek](https://github.com/DARIAH-DE/Topics).

#### Wodurch unterscheiden sich die Korpora von den originalen Plenarprotokollen?
1. Korpus 'Zeit'
   - die Dateinamen wurden durch das Sitzungsdatum ersetzt
   - die vorangehenden Tagesordnungspunkte wurden entfernt
   - die Anlagen wurden entfernt
  
 2. Korpus 'Parteien' (ausgehend von 1.)
    - Beifälle und Einwürfe wurden entfernt
    - alle Redner derselben Parteien wurden unter einem jeweiligen Partei-Dokument zusammengefasst
   
 3. Korpus 'Parteien_Segmente' (ausgehend von 2.)
    - Rednernamen wurden aus den Partei-Dokumenten entfernt (bis auf den ersten Redner)
    - alle Partei-Dokumente wurden auf Segmente von maximal 300000 Tokens verteilt
    - wegen der Segmentierung sind hier Satzzeichen und Umbrüche nicht mehr enthalten
