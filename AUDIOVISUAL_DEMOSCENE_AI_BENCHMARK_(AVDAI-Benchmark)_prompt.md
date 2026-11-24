# AUDIOVISUAL DEMOSCENE AI BENCHMARK v1.0

## 1. Aufgabenstellung und Zielsetzung

Entwickle eigenständig eine vollständige, technisch anspruchsvolle und künstlerisch außergewöhnliche audiovisuelle Demoscene-Produktion, die unmittelbar in einem modernen Webbrowser ausgeführt werden kann.

Orientiere dich am künstlerischen und technischen Anspruch hochwertiger Produktionen der klassischen Amiga- und modernen PC-Demoscene, beispielsweise von Future Crew, Farbrausch, The Black Lotus, ASD, CNCD, Fairlight oder vergleichbaren Demogruppen.

Das Ergebnis soll keine gewöhnliche Shader-Demonstration, kein Musikvisualizer, keine Präsentation einzelner 3D-Objekte und keine lose Aneinanderreihung von Effekten sein. Es soll ein zusammenhängendes, eigenständiges audiovisuelles Kunstwerk mit überraschenden Wendungen, komplexen geometrischen Transformationen, beeindruckender Kameraführung, hochwertiger elektronischer Musik und einem außergewöhnlichen Finale entstehen.

Versuche, den Betrachter emotional, visuell und akustisch zu überraschen und nachhaltig zu beeindrucken.

Diese Aufgabe dient zugleich als Benchmark zur Bewertung deiner technischen, mathematischen, musikalischen und künstlerischen Fähigkeiten.

## 2. Verbindliches Ausgabeformat

- Liefere eine vollständig lauffähige ZIP-Datei.
- Die ZIP-Datei darf ausschließlich eine einzige HTML-Datei enthalten.
- Sämtlicher HTML-, CSS-, JavaScript- und WGSL-Code muss in dieser Datei enthalten sein.
- Sämtliche Musik, Soundeffekte, Texturen, Modelle und sonstigen benötigten Ressourcen müssen innerhalb dieser Datei erzeugt oder eingebettet werden.
- Keine externen Bibliotheken, CDNs, APIs, Schriftarten oder sonstigen Online-Abhängigkeiten.
- Keine nachträglichen Downloads.
- Keine Installation zusätzlicher Software.
- Kein lokaler Webserver als reguläre Voraussetzung.
- Die Demo muss nach dem Entpacken durch direktes Öffnen der HTML-Datei in einem kompatiblen Browser gestartet werden können.
- Liefere das vollständige Endprodukt, keine Machbarkeitsstudie, keinen Prototyp, keinen Pseudocode und keine unvollständigen Codefragmente.
- Falls deine Ausführungsumgebung keine Dateierstellung unterstützt, liefere ersatzweise den vollständigen HTML-Quellcode ohne Kürzungen.

## 3. Technologische Anforderungen

Verwende ausschließlich WebGPU als Grafik-API und WGSL für die GPU-Shader.

WebGL, WebGL2, Canvas-2D-Rendering als Ersatz für die eigentliche Grafikengine sowie externe 3D-Engines sind nicht zulässig.

Für die Audiowiedergabe und Klangerzeugung darf insbesondere die Web Audio API verwendet werden.

Nutze geeignete moderne Rendering-Techniken, darunter nach Möglichkeit:

- Raymarching
- Signed Distance Fields (SDF)
- Compute Shader
- GPU-Partikelsysteme
- Instancing
- Prozedurale Geometrie
- Volumetrisches Rendering
- Prozedurale Texturgenerierung
- Physikalisch inspirierte Lichtberechnung
- Postprocessing
- Multipass-Rendering
- GPU-basierte Simulationen
- Effiziente Speicher- und Ressourcenverwaltung

Die Auswahl und Kombination der Technologien liegt in deiner Verantwortung. Verwende sie nicht ausschließlich als Selbstzweck, sondern zur Erzielung eines außergewöhnlichen visuellen Gesamtergebnisses.

## 4. Zielhardware und Kompatibilität

Optimiere die Produktion für folgende Referenzhardware:

