============================================================
VOCENTRA 1.0
KI-GESTÜTZTE TRANSKRIPTION, ÜBERSETZUNG UND DOKUMENTATION
============================================================

Technische Version: 1.0.0


1. WILLKOMMEN
-------------

Vocentra ist eine Windows-Anwendung zur Transkription, Übersetzung
und strukturierten Aufbereitung von Audio- und Videoinhalten.

Die Anwendung verbindet lokale Spracherkennung mit optionalen
KI-Diensten. Wiederkehrende Verarbeitungsschritte lassen sich in
Profilen speichern. Dadurch können vergleichbare Aufgaben mit
einheitlichen Einstellungen durchgeführt werden.

Typische Einsatzgebiete sind unter anderem:

- Vorlesungen, Seminare und Vorträge
- Besprechungen und Interviews
- Schulungs- und Informationsvideos
- Sprachaufzeichnungen
- fremdsprachige Audio- und Videoinhalte

Vocentra darf nur für Inhalte verwendet werden, deren Verarbeitung,
Transkription und Übersetzung rechtlich zulässig ist. Beachten Sie
insbesondere Urheberrechte, Persönlichkeitsrechte, Datenschutz-
vorschriften und gegebenenfalls erforderliche Einwilligungen.


2. LEISTUNGSUMFANG
------------------

Vocentra unterstützt insbesondere:

- Transkription von Audio- und Videodateien
- automatische oder vorgegebene Spracherkennung
- optionale Übersetzung in eine Zielsprache
- KI-gestützte Bereinigung und Aufbereitung von Transkripten
- Erstellung von Zusammenfassungen, Kernpunkten und Analysen
- Erzeugung strukturierter DOCX- und PDF-Berichte
- Speicherung wiederkehrender Einstellungen in Profilen
- Verwendung lokaler und cloudbasierter KI-Anbieter
- Fortsetzung geeigneter Verarbeitungsvorgänge
- grafische Bedienung und zusätzliche Kommandozeilenfunktionen

Der genaue Funktionsumfang hängt vom gewählten Profil, den
aktivierten Ausgaben und dem verwendeten KI-Anbieter ab.


3. SYSTEMVORAUSSETZUNGEN
------------------------

Erforderlich:

- Microsoft Windows 10 oder Windows 11
- 64-Bit-System
- ausreichend freier Speicherplatz für Programm, Modelle,
  temporäre Dateien und Ausgaben
- ausreichender Arbeitsspeicher für die gewählten Modelle

Für cloudbasierte KI-Dienste zusätzlich erforderlich:

- Internetverbindung
- gültiger API-Schlüssel des jeweiligen Anbieters
- ein beim Anbieter nutzbares Konto oder Abrechnungsmodell

Für lokale KI-Verarbeitung mit Ollama zusätzlich erforderlich:

- installierte und gestartete Ollama-Anwendung
- mindestens ein geeignetes lokales Modell
- ausreichender Arbeits- und gegebenenfalls Grafikspeicher

Die Eignung eines lokalen Modells hängt wesentlich von dessen Größe
und von der verfügbaren Hardware ab.


4. INSTALLATION
---------------

1. Starten Sie die Installationsdatei:

   Vocentra_1.0.0_Setup.exe

2. Folgen Sie den Anweisungen des Installationsassistenten.

3. Cloud-API-Schlüssel für Gemini oder Groq können während der
   Installation eingetragen werden. Dieser Schritt ist optional.

4. Der Installationsassistent prüft auf Wunsch die lokale
   Ollama-Umgebung und zeigt vorhandene Modelle an.

5. Starten Sie Vocentra nach Abschluss der Installation über das
   Startmenü oder die optional angelegte Desktop-Verknüpfung.

Vocentra wird standardmäßig im lokalen Programmbereich des
angemeldeten Windows-Benutzers installiert. Für die normale
Installation sind keine Administratorrechte erforderlich.


5. DER ERSTE START
------------------

Nach dem Start wählen Sie zunächst ein geeignetes Profil aus.
Ein Profil legt unter anderem fest:

- Einstellungen der Spracherkennung
- Sprache und Übersetzungsziel
- KI-Anbieter und KI-Modell
- Bereinigung und Analyse
- gewünschte Ausgabeformate
- Aufbau und Inhalt der Berichte

Anschließend:

1. Wählen Sie eine Audio- oder Videodatei aus.
2. Prüfen Sie das ausgewählte Profil.
3. Passen Sie bei Bedarf einzelne Einstellungen für den aktuellen
   Vorgang an.
