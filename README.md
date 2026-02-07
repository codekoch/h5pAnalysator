# <a href="https://codekoch.github.io/h5pAnalysator/h5p_Analysator.html">h5p_Analysator (Inhalts-Viewer)</a>

Der **h5p_Analysator** ist ein browserbasiertes Tool für Lehrer und Bildungsanbieter, um H5P-Dateien (Interaktive Inhalte) schnell zu analysieren, Lösungen einzusehen und die Inhalte für analoge Arbeitsblätter weiterzuverwenden.

Das Programm läuft vollständig lokal im Webbrowser (kein Server-Upload notwendig) und eignet sich daher hervorragend für den datenschutzkonformen Einsatz.

## 🚀 Funktionen

- **Unterstützte H5P-Typen**:
  - Drag & Drop (mit visueller Lösungsvorschau)
  - Multiple Choice / Single Choice Sets
  - Wahr/Falsch
  - Lückentexte (Blanks)
- **Deep Search**: Durchsucht die H5P-Dateistruktur rekursiv nach versteckten Texten und Bildern.
- **Lösungsanzeige**: Zeigt sofort die korrekten Antworten und Zuordnungen an.
- **Mediengalerie**: Extrahiert und zeigt alle in der H5P-Datei enthaltenen Bilder in einer Übersicht.
- **Druck-Optimierung**: Bereitet die Inhalte so auf, dass sie direkt als PDF gespeichert oder gedruckt werden können.

## 🛠️ Verwendung

1. Öffnen Sie die Datei `h5p_Analysator.html` in einem modernen Webbrowser (Chrome, Edge, Firefox).
2. Ziehen Sie eine `.h5p` Datei (oder ein umbenanntes `.zip` Archiv) in das Upload-Feld.
3. Das Tool analysiert den Inhalt automatisch und zeigt alle Fragen und Lösungen an.
4. Der Druck-Dialog (PDF speichern) öffnet sich oft automatisch, oder kann manuell oben rechts ausgelöst werden.

## 🤖 Arbeitsblätter mit KI erstellen

Eine mächtige Funktion dieses Tools ist die Vorbereitung von Inhalten für KI-Prompts. Da der h5p_Analysator die Strukturen der Aufgaben (Fragen, Antworten, Lücken, Zuordnungen) im Klartext extrahiert, können diese direkt genutzt werden, um gedruckte Arbeitsblätter zu erstellen.

### Workflow:
1. **Inhalt kopieren**: Markieren Sie den analysierten Text der H5P-Datei auf der Webseite und kopieren Sie ihn.
2. **KI Prompt nutzen**: Fügen Sie den Inhalt in einen KI-Chatbot (z.B. ChatGPT, Claude, Gemini) zusammen mit folgendem Prompt ein:

> "Erstelle basierend auf den Inhalten des pdf-Dokumentes im Anhang, ein strukturiertes Arbeitsblatt für Schüler. 
> Das pdf-Dokument zeigt einen Quiz im h5p Format. Erstelle jeweils eine Information zu den einzelnen Themen inkl. Übungsaufgaben, die auf den Quiz vorbereiten, aber nicht direkt die einzelnen Lösungen verraten.
> Füge am Ende des Dokumentes die Lösungen der gestellten Übungsaufgaben an.  

Durch diesen Schritt lassen sich digitale Übungen in Sekunden in klassische Papier-Arbeitsblätter oder Lernzielkontrollen transformieren, die exakt auf die digitalen Inhalte vorbereiten.

## 📝 Lizenz

Dieses Tool ist Open Source und zur freien Verwendung im Bildungsbereich gedacht.