- NVIDIA GeForce RTX 4060 Ti mit 16 GB VRAM
- Intel Core i5-3570K
- 32 GB Arbeitsspeicher
- Windows 10 Pro 22H2
- Aktuelle WebGPU-fähige Desktopbrowser
- Firefox, Chrome und Edge, sofern WebGPU auf der jeweiligen Plattform unterstützt wird
- Bildschirmauflösungen von 1920 × 1080 und 2560 × 1080 Pixeln

Die Demo soll unterschiedliche Seitenverhältnisse korrekt unterstützen, insbesondere 16:9 und 21:9.

Strebe eine flüssige Darstellung mit 60 FPS auf der Referenzhardware an. Die tatsächliche Bildrate muss von der gewählten Renderqualität und der jeweiligen Szene abhängig berücksichtigt werden.

Implementiere eine angemessene Qualitätssteuerung mit mindestens:

- 480p
- 720p
- 1080p
- 1440p
- Optional nativer Bildschirmauflösung
- Optional automatischer dynamischer Renderauflösung

Die interne Renderauflösung darf das Seitenverhältnis des Bildschirms nicht verzerren.

Vermeide unnötige CPU-Belastung, übermäßige Speicherallokationen pro Frame, unkontrollierte GPU-Ressourcenbelegung und langfristig anwachsenden Speicherverbrauch.

## 5. Dauer und dramaturgischer Aufbau

Die Gesamtdauer soll ungefähr fünf bis sechs Minuten betragen.

Entwickle eine durchgehende audiovisuelle Dramaturgie mit mindestens zwölf deutlich unterscheidbaren visuellen Entwicklungsphasen.

Die Produktion soll unter anderem folgende dramaturgische Eigenschaften besitzen:

- Atmosphärischer oder geheimnisvoller Beginn
- Langsame Entstehung erster Strukturen
- Kontinuierliche Entwicklung visueller und musikalischer Motive
- Mehrere musikalische und visuelle Steigerungen
- Überraschende Perspektivwechsel
- Dramatische Kontraste
- Ruhige, atmosphärische Zwischenpassagen
- Komplexe Transformationen
- Unerwartete Wendungen
- Mindestens einen ausgeprägten musikalischen Break
- Anschließenden kraftvollen Drop
- Ein außergewöhnliches, intensiv inszeniertes Finale

Vermeide es, sämtliche Szenen in gleich lange Abschnitte zu unterteilen. Die Dauer einzelner Szenen soll sich aus der Musik, der visuellen Entwicklung und der dramaturgischen Notwendigkeit ergeben.

Szenen dürfen sich überschneiden, miteinander verschmelzen und frühere visuelle Motive in veränderter Form wieder aufgreifen.

## 6. Magnonische Wellen als grundlegendes Motiv

Ein zentraler Bestandteil der Demo soll die künstlerische Interpretation magnonischer Wellen beziehungsweise Spinwellen sein.

Berücksichtige nach Möglichkeit:

- Spinwellenausbreitung
- Interferenz mehrerer Wellenquellen
- Konstruktive und destruktive Interferenz
- Phasenverschiebungen
- Resonanz
- Stehende Wellen
- Wellenpakete
- Dispersionsverhalten
- Frequenzabhängige Ausbreitung
- Nichtlineare Wechselwirkungen
- Wirbelstrukturen
- Magnetisierungsfelder

Als vereinfachte mathematische Grundlage kann beispielsweise folgende Spinwellendispersion verwendet werden:

?(k) = ?? + D · k²

Ergänze diese Grundlage nach eigenem Ermessen durch weitere mathematische oder physikalisch inspirierte Modelle.

Magnonische Wellen sollen nicht ausschließlich als zweidimensionale Wasserwellen interpretiert werden. Entwickle daraus dreidimensionale, organische, abstrakte, kosmische oder geometrische Erscheinungsformen.

Eine vollständige wissenschaftliche Simulation ist nicht erforderlich. Physikalisch inspirierte Visualisierungen dürfen künstlerisch abstrahiert werden.

Das magnonische Grundmotiv soll während der gesamten Produktion wiederholt aufgegriffen und weiterentwickelt werden.

## 7. Visuelle Effekte

Integriere eine möglichst vielfältige Auswahl komplexer visueller Effekte.

Folgende Effektfamilien müssen in erkennbarer und technisch substanzieller Form vorkommen:

### Geometrische Transformationen