4. Wählen Sie das Ausgabeverzeichnis.
5. Starten Sie die Verarbeitung.
6. Öffnen Sie nach Abschluss die erzeugten Ergebnisse.

Je nach Dateilänge, Hardware, Modell und KI-Anbieter kann die
Verarbeitung einige Zeit dauern.


6. UNTERSTÜTZTE EINGABEDATEIEN
------------------------------

Vocentra unterstützt in Version 1.0 insbesondere folgende
Dateiendungen:

- MP3
- WAV
- MP4
- M4A
- FLAC
- MOV
- AVI

Ob eine konkrete Datei erfolgreich verarbeitet werden kann, hängt
zusätzlich von ihrem tatsächlichen Audio- oder Videoformat und den
enthaltenen Codecs ab.


7. AUSGABEN UND BERICHTE
------------------------

Abhängig vom Profil kann Vocentra unter anderem folgende Ergebnisse
erzeugen:

- Rohtranskript
- bereinigtes Transkript
- segmentierte Transkriptionsdaten
- Übersetzung
- Zusammenfassung
- Kernpunkte
- Themen
- erkannte Entitäten
- Analyseergebnisse
- DOCX-Bericht
- PDF-Bericht
- technische Protokoll- und Statusdateien

Nicht jedes Profil erzeugt automatisch alle verfügbaren Ausgaben.


8. KI-ANBIETER
--------------

Vocentra unterstützt in Version 1.0 folgende KI-Anbieter:

OLLAMA

Ollama stellt lokale Sprachmodelle auf dem eigenen Computer bereit.
Die an Ollama übergebenen Inhalte werden lokal verarbeitet, sofern
Ollama und das verwendete Modell ausschließlich lokal betrieben
werden. Für größere Modelle ist entsprechend leistungsfähige
Hardware erforderlich.

GEMINI

Gemini ist ein cloudbasierter KI-Dienst von Google. Für die Nutzung
ist ein gültiger Gemini-API-Schlüssel erforderlich. Die für den
jeweiligen Verarbeitungsschritt benötigten Inhalte werden über das
Internet an den Anbieter übertragen.

GROQ

Groq stellt cloudbasierte Modellzugriffe über eine API bereit. Für
die Nutzung ist ein gültiger Groq-API-Schlüssel erforderlich. Die
für den jeweiligen Verarbeitungsschritt benötigten Inhalte werden
über das Internet an den Anbieter übertragen.

Verfügbarkeit, Modelle, Nutzungslimits, Preise und Bedingungen der
Cloud-Anbieter werden von den jeweiligen Anbietern festgelegt und
können sich unabhängig von Vocentra ändern.


9. PROFILE UND CONFIGURATION STUDIO
-----------------------------------

Mit dem Vocentra Configuration Studio können Profile erstellt,
dupliziert, geändert, aktiviert und zurückgesetzt werden.

Profile eignen sich besonders für wiederkehrende Aufgaben, zum
Beispiel:

- deutschsprachige Vorlesungen mit Zusammenfassung
- fremdsprachige Vorträge mit deutscher Übersetzung
- Besprechungen mit Kernpunkten und Themenübersicht
- ausführliche Berichte mit DOCX- und PDF-Ausgabe
- vollständig lokale Verarbeitung mit Ollama

Globale API-Schlüssel für Gemini und Groq werden ebenfalls im
Configuration Studio verwaltet. Ein API-Schlüssel gehört nicht zu
einem einzelnen Profil, sondern gilt für die jeweilige
Vocentra-Installation des Windows-Benutzers.

Änderungen an Profilen sollten vor einer neuen Verarbeitung
gespeichert werden.


10. DATENSCHUTZ UND VERTRAULICHKEIT
-----------------------------------

Bei lokaler Verarbeitung verbleiben die an lokale Komponenten
übergebenen Inhalte grundsätzlich auf dem verwendeten Computer.

Bei Verwendung eines cloudbasierten KI-Anbieters werden die für den
jeweiligen Verarbeitungsschritt erforderlichen Inhalte an diesen
Anbieter übertragen. Für die dortige Verarbeitung gelten die
Datenschutz-, Nutzungs- und Aufbewahrungsbedingungen des jeweiligen
Anbieters.

Verarbeiten Sie vertrauliche, personenbezogene oder anderweitig
sensible Inhalte nur, wenn dies zulässig ist und die gewählte
Verarbeitungsart den jeweiligen Anforderungen entspricht.

API-Schlüssel werden lokal für den angemeldeten Windows-Benutzer
gespeichert. Geben Sie diese Schlüssel nicht an Dritte weiter.
Behandeln Sie API-Schlüssel wie Zugangsdaten.


