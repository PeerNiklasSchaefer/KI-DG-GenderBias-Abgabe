# KI-DG-GenderBias

## Kurzfassung

Dieses Repository dokumentiert eine wissenschaftliche Studie zur Frage, ob aktuelle LLMs bei der automatisierten Bewertung von Bewerbungsunterlagen geschlechtsspezifische Tendenzen, einen sogenannten Gender-Bias, zeigen. Untersucht wurde der Einsatz von LLMs in einem personalbezogenen Entscheidungskontext, in dem zwei experimentelle Designs verwendet wurden: eine isolierte Bewertung einzelner Kandidat*innen sowie ein direkter Vergleich zwischen zwei ähnlich qualifizierten Profilen.

Die Studie kombiniert synthetisch erzeugte Kandidat*innen Beschreibungen mit standardisierten Stellenbeschreibungen und einheitlich aufgebauten Prompts. Dadurch wird der Einfluss nicht fachlicher Merkmale möglichst stark reduziert, damit geschlechtsspezifische Tendenzen besser sichtbar werden. Im zweiten Experiment wurden zusätzlich Positionseffekte, Namensvarianten und unterschiedliche Prompt-Varianten berücksichtigt, um systematische Verzerrungen robuster zu erfassen.

Die Ergebnisse deuten darauf hin, dass die untersuchten Modelle nicht neutral im engeren Sinn agieren, sondern je nach Experiment und Promptgestaltung leichte bis schwache Bias-Muster zeigen können. Besonders im direkten Vergleich der Kandidat*innen treten kleine, aber messbare Verschiebungen auf. Insgesamt sind die Effekte jedoch überwiegend gering und der praktische Kontext ist für die Interpretation entscheidend.

## Inhalt des Repositories

- `Code/`: Notebooks für Datenaufbereitung, Experimente und Auswertung
- `CV/` und `CV2/`: synthetische Bewerbungsprofile für beide Kandidat*innen-Gruppen
- `Stellenausschreibungen/`: standardisierte Stellenbeschreibungen
- `prompts/`: Prompt-Vorlagen für die Experimente
- `Results*/`: Ergebnisdateien, Zusammenfassungen und Visualisierungen