- Kontinuierliche 3D-Morphs
- Topologische Veränderungen
- Verschmelzende und sich trennende Körper
- Organisch deformierte Oberflächen
- Geometrische Knoten
- Torusvariationen
- Helix- und Doppelhelixstrukturen
- Twister und rotierende Wirbel
- Fragmentierung und anschließende Rekonstruktion
- Wechsel zwischen festen Körpern, fluidartigen Strukturen und Partikeln
- Mathematisch komplexe oder mehrdimensional inspirierte Geometrie

### Kosmische und räumliche Effekte

- Wurmlöcher
- Mehrdimensionale Tunnel
- Schwarze Löcher
- Animierte Akkretionsscheiben
- Künstlerisch interpretierte Gravitationslinseneffekte
- Dynamische Nebel
- Kosmische Energiefelder
- Bewegliche Sternenfelder
- Räumliche Parallaxeneffekte
- Verzerrungen des umgebenden Raums
- Supernovaartige Erscheinungen
- Expandierende Schockwellen

### Fraktale und mathematische Welten

- Dreidimensionale Fraktale
- Mandelbulb-, Mandelbox- oder vergleichbare rekursive Strukturen
- Fraktale Landschaften
- Rekursive Architekturen
- Kaleidoskopische Transformationen
- Unendliche geometrische Wiederholungen
- Selbstähnliche Strukturen
- Übergänge zwischen mikro- und makroskopischen Größenordnungen

### Energetische und partikelbasierte Effekte

- GPU-Partikelströme
- Plasmaartige Strukturen
- Elektrische Entladungen
- Energetische Verbindungen zwischen Objekten
- Pulsierende Energieringe
- Magnetfeldlinien
- Atomar inspirierte Orbitalstrukturen
- Explodierende und kollabierende Geometrien
- Künstlerisch dargestellte atomare Explosionspilze mit animierten volumetrischen Wolken, Schockwellen und Rauchstrukturen

Die Explosionsdarstellungen dienen ausschließlich der visuellen Inszenierung.

### Experimentelle Effekte

Entwickle zusätzlich mindestens drei eigenständige Effekte, die nicht lediglich direkte Umsetzungen der vorgegebenen Beispiele darstellen.

Nutze deine eigenen mathematischen und künstlerischen Ideen.

Originalität ist ausdrücklich Bestandteil der Bewertung.

## 8. Morphing und Szenenübergänge

Dieser Bereich ist besonders wichtig.

Die Demo darf nicht lediglich unterschiedliche Objekte vor einem unveränderten Hintergrund anzeigen und zwischen ihnen umschalten.

Vermeide insbesondere:

- Einfache Crossfades als dominierende Übergangstechnik
- Radiale, blumenartige Überblendungsmasken
- Reine Farbwechsel als vermeintliche geometrische Transformation
- Plötzlich erscheinende neue Objekte ohne visuelle Verbindung zum vorherigen Effekt
- Wiederholte Schwarzblenden
- Statische, isolierte Objektpräsentationen
- Unmotivierte harte Schnitte

Entwickle stattdessen räumlich und geometrisch nachvollziehbare Transformationen.

Ein Objekt soll beispielsweise:

- Seine Oberfläche öffnen
- Sich verdrehen
- In kleinere Strukturen zerfallen
- Seine Topologie verändern
- Neue Öffnungen ausbilden
- Sich in einen Tunnel verwandeln
- Sich mit seiner Umgebung verbinden
- In eine neue Landschaft übergehen
- Andere Strukturen aus seinem Inneren hervorbringen
- Seine Fragmente zu einer völlig neuen Form zusammensetzen

Nutze geeignete Verfahren wie SDF-Interpolation, Smooth-Min-Operationen, Domain Warping, räumliche Deformationen, prozedurale Feldtransformationen und Partikel-Morphing.

Achte darauf, dass einfache SDF-Interpolation nicht zu unbeabsichtigtem Verschwinden von Geometrie, abruptem Volumenverlust oder visuell unmotivierten Zwischenformen führt.

Der Betrachter soll den Eindruck erhalten, dass sich eine zusammenhängende Welt kontinuierlich verändert.

Übergänge dürfen selbst zu vollständigen visuellen Höhepunkten werden.

## 9. Kameraführung

Die Kamera muss aktiv an der Dramaturgie beteiligt sein.

Vermeide eine überwiegend statische Kamera, die isolierte Objekte aus gleichbleibender Entfernung betrachtet.