11. RECHTLICHE HINWEISE ZU AUFNAHMEN
------------------------------------

Die technische Möglichkeit zur Verarbeitung einer Aufnahme bedeutet
nicht automatisch, dass deren Nutzung rechtlich zulässig ist.

Vor der Transkription oder Übersetzung sollte insbesondere geprüft
werden:

- Darf die Aufnahme angefertigt und verarbeitet werden?
- Liegt eine erforderliche Zustimmung der Beteiligten vor?
- Dürfen Vorlesungs-, Seminar- oder Schulungsinhalte gespeichert,
  vervielfältigt oder weitergegeben werden?
- Enthält die Aufnahme personenbezogene oder vertrauliche Daten?
- Ist eine Übertragung an einen Cloud-Anbieter zulässig?

Für die rechtmäßige Nutzung der verarbeiteten Inhalte ist der
Anwender verantwortlich.


12. LIZENZIERUNG UND TESTPHASE
------------------------------

Vocentra ist kommerzielle Software.

Die Anwendung kann nach der Installation während eines
14-tägigen Testzeitraums ohne Lizenz genutzt werden.

Nach Ablauf des Testzeitraums ist für die weitere Nutzung
eine gültige Lizenz erforderlich.

Folgende Lizenzmodelle stehen zur Verfügung:

• Einzelplatz-Lizenz
  Nutzung auf einem Arbeitsplatz.

• Firmen-Lizenz (5 Arbeitsplätze)
  Nutzung auf bis zu fünf Arbeitsplätzen innerhalb eines
  Unternehmens oder einer Organisation.

Weitere Lizenzmodelle können künftig angeboten werden.
Aktuelle Informationen finden Sie auf der Vocentra-Website.


13. FEHLERBEHEBUNG
------------------

DIE VERARBEITUNG STARTET NICHT

- Prüfen Sie, ob die Eingabedatei erreichbar ist.
- Prüfen Sie das ausgewählte Profil.
- Prüfen Sie, ob ausreichend Speicherplatz vorhanden ist.
- Prüfen Sie bei Cloud-Anbietern den API-Schlüssel und die
  Internetverbindung.
- Prüfen Sie bei Ollama, ob der Dienst gestartet wurde und das
  ausgewählte Modell installiert ist.

EIN CLOUD-ANBIETER WIRD NICHT ANGEZEIGT

Ein Cloud-Anbieter steht in der Profilauswahl nur zur Verfügung,
wenn für ihn ein API-Schlüssel eingerichtet ist. Bereits vorhandene
Profile werden durch einen fehlenden Schlüssel nicht automatisch
verändert.

DAS GEWÜNSCHTE OLLAMA-MODELL FEHLT

Installieren Sie das Modell in Ollama und aktualisieren Sie
anschließend die Modellliste im Configuration Studio.

DIE VERARBEITUNG DAUERT SEHR LANGE

Die Dauer hängt von Dateilänge, Hardware, Whisper-Modell,
KI-Anbieter, Netzwerkgeschwindigkeit und Umfang der gewählten
Nachbearbeitung ab.


14. SUPPORT
-----------

Support und Kontakt:

IT-Beratung Scholz
Dipl.-Phys. Mathias Scholz

E-Mail:  it-beratung-scholz@t-online.de
Website: https://vocentra.carrd.co

Bitte geben Sie bei Supportanfragen möglichst folgende Informationen
an:

- Vocentra-Version
- Windows-Version
- verwendetes Profil
- verwendeter KI-Anbieter und Modellname
- genaue Fehlermeldung
- Beschreibung der letzten Arbeitsschritte

Übermitteln Sie keine API-Schlüssel und keine vertraulichen
Originalinhalte, sofern dies nicht ausdrücklich vereinbart und
erforderlich ist.


15. COPYRIGHT
-------------

Copyright 2026 IT-Beratung Scholz
Dipl.-Phys. Mathias Scholz

Alle Rechte vorbehalten.

Vocentra und die zugehörigen Programmdateien sind urheberrechtlich
geschützt. Das Kopieren, Verändern, Dekompilieren, Weiterverbreiten,
Vermieten, Unterlizenzieren oder anderweitige Verwerten ist nur
zulässig, soweit dies gesetzlich erlaubt oder durch eine
ausdrückliche Lizenz gestattet ist.

Bezeichnungen, Dienste und Marken Dritter sind Eigentum der
jeweiligen Rechteinhaber.


============================================================
ENDE DER README
============================================================
