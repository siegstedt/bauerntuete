# Bauerntuete: Data Exploration and Analysis

## Projektbeschreibung

Dieses Repository enthält eine umfassende Datenexploration und Analyse eines Online-Handels. Ziel des Projekts ist es, das Kaufverhalten der Kunden zu verstehen und darauf basierend datengetriebene Marketingstrategien zu entwickeln. Es werden verschiedene Techniken zur Datenexploration und -analyse vorgestellt, darunter Assoziationsregel-Mining und Clustering.

## Dateien im Repository

- **bauerntuete.csv**: Der ursprüngliche Datensatz mit Bestellungen und Kundendaten des Online-Gemüsehandels.
- **exploration.ipynb**: Das Jupyter Notebook, das den gesamten Explorations- und Analyseprozess dokumentiert. Enthält Code und Erklärungen zu den durchgeführten Analysen.
- **exploration.html**: Eine HTML-Version des Jupyter Notebooks für eine einfache Ansicht ohne Jupyter.
- **postcode_coordinates.json**: Eine JSON-Datei mit Postleitzahlen und deren entsprechenden Längen- und Breitengraden, die für die Kartenvisualisierung verwendet werden.
- **postcode_map.html**: Eine interaktive Karte, die die Versandpostleitzahlen auf einer Karte visualisiert.
- **requirements.txt**: Eine Liste der benötigten Python-Pakete und deren Versionen, die für die Ausführung des Notebooks erforderlich sind.

## Datenexploration und Analysen

### 1. Allgemeine Datenanalyse

In erster Instanz wurde der Datensatz erkundet und es wurden Chancen sowie Limitationen und Empfehlung für das weitere Datenmanagement abgeleitet.

### 2. Geografische Analyse

Die Versandpostleitzahlen wurden auf einer Karte visualisiert, um geografische Muster im Bestellverhalten zu erkennen. Diese Analyse kann helfen, regionale Marketingstrategien zu entwickeln und Lieferketten zu optimieren.

### 3. Assoziationsregel-Mining

Mit Hilfe des Assoziationsregel-Mining wurden häufig zusammen gekaufte Produkte identifiziert. Dies hilft dabei, Produktempfehlungen für Kunden zu generieren, die auf der Seite eines bestimmten Produkts sind.

### 4. Clustering

Durch die Anwendung der K-Means-Clustering-Methode wurden Kunden basierend auf ihrem Kaufverhalten in verschiedene Gruppen eingeteilt. Dies ermöglicht eine gezielte Marketingansprache und die Entwicklung von maßgeschneiderten Angeboten für verschiedene Kundengruppen.

## Verwendung

### Installation der Abhängigkeiten

Um die benötigten Python-Pakete zu installieren, führen Sie den folgenden Befehl aus:

```bash
pip install -r requirements.txt
```

### Ausführung des Notebooks

Öffnen Sie das Jupyter Notebook `exploration.ipynb` in Jupyter Notebook oder JupyterLab und führen Sie die Zellen aus, um die Datenexploration und Analyse nachzuvollziehen.

### Ansehen der HTML-Dateien

- **exploration.html**: Öffnen Sie diese Datei in einem Webbrowser, um die gesamte Datenexploration und Analyse ohne Jupyter anzusehen.
- **postcode_map.html**: Öffnen Sie diese Datei in einem Webbrowser, um die interaktive Karte der Versandpostleitzahlen zu sehen.

Viel Spaß bei der Datenexploration!