Implementiere komplexe, fließende und abwechslungsreiche Kamerafahrten, beispielsweise:

- Orbitale Kamerabewegungen
- Extreme Nahaufnahmen
- Makroskopische Oberflächenüberflüge
- Flüge unmittelbar entlang komplexer Oberflächen
- Durchflüge durch geometrische Öffnungen
- Flüge durch sich verändernde Objekte
- Kamerafahrten innerhalb von Fraktalen
- Rasante Tunneldurchflüge
- Bewegungen durch Wurmlöcher
- Annäherung an schwarze Löcher
- Dynamische Perspektivwechsel
- Langsame, atmosphärische Kamerafahrten
- Beschleunigungen und Verzögerungen
- Wechsel zwischen mikroskopischen und kosmischen Größenordnungen
- Kontrollierte Kamerarotation
- Musikalisch motivierte Kamerabewegungen

Ein besonders erwünschter Effekt ist der Flug unmittelbar oberhalb einer strukturierten, sich kontinuierlich morphenden Oberfläche, gefolgt von einem Flug durch eine entstehende Öffnung, hinter der sich eine neue, unerwartete Welt offenbart.

Kamerabewegungen sollen räumlich nachvollziehbar sein.

Vermeide unbeabsichtigtes Clipping, abruptes Springen, unkontrolliertes Zittern, permanente Rotation und monotone Bewegungsmuster.

Gezielte Kameraverzerrungen, Perspektivbrüche und kontrollierte Erschütterungen sind als dramaturgische Effekte zulässig.

## 10. Hintergrund und räumliche Umgebung

Der Hintergrund darf keine dauerhaft statische Sternentapete sein.

Die gesamte sichtbare Welt soll sich entwickeln.

Implementiere unter anderem:

- Mehrschichtige dynamische Sternenfelder
- Echte oder überzeugend simulierte räumliche Parallaxe
- Bewegliche Nebelstrukturen
- Animierte Volumen
- Atmosphärische Farbverläufe
- Dynamische Lichtquellen
- Bewegliche Hintergrundgeometrie
- Räumliche Tiefenwirkung
- Durch den Raum fließende Partikel
- Wechselnde kosmische und abstrakte Umgebungen
- Musikalisch reagierende Umgebungsbeleuchtung

Der Hintergrund soll unabhängig von zentralen Objekten eigene Bewegungen besitzen und zugleich visuell mit diesen interagieren.

Nutze unterschiedliche visuelle Größenordnungen, Vordergrundelemente und Hintergrundelemente zur Erzeugung eines glaubwürdigen Raumgefühls.

Auch außerhalb des Bildzentrums soll es interessante visuelle Entwicklungen geben.

## 11. Materialien, Texturen und Oberflächendetails

Verwende hochwertige, abwechslungsreiche und möglichst prozedural erzeugte Materialien.

Berücksichtige:

- Prozedurale Bumpmaps
- Prozedurale Normalmaps oder analytisch perturbierte Oberflächennormalen
- Fraktalrauschen
- Domain-Warped Noise
- Voronoi-Strukturen
- Turbulenzfunktionen
- Kaskadierende psychedelische Texturen
- Flüssigmetallartige Materialien
- Glänzende, metallische Oberflächen
- Kristalline Strukturen
- Organische Oberflächen
- Plasmaartige Materialien
- Emissive Materialien
- Glas- und Brechungseffekte
- Irisierende Oberflächen
- Fresnel-Effekte
- Animierte Mikrostrukturen

Oberflächen sollen bei extremen Nahaufnahmen weiterhin interessant aussehen und zusätzliche Details offenbaren.

Texturen sollen sich im Laufe der Zeit verändern und mit der geometrischen Transformation interagieren.

Vermeide, sämtliche Objekte mit demselben Rauschmuster, derselben Farbpalette oder demselben Material zu versehen.

## 12. Beleuchtung und Postprocessing

Erzeuge eine visuell überzeugende Beleuchtung und einen hochwertigen filmischen Gesamteindruck.

Nutze geeignete Verfahren wie:

