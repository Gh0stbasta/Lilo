# 🌊 Lilo Repository

Willkommen im Repository für Lilo!

## Teil 1: Einführung in Lilo

Lilo ist keine herkömmliche Programmiersprache, sondern eine strukturierte Methode, um einem KI-Assistenten durch eine Vorlage einen **Ablauf (Workflow)** für eine bestimmte Aufgabe oder Interaktion zu definieren. Anstatt klassischen Programmcode zu verwenden, nutzt Lilo eine Organisation in Abschnitte und Direktiven in natürlicher Sprache, um das Verhalten der KI zu steuern.

Wir haben uns für den Namen Lilo für unsere Workflow-Sprache entschieden, weil er kurz, einprägsam und klangvoll ist. Ähnlich wie ein sanfter Fluss steht Lilo für den reibungslosen und intuitiven Ablauf, den du mit unserer Methode zur Steuerung von KI-Workflows erreichen kannst. Lilo ist eingängig und einzigartig, genau wie unser Ansatz, komplexe Interaktionen auf einfache Weise zu definieren.

**Kernkonzepte von Lilo:**

1.  **Strukturierte Abschnitte:** Ein Lilo-Dokument gliedert sich in thematische Abschnitte (z.B. Initialisierung, Benutzereingabe, Ausgabe).

2.  **Direktiven in natürlicher Sprache:** Innerhalb dieser Abschnitte geben klare Anweisungen in natürlicher Sprache vor, was die KI tun soll. Dies beinhaltet sequenzielle Schritte, bedingte Verzweigungen (`Wenn... dann...`), und Anweisungen zur Interaktion mit dem Benutzer.

3.  **Implizite Zustandsverwaltung:** Durch die Abfolge der Abschnitte und die Speicherung von Benutzerinformationen (z.B. in einer Liste) kann ein einfacher Zustand innerhalb des Workflows verwaltet werden.

4.  **Workflow-Steuerung:** Der Ablauf der Interaktion wird durch die Anordnung der Abschnitte und die in ihnen enthaltenen Bedingungen gesteuert. Lilo ähnelt in seiner Konzeption einem Pseudocode, der einen Arbeitsablauf für die KI beschreibt.

## Teil 2: Beispiel – Einfache To-Do-Listen-Erstellung

Dieses Beispiel zeigt einen einfachen Lilo, der es einem Benutzer ermöglicht, eine To-Do-Liste zu erstellen, die am Ende als formatierte Liste ausgegeben wird.

---

# 📝 Lilo zur Erstellung einer einfachen To-Do-Liste

## ⚙️ Initialisierung

- Die KI begrüßt den Benutzer und erklärt, dass wir eine To-Do-Liste erstellen.
- Die KI fragt, ob der Benutzer ein Element hinzufügen möchte.

## ➕ Element hinzufügen?

- **Wenn** der Benutzer mit "ja" oder einer ähnlichen Zustimmung antwortet, gehe zu Abschnitt "✏️ Element eingeben".
- **Wenn** der Benutzer mit "nein" oder einer Ablehnung antwortet, gehe zu Abschnitt "💾 Liste ausgeben".

## ✏️ Element eingeben

- Die KI bittet den Benutzer, das To-Do-Element einzugeben.
- Die KI speichert das eingegebene Element zur Liste hinzu.
- Die KI fragt erneut, ob der Benutzer ein weiteres Element hinzufügen möchte (gehe zurück zu "➕ Element hinzufügen?").

## 💾 Liste ausgeben

- Die KI formatiert die gespeicherten Elemente als eine einfache Liste.
- Die KI gibt die formatierte Liste als "To-Do-Liste.txt" aus (simuliert die Dateiausgabe im Chat).
- Die KI bedankt sich beim Benutzer.

## 🔚 Abschluss

- Der Lilo-Code endet.

## Start

starte den Prozess

---
