# LLM Phishing Email Analysis

Dieses Projekt verwendet mehrere Large Language Models (LLMs) zur Analyse und Identifikation von Phishing-E-Mails. Ziel ist es, die Leistungsfähigkeit verschiedener Modelle zu bewerten und deren Fähigkeit zur Erkennung von Phishing-Versuchen zu vergleichen. 

## Verwendete LLMs

- **GPT-4** OpenAI
- **Gemini 1.5 Pro** Google
- **LLAMA3.1 405b** Meta
- **Claude 3.5 Sonnet** Anthropic

## Projektidee

Die Idee hinter diesem Projekt ist es, die Effizienz und Genauigkeit moderner LLMs bei der Erkennung von Phishing-E-Mails zu testen. Phishing-E-Mails sind eine häufige Bedrohung, und die Fähigkeit, solche E-Mails automatisch zu erkennen, kann erheblich zur Sicherheit im digitalen Kommunikationsbereich beitragen. Die Modelle sollen bewerten, ob eine E-Mail ein Phishing-Versuch ist, eine Wahrscheinlichkeitsbewertung abgeben und die Merkmale erläutern, die zur Entscheidung geführt haben.

## Projektstruktur

- **llm_test.ipynb**: Ein Jupyter Notebook, das die Schritte zur Analyse von E-Mails mit verschiedenen LLMs zeigt. Das Notebook lädt eine Datei mit Test-E-Mails, führt die Analyse durch und speichert die Ergebnisse.
- **test_emails.csv**: Eine Beispieldatei mit E-Mails, die analysiert werden sollen. Diese Datei wird im Notebook verwendet, um die Funktionalität der verschiedenen LLMs zu testen.

## Nutzung

1. **Vorbereitung**: Stellen Sie sicher, dass die notwendigen API-Schlüssel für die verwendeten LLMs (GPT-4, Gemini 1.5 Pro, LLAMA3 70b, Claude 3.5 Sonnet) verfügbar und als Umgebungsvariablen gesetzt sind.
2. **Notebook ausführen**: Öffnen Sie das Jupyter Notebook `llm_test.ipynb` und folgen Sie den Anweisungen im Notebook, um die Analyse der Phishing-E-Mails durchzuführen.
3. **Ergebnisse überprüfen**: Die Ergebnisse der Analyse werden im Notebook angezeigt und in einer neuen CSV-Datei gespeichert.

## Ziel des Projekts

Das Hauptziel dieses Projekts ist es, die Effektivität und Genauigkeit von LLMs bei der Erkennung von Phishing-E-Mails zu bewerten. Durch den Vergleich der Ergebnisse der verschiedenen Modelle kann eine fundierte Entscheidung darüber getroffen werden, welches Modell am besten für diese Aufgabe geeignet ist.