- Dynamische Lichtquellen
- Schatten
- Soft Shadows
- Ambient Occlusion
- Volumetrisches Licht
- God Rays
- Bloom
- Tonemapping
- HDR-inspirierte Lichtverarbeitung
- Emissive Oberflächen
- Tiefenabhängige Nebeleffekte
- Depth of Field
- Motion Blur
- Chromatische Aberration
- Lichtbrechung
- Spiegelungen
- Subsurface-Scattering-artige Effekte

Setze Postprocessing gezielt und situationsabhängig ein.

Vermeide permanentes übermäßiges Bloom, unleserliche Bildstrukturen, dauerhaft überbelichtete Szenen und monotone Neonfarben.

Wechsle bewusst zwischen unterschiedlichen Farbwelten, Kontrasten, Lichtstimmungen und Materialeigenschaften.

## 13. Musik – eigenständige hochwertige Komposition

Die Musik ist gleichwertiger Bestandteil der Produktion und darf nicht als nebensächliche Ergänzung behandelt werden.

Erzeuge einen vollständigen, eigenständigen elektronischen Soundtrack, der sich über die gesamte Laufzeit entwickelt.

Orientiere dich stilistisch an einer kreativen Verbindung aus:

- Klassischer Demoscene-Musik
- Psytrance
- Progressive Trance
- Elektronischer Filmmusik
- Synthwave
- Industrial Electronica
- Ambient
- Experimenteller elektronischer Musik

Die Auswahl und Gewichtung der Stilrichtungen liegt in deiner Verantwortung.

Ein Tempo im Bereich von ungefähr 130 bis 150 BPM ist erwünscht. Tempoänderungen sind zulässig, wenn sie dramaturgisch sinnvoll sind.

Die Musik soll mindestens folgende Eigenschaften besitzen:

- Druckvolle, qualitativ hochwertige Kickdrums
- Tiefer, sauberer Subbass
- Rhythmisch abwechslungsreiche Basslines
- Hochwertige Snares und Claps
- Unterschiedliche Hi-Hats
- Komplexere Percussion
- Melodische Hooklines
- Wiedererkennbare musikalische Leitmotive
- Arpeggios
- Mehrstimmige Harmonien
- Akkordprogressionen
- Atmosphärische Pads
- Mehrschichtige Synthesizer
- Unterschiedliche musikalische Abschnitte
- Variation von Rhythmus und Instrumentierung
- Breaks
- Build-ups
- Drops
- Drum-Fills
- Kontrapunktische oder harmonische Entwicklungen
- Ein eindrucksvolles musikalisches Finale

Vermeide billige, piepsende oder künstlich klingende Standardsamples, primitive Sinusmelodien und minutenlang unveränderte Vier-Takt-Schleifen.

Nutze nach Möglichkeit fortgeschrittene Syntheseverfahren:

- Subtraktive Synthese
- FM-Synthese
- Additive Synthese
- Wavetable-Synthese
- Layering
- Unison und Detuning
- ADSR-Hüllkurven
- Resonanzfilter
- Distortion und Saturation
- Stereo-Delay
- Reverb
- Chorus
- Sidechain-Kompression
- Dynamikbearbeitung

Erzeuge oder integriere hochwertige eigene Klangquellen.

Verwende keine urheberrechtlich geschützten Musikaufnahmen ohne entsprechende Berechtigung.

Die Musik soll auch unabhängig von der Grafik als interessante elektronische Komposition wahrgenommen werden können.

## 14. Audioqualität und Mixing

Lege besonderen Wert auf saubere Audioverarbeitung.

Erwünscht sind:

- Audioberechnung mit möglichst 44,1 oder 48 kHz beziehungsweise der tatsächlich verfügbaren AudioContext-Samplerate
- Ausgewogenes Frequenzspektrum
- Druckvolle, kontrollierte tiefe Frequenzen
- Verständliche mittlere Frequenzen
- Angenehme hohe Frequenzen
- Differenzierte Stereobühne
- Saubere Transienten
- Sinnvolle Dynamik
- Vermeidung digitaler Übersteuerung
- Vermeidung unbeabsichtigten Aliasings
- Keine hörbaren Klicks an Samplegrenzen
- Keine unbeabsichtigten Aussetzer
- Mastering mit geeigneter Dynamik- und Pegelkontrolle

Nutze geeignete Antialiasing-Verfahren für die Synthese, sofern technisch sinnvoll.

Vermeide, Lautheit mit Klangqualität zu verwechseln.

