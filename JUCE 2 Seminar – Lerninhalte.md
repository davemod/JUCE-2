# JUCE 2 Seminar – Lerninhalte

## Einheit 1: Git Intro Again
- **Wiederholung Git Basics**
  - Git-Submodule
  - Branching, Commits, und Git-Workflows

---

## Einheit 2: Alle Parameter, AudioProcessorValueTreeState & UI-Anbindung
- **AudioProcessorValueTreeState** 
- **Parameter anlegen:**
  - Float, Bool, Choice
  - UI-Elemente anbinden (Slider, Button, ComboBox)

---

## Einheit 3: UI-Anpassungen
- **Slider, ComboBox, Button anpassen**
- **LookAndFeel** 
- **Filmstrips für dynamische UI**

---

## Einheit 4: State Management & UndoManager
- **State speichern und laden** mit `getStateInformation()` und `setStateInformation()`
- **UndoManager** für Rückgängig-Funktionalität
- **Preset Menu** für ein eigenes Preset Management

---

## Einheit 5: JUCE::DSP Intro & Delay
- **Digitale Signalverarbeitung (DSP)**
  - Delay-Implementierung
  - Grundlagen der DSP-Architektur in JUCE

---

## Einheit 6: BPM-Sync
- **BPM Synchronisation** für LFO und andere Effekte
- **Host BPM und PositionInfo nutzen**

---

## Einheit 7: Gain & Waveshaper
- **Gainsteuerung und Waveshaping** in JUCE
- **Signalbearbeitung und Modulation**

---

## Einheit 8: Metering
- **RMS/Peak Meter** für Lautstärkekontrolle
- **Meter-UI-Design und Implementierung**

---

## Einheit 9,10,11: Eigenarbeit / Exkurse
- **Eigenständige Projektarbeit** und Umsetzung der erlernten Inhalte
- **Testen mit PluginVal** um Crashs und andere mögliche Fehler zu finden

---

## Einheit 12: Vorstellung
- **Präsentation der Abschlussprojekte**
- **Feedback & Code-Reviews**

---

### Abschlussprojekt
- **Eigenes Plugin entwickeln**, ein sehr simples Plugin um das Verständnis der erlernten Inhalte zu demonstrieren. Das Plugin soll maximal drei Parameter haben. Alle Parameter sollen der DAW zur Verfügung stehen, ein Undo Management soll implementiert sein sowie eigene Presets in der Dateistruktur des OS (Finder, Explorer) gespeichert und geladen werden können. Es soll mindestens ein Modul aus juce::dsp verwendet oder ein eigenes erstellt werden. Es soll ein Meter integriert werden und – falls zum Plugin Type passend – auf die aktuelle BPM der DAW zurückgegriffen werden.