Der Soundtrack soll nicht ausschließlich aus unmittelbar pro Frame ausgelösten Oszillatoren bestehen. Verwende eine robuste, samplegenaue oder vorausschauend geplante Audioarchitektur.

Geeignete Ansätze sind beispielsweise vorgerenderte Audiosegmente, OfflineAudioContext, AudioWorklets oder ein präziser Audio-Scheduler.

Berücksichtige die Browserrestriktionen für den Audiostart und die verfügbaren Möglichkeiten innerhalb einer einzigen lokalen HTML-Datei.

## 15. Zusätzliche Soundeffekte

Integriere gezielt Soundeffekte, die unabhängig von der eigentlichen musikalischen Instrumentierung auftreten.

Beispiele:

- Tiefe Impacts
- Explosionsgeräusche
- Energetische Entladungen
- Räumliche Vorbeifluggeräusche
- Riser
- Reverse-Effekte
- Gravitationsartig verzerrte Klangstrukturen
- Partikelgeräusche
- Mechanische Transformationen
- Resonanzgeräusche
- Schockwellen
- Übergangseffekte
- Akustische Kollaps- und Expansionsereignisse

Soundeffekte sollen präzise mit relevanten visuellen Ereignissen synchronisiert sein und sich harmonisch in den Soundtrack einfügen.

Sie dürfen weder permanent im Vordergrund stehen noch die Musik unnötig überdecken.

## 16. Audiovisuelle Synchronisation

Die Verbindung von Musik und Grafik ist ein zentraler Bestandteil des Benchmarks.

Verwende die Audiotimeline als maßgebliche Zeitreferenz oder implementiere eine vergleichbar robuste Synchronisationsarchitektur.

Berücksichtige:

- Beat
- Takt
- Musikalische Phrasen
- Kickdrum-Impulse
- Snare-Akzente
- Bassfrequenzen
- Mittlere und hohe Frequenzbereiche
- Melodische Entwicklungen
- Musikalische Breaks
- Drops
- Dynamische Lautstärkeentwicklung
- Gezielte musikalische Ereignisse

Nutze beispielsweise spektrale Analyse, RMS-Werte, geglättete Frequenzbänder, musikalische Event-Timelines und explizite Beat- und Phrasenmarker.

Die visuelle Synchronisation darf sich nicht auf pulsierende Objektgrößen oder Helligkeitsänderungen bei jedem Bassschlag beschränken.

Musik und Soundeffekte sollen unterschiedliche visuelle Eigenschaften beeinflussen können:

- Geometrie
- Morphing
- Materialeigenschaften
- Farben
- Beleuchtung
- Partikelverhalten
- Kamerabewegungen
- Raumverzerrungen
- Wellenausbreitung
- Szenenübergänge
- Geschwindigkeit
- Texturentwicklung
- Komplexität der sichtbaren Strukturen

Auch größere musikalische Entwicklungen müssen sich in der visuellen Dramaturgie widerspiegeln.

Bei schwankender Bildrate darf die audiovisuelle Synchronisation nicht zunehmend auseinanderlaufen.

## 17. Das ultimative Finale

Entwickle ein eigenständiges Finale, das einen deutlich erkennbaren Höhepunkt der gesamten Produktion bildet.

Das Finale soll nicht lediglich einen vorherigen Effekt mit höherer Geschwindigkeit, stärkerem Bloom oder größerer Lautstärke wiederholen.

Führe stattdessen frühere visuelle und musikalische Motive in einer neuen, überraschenden Gesamtstruktur zusammen.

Erwünscht sind:

- Eine zunehmende Verdichtung musikalischer und visueller Motive
- Gleichzeitig interagierende Effektfamilien
- Ein unerwarteter geometrischer oder räumlicher Perspektivwechsel
- Eine außergewöhnliche finale Transformation
- Ein präzise inszenierter musikalischer Höhepunkt
- Eine überzeugende abschließende Auflösung

Der Betrachter soll den Eindruck erhalten, dass die gesamte vorherige Produktion auf diesen Moment hingearbeitet hat.

Nutze kreative Freiheit, um einen möglichst einzigartigen und wiedererkennbaren Abschluss zu schaffen.

## 18. Benutzeroberfläche und Bedienung

Implementiere einen minimalistischen Startbildschirm mit:

- Eigenständig gewähltem Titel der Produktion
- Start-Button
- Optionaler Auswahl der Renderqualität
- Verständlicher Anzeige relevanter Kompatibilitätsprobleme

Während der eigentlichen Demo dürfen standardmäßig keinerlei Benutzeroberflächenelemente sichtbar sein.

Insbesondere:

- Keine Szenenbezeichnungen
- Keine Zeitanzeige
- Keine FPS-Anzeige
- Keine Fortschrittsanzeige
- Keine permanenten Logos
- Keine Bedienelemente
- Kein HUD

Der gesamte Bildschirm soll ausschließlich dem audiovisuellen Werk dienen.

Implementiere folgende Tastatursteuerung:

F – Vollbildmodus umschalten

M – Musik und Soundeffekte stummschalten

Leertaste – Pause und Fortsetzen

R – Vollständiger Neustart

Q – Renderqualität wechseln

Pfeil links – Vorheriger Demopart

Pfeil rechts – Nächster Demopart

H – Optionales Diagnose-HUD ein- und ausblenden

Escape – Vollbildmodus verlassen beziehungsweise zum Startbildschirm zurückkehren, soweit browserseitig möglich

Der Mauszeiger soll während der Demo nach kurzer Inaktivität ausgeblendet werden.

Pausieren, Neustarten und Szenenwechsel müssen Musik und Grafik konsistent synchronisieren.

Der Ton darf erst nach einer geeigneten Benutzerinteraktion gestartet werden.

## 19. Technische Robustheit und Fehlerbehandlung

Die fertige Produktion muss technisch vollständig und ausführbar sein.

Achte besonders auf:

- Korrekte JavaScript-Syntax
- Korrekte WGSL-Syntax
- Vermeidung reservierter WGSL-Schlüsselwörter als Variablennamen
- Korrekte Typkonvertierungen
- Korrekte Vektor- und Matrixoperationen
- Korrekte Shader-Bindings
- Korrektes Uniform-Buffer-Alignment
- Korrekte Pipeline-Konfiguration
- Gültige GPU-Texturformate
- Korrekte Ressourceninitialisierung
- Robuste Behandlung von Fenstergrößenänderungen
- Korrekte Initialisierung des AudioContext
- Fehlerfreie Audio-Scheduler
- Stabile Szenenwechsel
- Vermeidung von NaN- und Infinity-Werten
- Numerisch stabile Raymarching-Verfahren
- Keine Endlosschleifen im Shader
- Keine unkontrollierten Ressourcenallokationen

Implementiere eine differenzierte Fehlerbehandlung für:

- Fehlende WebGPU-Unterstützung
- Fehlenden GPU-Adapter
- Fehlgeschlagene GPU-Geräteinitialisierung
- WGSL-Kompilierungsfehler
- Pipeline-Validierungsfehler
- GPU Device Lost
- Audioinitialisierungsfehler
- Fehler bei der Ressourcenverwaltung

Zeige bei Shaderfehlern nach Möglichkeit die tatsächlichen Compilerinformationen einschließlich Zeilennummern an.

Ein Shader-Kompilierungsfehler darf nicht fälschlicherweise als nicht verfügbare GPU bezeichnet werden.

Implementiere WebGPU-Error-Scopes, geeignete Kompilierungsdiagnosen und Fehlerbehandlung für asynchrone Initialisierungsvorgänge.

Berücksichtige bekannte WGSL-Einschränkungen und verwende keine GLSL-Syntax, die in WGSL ungültig ist.

## 20. Performance und Ressourcenmanagement

Die grafische Komplexität soll möglichst effizient auf der GPU umgesetzt werden.

Berücksichtige:

- Adaptive Raymarching-Schrittweiten
- Sinnvolle Begrenzung der Raymarching-Iterationen
- Bounding Volumes
- Frühzeitige Abbruchbedingungen
- Szenenabhängige Shader-Komplexität
- Wiederverwendung von GPU-Ressourcen
- Effiziente Partikelberechnung
- Qualitätsabhängige Renderparameter
- Reduzierte Auflösung für geeignete Postprocessing-Pässe
- Dynamische Auflösungsskalierung
- Begrenzten und nachvollziehbaren Speicherverbrauch

Die Demo darf auch bei langen Laufzeiten nicht zunehmend langsamer werden.

Vermeide unnötige Shader-Neukompilierungen während der Wiedergabe.

Vorbereitungszeiten beim Start sind zulässig, sofern sie technisch erforderlich und durch eine dezente Fortschrittsanzeige nachvollziehbar sind.

## 21. Künstlerische Eigenständigkeit

Du hast ausdrücklich kreative Freiheit hinsichtlich:

- Titel
- Künstlerischem Gesamtkonzept
- Farbgestaltung
- Musikalischer Identität
- Auswahl mathematischer Verfahren
- Dramaturgischer Reihenfolge
- Gestaltung der einzelnen Effekte
- Kamerachoreografie
- Komposition
- Übergängen
- Finale

Die vorgegebenen Effektfamilien definieren den technischen und künstlerischen Mindestumfang. Sie sollen nicht dazu führen, dass du lediglich eine Checkliste abarbeitest.

Entwickle eine eigene visuelle und musikalische Handschrift.

Versuche, mindestens einen Moment zu erschaffen, den der Betrachter in dieser Form nicht erwartet hätte.

Priorisiere künstlerische Kohärenz, Originalität, visuelle Tiefe und musikalische Qualität gegenüber der bloßen Anzahl implementierter Effekte.

Kopiere keine bestehende Demoscene-Produktion.

## 22. Eigenständige Qualitätskontrolle

Überprüfe vor der Auslieferung das vollständige Ergebnis so weit wie in deiner tatsächlichen Ausführungsumgebung möglich.

Führe nach Möglichkeit folgende Prüfungen durch:

1. JavaScript-Syntaxprüfung.
2. WGSL-Validierung sämtlicher Shader.
3. Prüfung der WebGPU-Pipelines.
4. Browserstarttest.
5. Prüfung der Audioinitialisierung.
6. Prüfung sämtlicher Demoparts.
7. Prüfung aller Szenenübergänge.
8. Prüfung der audiovisuellen Synchronisation.
9. Prüfung der Pause- und Neustartfunktion.
10. Prüfung der Szenensprungfunktion.
11. Prüfung der unterschiedlichen Renderauflösungen.
12. Prüfung der Seitenverhältnisse 16:9 und 21:9.
13. Prüfung auf dauerhaft anwachsenden Speicherverbrauch.
14. Prüfung auf JavaScript- und WebGPU-Konsolenfehler.
15. Prüfung des Offline-Betriebs.
16. Prüfung der ZIP-Integrität.
17. Prüfung, dass die ZIP-Datei ausschließlich die vollständige HTML-Datei enthält.

Falls du einzelne Prüfungen aufgrund technischer Einschränkungen nicht durchführen kannst, dokumentiere dies transparent.

Behaupte keine erfolgreiche Ausführung, Kompilierung, visuelle Prüfung, Audioprüfung oder Performance-Messung, wenn diese tatsächlich nicht stattgefunden hat.

Unterscheide klar zwischen implementierten, statisch geprüften und praktisch getesteten Funktionen.

## 23. Auslieferung

Liefere abschließend:

- Die vollständige ZIP-Datei mit genau einer HTML-Datei.
- Den Titel deiner Produktion.
- Die tatsächliche Gesamtlaufzeit.
- Eine kurze Beschreibung des künstlerischen Gesamtkonzepts.
- Eine knappe Übersicht der Demoparts und Effekte.
- Eine kurze Beschreibung des musikalischen Konzepts.
- Die tatsächlich durchgeführten technischen Prüfungen.
- Bekannte Einschränkungen.

Die ergänzenden Informationen sollen außerhalb der ZIP-Datei angegeben werden.

Das eigentliche audiovisuelle Werk ist das primäre Ergebnis.

Beginne unmittelbar mit der vollständigen Entwicklung und Auslieferung.

Stelle keine unnötigen Rückfragen. Triff fehlende künstlerische und technische Entscheidungen selbstständig.

Liefere keine bloße Beschreibung dessen, was du entwickeln würdest. Entwickle es tatsächlich.

Nutze deine verfügbaren Programmier-, Mathematik-, Grafik-, Audio- und Analysefähigkeiten möglichst umfassend.

Das Ziel ist nicht einfach eine funktionierende Demo, sondern eine technisch überzeugende, musikalisch hochwertige, überraschende und atemberaubende Demoscene-Produktion mit eigenständiger künstlerischer Identität.