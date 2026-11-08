# Data Science LNW I – Snippet-Sammlung

Oct 18, 2026 · @Charlie

Diese Sammlung ist das Nachschlagewerk für die Prüfung vom 9.11.2026. Open Book und Open Internet sind erlaubt, KI-Hilfsmittel nicht — dieses Dokument darfst du also nutzen.

Die Sammlung wächst mit dem Lernplan mit: Abschnitte ohne Inhalt werden in den kommenden Wochen gefüllt.

Offene Fragen und Antworten aus den Übungen: Q&A Backlog

## Dokumentation (Open Internet)

### Die URL-Muster

Wichtiger als jeder Einzellink: Mit diesen Mustern findest du **jede** Funktion in Sekunden, ohne zu suchen.

| Bibliothek | Muster |
| --- | --- |
| seaborn | `seaborn.pydata.org/generated/seaborn.<funktion>.html` |
| matplotlib (Achsen) | `matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.<funktion>.html` |
| matplotlib (pyplot) | `matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.<funktion>.html` |
| pandas | `pandas.pydata.org/docs/reference/api/pandas.<funktion>.html` bzw. `pandas.DataFrame.<methode>.html` |
| scikit-learn | `scikit-learn.org/stable/modules/generated/sklearn.<modul>.<Klasse>.html` |

### Kurs-Ressourcen (W1, Folie 4)

Vom Dozenten ausdrücklich als prüfungsrelevant genannt.

- [Python Tutorial (W3Schools)](https://www.w3schools.com/python/)
- [SQL Tutorial (W3Schools)](https://www.w3schools.com/sql/)
- [PostgreSQL Tutorial (W3Schools)](https://www.w3schools.com/postgresql/)

### pandas

- [API-Referenz](https://pandas.pydata.org/docs/reference/index.html) · [User Guide](https://pandas.pydata.org/docs/user_guide/index.html)
- [`read_csv`](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html) · [`merge`](https://pandas.pydata.org/docs/reference/api/pandas.merge.html) · [`concat`](https://pandas.pydata.org/docs/reference/api/pandas.concat.html)
- [`DataFrame.groupby`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.groupby.html) · [`DataFrame.describe`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.describe.html) · [`DataFrame.corr`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.corr.html)
- [`crosstab`](https://pandas.pydata.org/docs/reference/api/pandas.crosstab.html) · [`get_dummies`](https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html) · [`qcut`](https://pandas.pydata.org/docs/reference/api/pandas.qcut.html) · [`cut`](https://pandas.pydata.org/docs/reference/api/pandas.cut.html)
- [`to_numeric`](https://pandas.pydata.org/docs/reference/api/pandas.to_numeric.html) · [`to_datetime`](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html)

### seaborn

- [API-Übersicht](https://seaborn.pydata.org/api.html)
- [`histplot`](https://seaborn.pydata.org/generated/seaborn.histplot.html) · [`boxplot`](https://seaborn.pydata.org/generated/seaborn.boxplot.html) · [`violinplot`](https://seaborn.pydata.org/generated/seaborn.violinplot.html)
- [`countplot`](https://seaborn.pydata.org/generated/seaborn.countplot.html) · [`barplot`](https://seaborn.pydata.org/generated/seaborn.barplot.html)
- [`scatterplot`](https://seaborn.pydata.org/generated/seaborn.scatterplot.html) · [`pairplot`](https://seaborn.pydata.org/generated/seaborn.pairplot.html) · [`heatmap`](https://seaborn.pydata.org/generated/seaborn.heatmap.html)

### matplotlib

- [API-Übersicht](https://matplotlib.org/stable/api/index.html)
- [`pyplot.subplots`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html) · [`pyplot.pie`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.pie.html)
- [`Axes.hist`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.hist.html) · [`Axes.boxplot`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.boxplot.html) · [`Axes.bar`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.bar.html) · [`Axes.barh`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.barh.html)
- [`Axes.scatter`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.scatter.html) · [`Axes.hexbin`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.hexbin.html)

### scipy und scikit-learn

- [`scipy.stats.probplot`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.probplot.html) (QQ-Plot)
- [scikit-learn, Startseite](https://scikit-learn.org/stable/)
- [`train_test_split`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) · [`cross_val_score`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html) · [`GridSearchCV`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
- [`LinearRegression`](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) · [`DecisionTreeRegressor`](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html) · [`RandomForestRegressor`](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
- [`MinMaxScaler`](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html) · [`StandardScaler`](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
- [`confusion_matrix`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html) · [Metriken im Überblick](https://scikit-learn.org/stable/modules/model_evaluation.html)

### Weitere

- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) (Web Scraping)
- [SQLAlchemy](https://docs.sqlalchemy.org/) (`create_engine`)
- [PostgreSQL-Handbuch](https://www.postgresql.org/docs/current/)

> **Tipp für die Prüfung:** Auf jeder Doku-Seite stehen die **Parameter** mit ihren Standardwerten und ganz unten **Beispiele**. Meist ist der Blick auf die Beispiele schneller als das Lesen der Parameterliste.

## Wo das Beispiel herkommt

Wenn in der Prüfung ein Snippet nicht reicht: Hier steht, in welchem Notebook das ausgeführte Beispiel liegt. Die Repos sind alle in deinem GitHub-Konto geforkt.

### Repo `python_exploratory_data_analysis`

Datensatz: `data/ev_charging_stations.csv` (2442 Zeilen, Schweizer Ladestationen)

| Thema | Datei |
| --- | --- |
| Was EDA ist, Ablauf | `01_introduction_to_eda/introduction_to_eda.ipynb` |
| Lagemasse, Quantile, Schiefe, Kurtosis, Kontingenztabelle, Korrelation | `02_non_graphical_eda/concept_non_graphical_eda.ipynb` · `exercise_...` · `solution_...` |
| Histogramm, Boxplot, QQ-Plot, Hexbin, Heatmap | `03_graphical_eda/concept_graphical_eda.ipynb` · `exercise_...` |
| `fig`/`ax`, Balken, Kreisdiagramm, Subplots | `04_matplotlib/concept_matplotlib.ipynb` · `exercise_...` |
| `histplot`, `violinplot`, `countplot`, `pairplot`, `heatmap` | `05_seaborn/concept_seaborn.ipynb` · `exercise_...` |
| Plotly, Streamlit, FastAPI | `06_interactive_graphics/` — nicht prüfungsrelevant |
| sweetviz, Profiling | `07_automated_eda/` — nicht prüfungsrelevant |

### Repo `python_data_preparation`

Datensätze: `Data/apartments_data_zuerich.csv` · `Data/autoscout24_data.csv`

| Thema | Datei |
| --- | --- |
| Regex-Extraktion, Missing Values, Duplikate, String-Methoden, Diskretisierung, One-Hot, Scaling, Transformationen, `merge`, Pivot | `advanced_data_preparation_apartment_data.ipynb` (durchgearbeitetes Vorbild) |
| Dieselben Schritte als Übung | `advanced_data_preparation_car_data.ipynb` |
| Lösung dazu | `advanced_data_preparation_car_data_solution.ipynb` |

### Repo `data_ingestion`

| Thema | Datei |
| --- | --- |
| BeautifulSoup, HTML parsen | `07_Web_Scraping_Python_BS4/web_scraping_python_beautifulsoup.ipynb` |
| Tabelle aus gespeichertem HTML lesen | `07_Web_Scraping_Python_BS4/skipass_data.ipynb` — Vorbild für AP02 |
| Selenium | `08_Web_Scraping_Python_Selenium_Cloud/web_scraping_python_selenium.ipynb` |

### Repo `python_machine_learning_basics`

Datensätze unter `00_Data/`, u.a. `car_fuel_consumption_2025.csv` und `rental_apartments_canton_zh.csv`.

Jeder Ordner enthält drei Notebooks nach demselben Muster: `*_concept` (Theorie), `*_exercise` (Lücken mit `# TODO`) und `*_solution`.

| Thema | Ordner |
| --- | --- |
| Loss, Train/Test, Kreuzvalidierung, Bias-Varianz | `01_Model_Training_Evaluation/` |
| Regression Tree, Random Forest, Boosting, Feature Importance, Pruning | `03_Regression_Trees_Ensembles/` |
| kNN, Naive Bayes, SVM | `06_kNN_Naive_Bayes_SVM/` — **nicht prüfungsrelevant** |
| Clustering, PCA | `07_Clustering_PCA/` — **nicht prüfungsrelevant** |
| Neuronale Netze | `08_Neural_Networks/` — nicht prüfungsrelevant |

Vollständige Ordnerstruktur, prüfungsrelevant sind 01 bis 05: 01\_Model\_Training\_Evaluation, 02\_Linear\_Regression, 03\_Regression\_Trees\_Ensembles, 04\_Logistic\_Regression\_Evaluation, 05\_Classification\_Trees\_Ensembles. Nicht prüfungsrelevant: 06\_kNN\_Naive\_Bayes\_SVM, 07\_Clustering\_PCA, 08\_Neural\_Networks, 09\_NLP\_Transformers.

### Repo `DS_HS2026_LNW` (Probeprüfung)

| Arbeitspaket | Datei | Daten |
| --- | --- | --- |
| AP01 Relationale Daten | `DS_HS2026_LNW_I_Examples/AP01/AP01_Mgmt_Nutzung_Relationale_Daten.ipynb` | `cinema.db`, `cinema_data.xlsx` (Sheets «Description» und «ER-Diagram») |
| AP02 Beschaffung, Aufbereitung, EDA | `.../AP02/AP02_Datenbeschaffung_Aufbereitung_EDA.ipynb` | `html/shop_page_1–3.html`, `html/product_detail.html`, `reviews.json`, `smartphones_clean.csv` |
| AP03 Machine Learning | `.../AP03/AP03_Machine_Learning.ipynb` | `bicycle_data.csv` |

Zu jedem Arbeitspaket gibt es im selben Ordner eine Datei `..._Musterloesung.ipynb`. **Achtung beim Öffnen:** Die Dateinamen unterscheiden sich nur durch diesen Zusatz am Ende.

### Folien

| Thema | Foliensatz |
| --- | --- |
| Prerequisites, SQL-Wiederholung, Data Quality | Woche 1 |
| Datenquellen, Dateiformate, Scraping, XPath, REST-APIs, RSS | Woche 4, Teil I |
| Data Cleansing, MCAR/MAR/MNAR, Regex, Diskretisierung, One-Hot, Scaling, `merge`, Pivot | Woche 4, Teil II |
| EDA: Lagemasse, Streuung, Schiefe, Kurtosis, Korrelation, Grafiktypen | Woche 5 |
| Supervised Learning: OLS, R², RMSE, Bäume, Ensembles, Konfusionsmatrix, ROC/AUC | Woche 6 |

## Setup und Datenbankverbindung

Jedes Notebook beginnt mit diesem Block. Ohne ihn existiert `engine` nicht und jede Abfrage schlägt fehl.

```python
import pandas as pd
from sqlalchemy import create_engine

engine = create_engine(db_connection_url)
```

**Abfrage absetzen** — das meistgenutzte Muster überhaupt. SQL ist für Python ein String, darum die dreifachen Anführungszeichen:

```python
query = """
    SELECT *
    FROM movies
    WHERE duration_min > 140
    ORDER BY duration_min DESC
"""
df = pd.read_sql_query(query, con=engine)
df
```

**Verbindung schliessen**, wenn du fertig bist:

```python
engine.dispose()
```

**Fallback auf SQLite**, falls PostgreSQL streikt. Tabellen und Inhalte sind identisch, alle Abfragen laufen unverändert:

```python
engine = create_engine('sqlite:///cinema.db')
```

**Kernel prüfen**, wenn etwas unerklärlich schiefgeht. Erwartet wird `/usr/local/bin/python` und Version 3.12:

```python
import sys
print(sys.executable, sys.version)
```

Typische Fehler beim Start:

| Symptom | Ursache | Lösung |
| --- | --- | --- |
| `SyntaxError: invalid syntax` bei `SELECT` | SQL direkt in Python-Zelle geschrieben | SQL in `"""..."""` als String verpacken |
| «erfordert das Paket ipykernel» | falscher Kernel (System-Python 3.11) | Kernel auf Python 3.12 wechseln |
| `connection refused` | Postgres-Container läuft nicht | im Terminal `docker compose up -d --wait` |
| `NameError: engine` | Setup-Zelle nicht ausgeführt | Setup-Zelle laufen lassen |

## Git, Codespace und Terminal

### Die vier Schritte zum Sichern

Speichern im Codespace (`Ctrl+S`) ist **nicht** dasselbe wie sichern. Erst der Push bringt die Arbeit auf GitHub.

```bash
git add .                      # alle Änderungen vormerken
git commit -m "Nachricht"      # Stand festhalten
git push                       # auf GitHub hochladen
git status                     # was ist noch offen?
```

**Jeder** Git-Befehl beginnt mit `git`. `commit -m "..."` allein ergibt `bash: commit: command not found`.

### Remote prüfen

```bash
git remote -v
```

Erwartet: `origin` zeigt auf den **eigenen** Fork, `upstream` (falls vorhanden) auf das Original des Dozenten. Gepusht wird immer nach `origin`.

Falls `origin` aufs Original zeigt:

```bash
git remote set-url origin https://github.com/<benutzername>/<repo>.git
```

### Codespace

- Der Codespace wird aus dem Ordner `.devcontainer` aufgebaut: Python-Version, Pakete und Extensions sind dort festgelegt. Prüfungs-Repos entfernen darüber automatisch alle KI-Extensions.
- **Stoppen** erhält alle Dateien, **Löschen** vernichtet alles, was nicht gepusht wurde.
- Lokal in VS Code gilt der `.devcontainer` **nicht** — dort läuft die lokal installierte Python-Version, nicht die des Containers.

### Kernel

Der häufigste Startfehler. Oben rechts im Notebook prüfen, welcher Kernel aktiv ist.

```python
import sys
print(sys.executable, sys.version)
```

**Die richtige Version hängt vom Repo ab.** Jedes Repo legt in seinem `.devcontainer` eine eigene Python-Version fest: `python_exploratory_data_analysis` nutzt 3.11, das Prüfungs-Repo `DS_HS2026_LNW` nutzt 3.12. Beides ist in der jeweiligen Umgebung richtig — es gibt keine Versionsnummer, die immer stimmt.

Entscheidend ist der **Pfad**: `/usr/local/bin/python` ist die Umgebung des Containers mit allen installierten Paketen. Zeigt es dagegen `/usr/bin/python3`, ist das Debian-System-Python ausgewählt — dort fehlen pandas und Co. Dann: Kernel-Anzeige → **Select Another Kernel…** → **Python Environments…** → den empfohlenen Eintrag wählen.

Der verlässlichste Test ist ohnehin nicht die Zahl, sondern ob die Setup-Zelle des Notebooks fehlerfrei durchläuft.

**Wichtig:** Niemals der Aufforderung folgen, `ipykernel` nachzuinstallieren. Das repariert nur das Symptom und erzeugt eine Umgebung ohne die nötigen Pakete.

### Datenbank-Container

```bash
docker compose up -d --wait    # Postgres starten, falls connection refused
```

### Nützliche Terminal-Befehle

```bash
pwd            # wo bin ich?
ls             # was liegt hier?
cd ordner      # Ordner wechseln
cd ..          # eine Ebene hoch
```

### Fehlermeldungen und ihre Ursache

| Meldung | Ursache | Lösung |
| --- | --- | --- |
| `bash: commit: command not found` | `git` vergessen | `git commit -m "..."` |
| `connection refused` (Port 5432) | Postgres-Container läuft nicht | `docker compose up -d --wait` |
| «erfordert das Paket ipykernel» | falscher Kernel | Kernel des Containers wählen |
| `NameError: engine` | Setup-Zelle nicht ausgeführt | Setup-Zelle laufen lassen |
| `SyntaxError` bei `SELECT` | SQL in einer Python-Zelle | SQL in `"""..."""` verpacken |
| `ModuleNotFoundError` | Paket fehlt oder falscher Kernel | zuerst Kernel prüfen, dann `pip install` |

### Am Prüfungstag

1. Codespace aus dem Prüfungs-Repo starten und warten, bis das Setup fertig ist.
2. Kernel prüfen (Pfad /usr/local/bin/python), **bevor** du mit dem Lösen beginnst.
3. Setup-Zelle des Notebooks ausführen und kontrollieren, dass eine Testabfrage ein Ergebnis liefert.
4. Zwischendurch committen und pushen, nicht erst am Schluss.

Nicht ausführbarer Code gibt null Punkte. Deshalb immer zuerst eine **lauffähige** Fassung herstellen und erst danach Labels, Titel und Feinschliff ergänzen.

## SQL-Grundmuster

### Reihenfolge der Klauseln

Die Schreibreihenfolge ist fix. `WHERE` filtert **vor** der Gruppierung, `HAVING` **nach** der Gruppierung:

```sql
SELECT   spalte, AGG(spalte2)
FROM     tabelle
WHERE    bedingung_auf_einzelzeilen
GROUP BY spalte
HAVING   bedingung_auf_gruppen
ORDER BY spalte DESC
LIMIT    10
```

### Filtern

```sql
WHERE city <> 'Zürich'           -- ungleich
WHERE genre IN ('Action', 'Drama')
WHERE duration_min BETWEEN 90 AND 120
WHERE title LIKE 'The %'         -- % = beliebig viele Zeichen
WHERE birthdate IS NULL          -- niemals = NULL schreiben
```

### Aggregation

`COUNT(*)` zählt Zeilen, `COUNT(spalte)` zählt nur Nicht-NULL-Werte. Der Unterschied ist prüfungsrelevant.

```sql
SELECT   genre, COUNT(*) AS anzahl, AVG(duration_min) AS schnitt
FROM     movies
GROUP BY genre
HAVING   COUNT(*) > 2
```

Regel: Jede Spalte im `SELECT`, die nicht in einer Aggregatfunktion steht, muss in `GROUP BY` stehen.

### Joins

```sql
SELECT s.screeningid, m.title, c.name AS kino
FROM   screenings AS s
JOIN   movies  AS m ON s.movieid  = m.movieid
JOIN   cinemas AS c ON s.cinemaid = c.cinemaid
```

| Join-Typ | Behält | Typischer Einsatz |
| --- | --- | --- |
| `INNER JOIN` | nur Zeilen mit Treffer auf beiden Seiten | Standardfall, Verknüpfung über Fremdschlüssel |
| `LEFT JOIN` | alle Zeilen der linken Tabelle, fehlende rechts werden NULL | Objekte ohne zugehörige Datensätze sichtbar machen |
| `FULL OUTER JOIN` | alle Zeilen beider Seiten | selten, in SQLite nicht verfügbar |

**Merksatz:** Ein `INNER JOIN` lässt Datensätze stillschweigend verschwinden. Wenn eine Frage mit «alle …, auch die ohne …» beginnt, brauchst du einen `LEFT JOIN`.

### Anti-Join: Datensätze ohne Gegenstück finden

```sql
SELECT c.cinemaid, c.name
FROM   cinemas AS c
LEFT JOIN screenings AS s ON c.cinemaid = s.cinemaid
WHERE  s.screeningid IS NULL
```

Das Muster — LEFT JOIN plus `WHERE rechte_spalte IS NULL` — beantwortet alle Fragen der Form «welche X haben kein Y».

### Aggregation über einen LEFT JOIN

Achtung beim Zählen: `COUNT(*)` zählt auch die leere Treffer-Zeile und liefert fälschlicherweise 1 statt 0. Richtig ist `COUNT(s.screeningid)`, weil NULL nicht mitgezählt wird.

```sql
SELECT   c.name, COUNT(s.screeningid) AS anzahl_vorstellungen
FROM     cinemas AS c
LEFT JOIN screenings AS s ON c.cinemaid = s.cinemaid
GROUP BY c.name
```

### NULL-Handling

`NULL` ist «unbekannt», nicht null und nicht leerer String. Jeder Vergleich mit `=` ergibt wieder unbekannt.

```sql
WHERE spalte IS NULL / IS NOT NULL
COALESCE(spalte, 0)              -- NULL durch Ersatzwert ersetzen
```

### Datenqualität prüfen

Duplikate auf einem Schlüssel:

```sql
SELECT   ticketid, COUNT(*)
FROM     tickets
GROUP BY ticketid
HAVING   COUNT(*) > 1
```

Verwaiste Verweise (referenzielle Integrität) findest du mit demselben Anti-Join-Muster wie oben.

## pandas-Grundmuster

Die Denkweise ist dieselbe wie bei SQL, nur die Syntax ist anders. Diese Gegenüberstellung hilft beim Übersetzen:

| SQL | pandas |
| --- | --- |
| `SELECT a, b` | `df[['a', 'b']]` |
| `WHERE x > 5` | `df[df['x'] > 5]` |
| `ORDER BY x DESC` | `df.sort_values('x', ascending=False)` |
| `GROUP BY k` | `df.groupby('k')` |
| `COUNT(*)` | `.size()` |
| `COUNT(spalte)` | `.count()` |
| `LEFT JOIN` | `pd.merge(..., how='left')` |
| `LIMIT 10` | `df.head(10)` |

### Spalten auswählen

```python
df['preis']            # Series (eine Spalte)
df[['preis']]          # DataFrame (Tabelle mit einer Spalte)
df[['preis', 'jahr']]  # mehrere Spalten
```

**Fallstrick:** Einfache Klammern geben eine Series, doppelte einen DataFrame. scikit-learn erwartet für `X` einen DataFrame (doppelte Klammern), für `y` eine Series (einfache).

### Zeilen filtern

```python
df[df['preis'] > 20000]
df[(df['preis'] > 20000) & (df['jahr'] >= 2018)]    # UND
df[(df['marke'] == 'Audi') | (df['marke'] == 'BMW')] # ODER
df[df['marke'].isin(['Audi', 'BMW'])]                # kürzer
df[~df['marke'].isin(['Audi'])]                      # NICHT
df[df['preis'].between(10000, 20000)]
df[df['preis'].isna()]
```

**Drei Fallstricke:**

- `&` und `|` statt `and`/`or` — letztere lösen einen `ValueError` aus.
- **Jede** Teilbedingung in eigene Klammern, sonst greift die falsche Operator-Rangfolge.
- `df.loc[zeilen, spalten]` wählt beides gleichzeitig: `df.loc[df['preis'] > 20000, ['marke', 'preis']]`.

### Gruppieren und aggregieren

```python
df.groupby('marke')['preis'].mean()
df.groupby('marke')['preis'].agg(['count', 'mean', 'median'])
df.groupby(['marke', 'treibstoff'])['preis'].mean()

# mehrere Spalten, eigene Namen
df.groupby('marke').agg(
    anzahl=('preis', 'size'),
    preis_median=('preis', 'median'),
    km_mittel=('km', 'mean')
).reset_index()
```

**Fallstricke:** `size()` zählt Zeilen (wie `COUNT(*)`), `count()` nur Nicht-NULL-Werte (wie `COUNT(spalte)`) — derselbe Unterschied wie in SQL. `groupby` macht die Gruppierungsspalte zum Index; `reset_index()` macht daraus wieder eine normale Spalte.

### Tabellen zusammenführen

```python
pd.merge(df_links, df_rechts, on='id', how='left')
pd.merge(df_a, df_b, left_on='kunde_id', right_on='id', how='inner')
pd.concat([df1, df2], ignore_index=True)   # untereinander hängen
```

`how` kennt `'inner'` (Standard), `'left'`, `'right'`, `'outer'` — identisch zu den SQL-Join-Typen.

**Fallstrick:** Immer die Zeilenzahl vorher und nachher vergleichen. Wächst sie, hat der Schlüssel auf einer Seite Duplikate. Schrumpft sie bei `how='inner'`, fehlen Gegenstücke.

#### Beispiel: Geodaten an Wohnungsdaten hängen (Apartment-Notebook)

```python
df2 = df.merge(df_geo[['web-scraper-order', 'lat', 'lon', 'bfs_number', 'bfs_name']],
               on='web-scraper-order')
```

| Teil | Bedeutung |
| --- | --- |
| `df.merge(...)` | Methoden-Schreibweise: `df` ist die **linke** Tabelle. Gleichwertig zu `pd.merge(df, df_geo[...], ...)` |
| `df_geo[[...]]` | nur die benötigten Spalten der **rechten** Tabelle mitnehmen (doppelte Klammern = DataFrame) |
| `on='web-scraper-order'` | Schlüsselspalte, die in **beiden** Tabellen vorkommt und die Zeilen einander zuordnet |
| `how` (fehlt) | Standard `'inner'`: nur Wohnungen mit Gegenstück in `df_geo` bleiben |

Ergebnis: jede Wohnung erhält `lat`, `lon`, `bfs_number` und `bfs_name` als neue Spalten.

Drei Kontrollen nach dem Merge:

- `len(df)` vs. `len(df2)`: weniger Zeilen = Wohnungen ohne Geodaten fielen weg (inner); mehr Zeilen = Schlüssel in `df_geo` nicht eindeutig.
- Nur die nötigen Spalten mitnehmen: Kommt eine Spalte (ausser dem Schlüssel) in beiden Tabellen vor, entstehen `_x`/`_y`-Spalten.
- Sollen alle Wohnungen erhalten bleiben, `how='left'` setzen; fehlende Geodaten werden dann `NaN`.

### Datentypen

```python
df.dtypes
df['preis'] = df['preis'].astype(float)
df['preis'] = pd.to_numeric(df['preis'], errors='coerce')  # Fehler → NaN
df['datum'] = pd.to_datetime(df['datum'], errors='coerce')
```

**Fallstrick:** `object` bei einer Spalte, die numerisch sein sollte, bedeutet fast immer: Text im Wert (Einheiten, Tausendertrennzeichen, «k.A.»). `errors='coerce'` macht daraus NaN, statt die Umwandlung abzubrechen — danach `isna().sum()` prüfen.

### Neue Spalten und Sortieren

```python
df['preis_pro_km'] = df['preis'] / df['km']
df = df.sort_values(['marke', 'preis'], ascending=[True, False])
df = df.reset_index(drop=True)
```

**Index nach dem Sortieren:** Nach `sort_values` behalten die Zeilen ihren alten Index (z. B. 1734, 52, …). Das ist kein Fehler, aber wer danach mit `.iloc` oder per Position arbeitet, setzt den Index mit `reset_index(drop=True)` neu auf 0, 1, 2, … (`drop=True` verhindert, dass der alte Index als zusätzliche Spalte erhalten bleibt).

### Vektorisiert rechnen statt Schleife

```python
# idiomatisch: der Operator arbeitet elementweise auf der ganzen Spalte
df['price_per_m2'] = df['price'] / df['area']

# umständlich und langsam
for i in range(len(df)):
    df.loc[i, 'price_per_m2'] = df.loc[i, 'price'] / df.loc[i, 'area']
```

**Faustregel:** Wer in pandas eine `for`-Schleife über Zeilen schreiben will, übersieht meist den vektorisierten Weg.

**Zwei stille Nebenwirkungen bei berechneten Spalten:**

- Ist einer der beiden Werte `NaN`, wird das Ergebnis `NaN` — ohne Fehler und ohne Warnung.
- Division durch 0 ergibt `inf` (bei 0/0 ebenfalls `NaN`). Vorher filtern, wenn der Nenner 0 sein kann:

```python
valid = df[df['area'] > 0].copy()
valid['price_per_m2'] = valid['price'] / valid['area']
```

Das `.copy()` ist nötig, weil `df[...]` nur eine **Sicht** auf den ursprünglichen DataFrame liefert. Schreibt man ohne Kopie eine Spalte hinein, erscheint eine `SettingWithCopyWarning` und die Änderung landet möglicherweise nicht dort, wo man sie erwartet.

### Zählen: vier Methoden, vier Ergebnisse

| Aufruf | Ergebnis | Zählt |
| --- | --- | --- |
| `df['col'].nunique()` | eine Zahl | verschiedene Werte im **ganzen** DataFrame |
| `df.groupby('g')['col'].nunique()` | Series | verschiedene Werte **pro Gruppe** |
| `df.groupby('g').size()` | Series | **Zeilen** pro Gruppe |
| `df.groupby('g').count()` | DataFrame | **Nicht-NA-Werte** je Spalte und Gruppe |
| `df['col'].value_counts()` | Series | Häufigkeit jeder Ausprägung, absteigend sortiert |

**Wichtig:** `size()` und `count()` sind **nicht** dasselbe. Enthält eine Gruppe mit 2 Zeilen einen fehlenden Wert, liefert `size()` 2 und `count()` 1. Das ist exakt der Unterschied zwischen `COUNT(*)` und `COUNT(spalte)` in SQL.

Ein Skalar lässt sich nicht weitergruppieren — `df.groupby('city')[df['x'].nunique()]` wirft einen `KeyError`, weil pandas die Zahl als Spaltennamen sucht.

### Top N auswählen: drei Situationen

```python
# 1. Ranking nach Häufigkeit
top10 = df['city'].value_counts().head(10)

# 2. Ranking nach einer Kennzahl
top10_teuer = (df.groupby('city')['price'].mean()
                 .sort_values(ascending=False).head(10))

# 3. Den ganzen DataFrame auf die Top 10 filtern (zum Weiterplotten)
top10_namen = df['city'].value_counts().head(10).index
df_top10 = df[df['city'].isin(top10_namen)]
```

`value_counts()` beantwortet «wie oft?», `groupby().agg()` beantwortet «wie viel im Durchschnitt?». Für Rankings nach Beträgen immer `groupby()`.

**Zwei Fallen in der Methodenkette:**

- `sort_index()` sortiert nach dem **Index** (alphabetisch), `sort_values()` nach den **Werten**. Wer «die grössten 10» will, braucht `sort_values(ascending=False)` oder `value_counts()`, das bereits vorsortiert ist.
- Die **Reihenfolge** entscheidet: `value_counts().head(10).sort_index()` liefert die 10 häufigsten, alphabetisch angeordnet. `value_counts().sort_index().head(10)` liefert dagegen die alphabetisch ersten 10 Städte — ein ganz anderes Ergebnis.

Beim Debuggen einer Kette hilft es, die Zwischenschritte einzeln auszugeben:

```python
print(df['city'].value_counts())            # stimmt die Sortierung?
print(df['city'].value_counts().head(10))   # sind es wirklich 10?
```

### `axis=0` und `axis=1`

```python
df[['a', 'b', 'c']].sum(axis=1)   # Zeilensumme — über die Spalten hinweg
df[['a', 'b', 'c']].sum(axis=0)   # Spaltensumme — über die Zeilen hinweg (Standard)
df.drop('spalte', axis=1)         # Spalte entfernen
```

**Merksatz:** `axis=1` bewegt sich **horizontal** (über Spalten), `axis=0` **vertikal** (über Zeilen). Ohne Angabe gilt `axis=0`.

Typische Anwendung — eine Summenspalte gegen ihre Bestandteile prüfen:

```python
passt = df[['teil_1', 'teil_2', 'teil_3']].sum(axis=1) == df['total']
konsistent   = df[passt]
inkonsistent = df[~passt]      # ~ ist das logische NICHT

assert len(konsistent) + len(inkonsistent) == len(df)
```

### Grösse prüfen

```python
df.shape        # (Zeilen, Spalten)
df.shape[0]     # Anzahl Zeilen
df.shape[1]     # Anzahl Spalten
len(df)         # ebenfalls Anzahl Zeilen
```

Bei einer Series hat `shape` nur eine Dimension: `(n,)`. `shape[1]` läuft dort auf einen `IndexError`.

### Zahlen lesbar ausgeben (f-Strings)

In der Prüfung wird gerundete, beschriftete Ausgabe erwartet. Das Format steht nach dem Doppelpunkt:

```python
print(f"Mittelwert: {df['preis'].mean():.2f}")
print(f"Anteil:     {0.15234:.2%}")      # 15.23%
print(f"Betrag:     {1234567.89:,.0f}")  # 1,234,568
```

| Format | aus 1234.5678 wird | wofür |
| --- | --- | --- |
| `:.2f` | 1234.57 | zwei Dezimalstellen |
| `:.0f` | 1235 | ganze Zahl |
| `:,.2f` | 1,234.57 | mit Tausendertrennzeichen |
| `:.2%` | (aus 0.15234) 15.23% | Prozent |
| `:.3e` | 1.235e+03 | wissenschaftlich |

**Fallstrick:** Nur **ein** Punkt vor der Stellenzahl. `:,..2f` wirft `ValueError: Format specifier missing precision`.

### `.mode()` gibt eine Series zurück

```python
df['preis'].mode()      # Series — es kann mehrere häufigste Werte geben
df['preis'].mode()[0]   # der erste davon, als Zahl
```

Ohne `[0]` schlägt jede Formatierung fehl. `mean()` und `median()` liefern dagegen direkt eine Zahl.

## Datenaufbereitung

### Datensatz laden (CSV)

```python
# Load the dataset
df = pd.read_csv('/workspaces/python_exploratory_data_analysis/data/ev_charging_stations.csv')
```

Ein Komma am Ende der Argumentliste (`read_csv('…', )`) ist erlaubt, aber unnötig: Python ignoriert es.

**CSV mit Semikolon und Encoding** (Apartment-Notebook, Geodaten):

```python
df_geo = pd.read_csv('./Data/apartments_data_geocoded.csv',
                     sep=';',            # Trennzeichen zwischen den Spalten
                     encoding='utf-8')   # Zeichensatz, wichtig für ä, ö, ü
df_geo.head()
```

Standard ist `sep=','`. Steht in der Datei `;` (in der Schweiz und in Deutschland häufig, weil das Komma Dezimaltrenner ist) und fehlt `sep=';'`, landet alles in **einer** Spalte. Falsches Encoding zeigt sich an kaputten Umlauten (`ZÃ¼rich`) oder einem `UnicodeDecodeError`; dann z. B. `encoding='latin-1'` versuchen. Kontrolle immer mit `.head()` und `.shape`.

**Immer relative Pfade verwenden.** Ein absoluter Pfad enthält den Namen des Workspace:

```python
# bricht in jeder anderen Umgebung
df = pd.read_csv('/workspaces/python_exploratory_data_analysis/data/datei.csv')

# funktioniert überall
df = pd.read_csv('../data/datei.csv')
```

In der Prüfung heisst der Workspace anders als beim Üben — ein absoluter Pfad führt dort zu `FileNotFoundError`, und nicht lauffähiger Code gibt null Punkte.

Der relative Pfad zählt ab dem **Ordner des Notebooks**: `../` geht eine Ebene hoch, `./` bleibt im selben Ordner. Bei Unsicherheit zeigt `print(os.getcwd())`, von wo aus gezählt wird.

### Datensatz-Übersicht: Shape, Duplikate, Missing Values

Kennzahlen für das ganze Dataset als beschriftete `print`-Zeilen, Infos **pro Spalte** als eigenes DataFrame:

```python
print('Shape:', df.shape)
print('Nr. of Duplicated Rows:', df.duplicated().sum())

df_summary = pd.DataFrame({
    'Data Type':             df.dtypes,
    'Sum of Missing Values': df.isna().sum(),
    'Missing Values in %':   (df.isna().mean() * 100).round(2),
    'Nr of Unique Values':   df.nunique()
})

display(df.head(3))
display(df_summary)
```

- Jupyter zeigt nur den **letzten Ausdruck** einer Zelle automatisch an. Für Tabellen mitten in der Zelle `display()` verwenden, nicht `print()` (sonst reiner Text).
- `df.info()` nicht in `display()` packen: `info()` gibt selbst aus und liefert `None`.
- `isna().mean()` ist ein **Anteil** (0–1). Zuerst `* 100`, dann runden, darum die Klammern.
- `duplicated()` zählt doppelte **Zeilen**; ohne `.sum()` gibt es eine True/False-Serie pro Zeile.

### Fehlende Werte: MCAR, MAR, MNAR (W4 II, S. 8–11)

Der Mechanismus entscheidet, ob Entfernen zulässig ist. In Teil A ist die Begründung am Datensatz gefragt, nicht die Definition.

| Mechanismus | Bedeutung | Folge beim Entfernen |
| --- | --- | --- |
| **MCAR** | Das Fehlen hängt weder von der Variablen selbst noch von anderen ab | Entfernen ist unproblematisch |
| **MAR** | Das Fehlen hängt von **anderen** Variablen ab, nicht von der fehlenden selbst | Ergebnis verzerrt, Zusammenhänge bleiben unverzerrt |
| **MNAR** | Das Fehlen hängt von der **fehlenden Variablen selbst** ab | Ergebnis und Zusammenhänge verzerrt |

Prüffrage für die Zuordnung: *Warum* fehlt der Wert? Hängt der Grund am Wert selbst (hohe Preise werden ausgeblendet, tiefe Einkommen nicht genannt), ist es MNAR. Hängt er an einer anderen Variablen, MAR.

### Fehlende Werte behandeln

```python
df.isna().sum()                     # Anzahl je Spalte
df.isna().mean().round(4) * 100     # Anteil in Prozent

df = df.dropna()                            # alle Zeilen mit NaN
df = df.dropna(subset=['preis'])            # nur bei dieser Spalte

df['preis'] = df['preis'].fillna(df['preis'].median())   # Imputation
```

**Entfernen oder imputieren (S. 9):** Entfernen kostet Fälle und verzerrt bei MAR und MNAR. Imputation erhält den Stichprobenumfang, erfindet aber Werte und verringert die Streuung künstlich. Bei schiefen Verteilungen ist der **Median** die robustere Imputation als der Mittelwert.

#### Übung: Missing Values zählen und entscheiden

```python
print(f"Number of missing values: {pd.isna(df).sum().sum()}")
df = df.dropna().reset_index(drop=True)
```

Jede `.sum()` summiert eine Dimension weg:

| Schritt | Ergebnis |
| --- | --- |
| `pd.isna(df)` | DataFrame mit `True`/`False`, gleiche Form wie `df` |
| `.sum()` | Series: Anzahl NaN **pro Spalte** (`True` zählt als 1) |
| `.sum().sum()` | eine Zahl: NaN im **ganzen** DataFrame |

**Löschen ist eine Entscheidung, keine Regel.** Im Apartment-Notebook fielen durch `dropna()` 147 von 1008 Zeilen weg (rund 15 %). Die NaN entstanden erst bei der Regex-Extraktion. `dropna()` löscht immer die **ganze Zeile**, also auch gültige Werte in anderen Spalten. Fehlen Werte nicht zufällig (z. B. vor allem bei teuren Wohnungen), entsteht **Bias**: Zusammenhänge und Kennzahlen wie der Durchschnittspreis verschieben sich.

Alternative **Imputation** am Beispiel `rooms`:

- **Median** statt Mean: robust gegenüber Ausreissern und ergibt eher eine realistische Zimmerzahl.
- **Aus einer verwandten Spalte schätzen:** typisches Verhältnis m² pro Zimmer aus den vollständigen Zeilen (Median), dann `rooms ≈ area / Verhältnis`, auf halbe Zimmer runden. Geht nur, wenn `area` in dieser Zeile vorhanden ist.
- Imputierte Werte in einer Hilfsspalte markieren, damit spätere Analysen sie erkennen.

#### Missing Values und Duplikate: eigene Lösung vs. Dozent (Car-Notebook)

Eigene Lösung:

```python
print(f"Number of missing values: {pd.isna(df).sum().sum()}")
df = df.dropna().reset_index(drop=True)

print(f"Number of duplicated values: {df[['offer_id']].duplicated().sum()}")
df = df.drop_duplicates().reset_index(drop=True)
print('\nDimension:', df.shape)
```

Lösung Dozent:

```python
print("Missing values before removing: ", df.isnull().sum().sum())
df = df.dropna()
print("Missing values after removing: ", df.isnull().sum().sum())
df = df.reset_index(drop=True)

print("Number of duplicates before removing: ", df.duplicated().sum())
df = df.drop_duplicates()
print("Number of duplicates after removing: ", df.duplicated().sum())
df = df.reset_index(drop=True)
```

|  | Eigene Lösung | Dozent |
| --- | --- | --- |
| Kontrolle | nur vorher gezählt | **vorher und nachher** gezählt (23 → 0) |
| Mehrfach ausführen | zeigt beim 2. Lauf 0, obwohl Zeilen fehlen → verwirrend | Vorher/Nachher macht den Stand jederzeit nachvollziehbar |
| Duplikate zählen vs. löschen | zählt nur nach `offer_id`, löscht nach **allen** Spalten → inkonsistent | zählt und löscht beide nach allen Spalten → konsistent |
| Kürze | kompakt, `reset_index` direkt verkettet | etwas länger |

`isnull()` und `isna()` sind identisch, nur zwei Namen für dieselbe Methode.

**Empfehlung:** Die Variante des Dozenten übernehmen: immer vorher und nachher ausgeben und für Zählen und Löschen dasselbe Kriterium verwenden. Sollen Duplikate nach einem Schlüssel erkannt werden, beides mit demselben `subset` aufrufen:

```python
df['offer_id'].duplicated().sum()
df = df.drop_duplicates(subset=['offer_id'], keep='last')   # bei keep='last' vorher nach scrape_dt sortieren
```

Zusätzlich hilfreich: `df.shape` vor und nach dem Bereinigen ausgeben. Wichtig: Notebook immer von oben nach unten ausführen. Wird eine Bereinigungszelle zweimal ausgeführt, arbeitet sie auf bereits bereinigten Daten.

### Duplikate

```python
df.duplicated().sum()                        # vollständig gleiche Zeilen
df.duplicated(subset=['id']).sum()           # Duplikate auf einem Schlüssel
df = df.drop_duplicates().reset_index(drop=True)
```

### Ausreisser

```python
q1, q3 = df['preis'].quantile([0.25, 0.75])
iqr = q3 - q1
unten, oben = q1 - 1.5 * iqr, q3 + 1.5 * iqr
ausreisser = df[(df['preis'] < unten) | (df['preis'] > oben)]

df = df.loc[(df['preis'] >= 1000) & (df['preis'] <= 5000)]   # plausible Grenzen
```

**Merksatz:** Ein **Messfehler** ist technisch falsch (negatives Alter, Preis 0) und darf entfernt werden. Ein **Ausreisser** ist ein echter, nur seltener Wert — Entfernen muss begründet werden, sonst verfälschst du das Ergebnis. Prüfen, ob der Wert physikalisch oder fachlich möglich ist, bevor er fliegt.

### Strings bereinigen und Regex

```python
df['marke'] = df['marke'].str.strip().str.lower()
df['marke'] = df['marke'].replace({'vw': 'volkswagen'})

# Zahl aus Text extrahieren: "120 PS" → 120
df['ps'] = df['leistung'].str.extract(r'(\d+)').astype(float)

# Tausendertrennzeichen und Einheit entfernen: "CHF 24'900" → 24900
df['preis'] = (df['preis'].str.replace(r"[^\d.]", "", regex=True)
                           .pipe(pd.to_numeric, errors='coerce'))
```

Nützliche Regex-Bausteine: `\d` Ziffer, `+` ein- oder mehrmals, `[^...]` alles ausser, `()` Fanggruppe für `extract`.

#### Regex im Detail (Übung Apartment-Daten)

`re.findall(pattern, string)` sucht alle Treffer von `pattern` in `string` und gibt eine **Liste** zurück. Ohne Klammern im Muster kommen die ganzen Treffer zurück, mit **einer** Gruppe `( )` nur deren Inhalt, mit mehreren Gruppen eine Liste von Tupeln.

| Baustein | Bedeutung | Beispiel |
| --- | --- | --- |
| `\d` | eine Ziffer | `\d` → `7` |
| `\s` | Leerzeichen oder Tab |  |
| `.` | beliebiges Zeichen |  |
| `+` | 1 oder mehr | `\d+` → `2100` |
| `*` | 0 oder mehr | `\s*` |
| `?` | 0 oder 1 (optional) | `,?` |
| `{n,m}` | n bis m Mal | `\d{1,3}` → `120` |
| `[ ]` | eines dieser Zeichen | `[,.]` → Komma oder Punkt |
| `\|` | ODER | `a\|b` |
| `( )` | Gruppe: das, was zurückkommt |  |
| `(?: )` | Gruppe, die zusammenfasst, aber nichts zurückgibt |  |
| `\` | Sonderzeichen wörtlich nehmen | `\.` → echter Punkt |

**Muster bauen in vier Schritten:**

1. Ein paar Rohstrings anschauen: Wie sieht der Wert aus, was steht davor oder danach?
2. Diesen Anker wörtlich ins Muster schreiben (z. B. `Zimmer`, `km`).
3. Den variablen Teil mit Bausteinen beschreiben und in `( )` setzen.
4. Auf regex101.com testen (Flavor „Python“).

**Muster direkt im Notebook testen**, bevor es in die Schleife kommt:

```python
re.findall(r"(\d{1,3}(?:'\d{3})*)\s*km", "75'000 km")   # erwartet: ["75'000"]
```

Kommt eine leere Liste `[]` zurück, greift das Muster nicht. In der Schleife landet dann jede Zeile im `except`, und die ganze Spalte wird `NaN`, ohne Fehlermeldung. Typische Ursache: ein Tippfehler im Quantifier, z. B. `{1:3}` statt `{1,3}`; Regex liest `{1:3}` dann als wörtlichen Text.

**Unsichtbare Unterschiede: welches Zeichen steht wirklich da?** Greift ein Muster trotz richtigem Aufbau nicht, steckt oft ein Sonderzeichen dahinter, das gleich aussieht, aber ein anderes ist.

```python
[hex(ord(c)) for c in df['price_raw'][0]]   # Unicode-Code jedes Zeichens
```

`ord()` liefert die Nummer eines Zeichens, `hex()` zeigt sie als Unicode-Code. Häufige Verwechslung bei Strichen:

| Zeichen | Name | Unicode | Beispiel |
| --- | --- | --- | --- |
| `-` | Bindestrich | U+002D | Tastatur, Code |
| `–` | Halbgeviertstrich | U+2013 | Car-Daten: `CHF 22'500.–` |
| `—` | Geviertstrich | U+2014 | Gedankenstrich |
| `−` | Minuszeichen | U+2212 | mathematische Texte |

Faustregel bei gescrapten Daten: stabile Anker wie `CHF` oder `km` wählen, keine Sonderzeichen am Rand.

**Beispiel 1: Zimmerzahl**

```python
rooms = []
for i in df['rooms_area_price_raw']:          # i = Rohstring einer Zeile
    d1 = re.findall(r"(\d+,\d+|\d+)\s*Zimmer", i) # z. B. ['3,5']
    try:
        d2 = d1[0].strip().replace(',', '.')  # '3,5' → '3.5'
    except:
        d2 = None                             # leere Liste → IndexError
    rooms.append(d2)

df['rooms'] = pd.Series(rooms, dtype="float64") # Strings → Zahlen, None → NaN
```

Muster gelesen: Dezimalzahl mit Komma **oder** Ganzzahl, dann beliebig viele Leerzeichen, dann wörtlich „Zimmer“. `i` ist die Schleifenvariable und enthält pro Durchlauf den Rohstring einer Zeile.

Drei Fallstricke:

- `findall` steht ausserhalb von `try`: Ist ein Rohwert `NaN`, bricht der Code ab.
- `pd.Series(rooms)` hat den Index 0…n-1. Wurden vorher Zeilen gelöscht, landen Werte in falschen Zeilen. Lösung: `index=df.index` angeben.
- Ohne Raw-String `r"..."` warnt Python bei `\d`.

**Beispiel 2: Kilometer mit Tausender-Hochkomma**

```python
treffer = re.findall(r"(\d{1,3}(?:'\d{3})*)\s*km", raw)   # "1'250'000 km" → ["1'250'000"]
km = float(treffer[0].replace("'", ""))          # → 1250000.0
```

| Teil | Bedeutung | Im Ergebnis? |
| --- | --- | --- |
| `( … )` | äussere Gruppe = die ganze Zahl | ja |
| `\d{1,3}` | erster Block: 1 bis 3 Ziffern | ja |
| `(?:'\d{3})*` | Block aus Hochkomma + genau 3 Ziffern, 0-mal oder beliebig oft | ja |
| `\s*` | Leerzeichen zwischen Zahl und Einheit | nein |
| `km` | Anker | nein |

| Rohstring | Ergebnis | Block B kommt vor |
| --- | --- | --- |
| `950 km` | `['950']` | 0-mal |
| `120'000 km` | `["120'000"]` | 1-mal |
| `1'250'000 km` | `["1'250'000"]` | 2-mal |

Typische Fehler beim Bauen: Ein Quantifier (`*`, `{n,m}`) wirkt nur auf das **direkt davorstehende** Element. Zwei Quantifier hintereinander (`\d+{3}`) werfen `multiple repeat`. Leerzeichen im Muster sind echte Zeichen. Zwei normale Gruppen liefern Tupel, deshalb die innere als `(?: )`.

**Zwei Lösungswege im Vergleich: Car-Notebook (eigene Lösung vs. Dozent)**

Kilometer und PS, eigene Lösung mit Anker:

```python
d1 = re.findall(r"(\d{1,3}(?:'\d{3})*)\s*km", i)   # ["75'000"]
d2 = d1[0].strip().replace("'", "")                 # '75000'

d1 = re.findall(r"(\d+)\s*PS", i)                    # ['245']
d2 = d1[0].strip()
```

Kilometer und PS, Dozent mit `join`:

```python
d1 = re.findall("\d+", i)        # "75'000 km" → ['75', '000']
d2 = int(''.join(d1))            # '75' + '000' → 75000
```

`\d+` findet jede Ziffernfolge einzeln, das Hochkomma trennt sie. `''.join(...)` klebt alle Teile ohne Trenner wieder zusammen. Gleicher Code für `hp_raw`.

Preis, eigene Lösung vs. Dozent:

```python
re.findall(r"CHF\s*(\d{1,3}(?:'\d{3})*)\.–", i)   # eigene: striktes Tausenderformat
re.findall("CHF\s*([\d']+)\.–", i)                 # Dozent: beliebige Folge aus Ziffern und '
```

`[\d']` steht für **ein** Zeichen, das eine Ziffer **oder** ein Hochkomma ist; `+` wiederholt es. Akzeptiert werden also auch `22500`, `2'2'5'00` oder `'''`.

|  | Eigene Lösung | Dozent |
| --- | --- | --- |
| Muster | genau: Tausenderformat + Anker (`km`, `PS`, `CHF`) | einfach: `\d+` bzw. `[\d']+` |
| Hochkomma | mit `.replace("'", "")` entfernt | durch `join` übersprungen bzw. mit `.replace()` entfernt |
| Falsches Format (`2'2'5'00`) | wird abgelehnt → `NaN` | wird akzeptiert |
| Weitere Zahlen im String (`Baujahr 2019, 75'000 km`) | richtig: 75'000 | falsch, ohne Fehlermeldung: 201'975'000 |
| Vorteil | robust bei gemischten Rohtexten, prüft das Format | kurz, schnell geschrieben, wenig Fehlerquellen beim Tippen |
| Nachteil | länger, Tippfehler (z. B. `{1:3}`) führen still zu `NaN` | funktioniert nur, wenn der String sonst keine Zahlen enthält |

**Faustregel:** Enthält der Rohstring nur die gesuchte Zahl (wie `mileage_raw`, `hp_raw`), reicht die einfache Variante. Bei gemischten Texten (wie `rooms_area_price_raw`) braucht es einen Anker. An der Prüfung zählt lauffähiger Code mit richtigem Ergebnis; die einfache Variante ist oft schneller geschrieben.

Datentyp: Der Dozent verwendet `dtype="Int64"` (ganze Zahl mit `NaN`-Unterstützung), die eigene Lösung `"float64"`. Beides funktioniert.

**Anführungszeichen `'` oder `"`**

Technisch kein Unterschied, beide erzeugen denselben String (auch Spaltennamen sind Strings). Python beendet den String beim **nächsten gleichen** Zeichen. Enthält der Text `'`, aussen `"…"` verwenden und umgekehrt, oder das innere Zeichen escapen: `"Er sagte \"Hallo\""`. Sonst nur konsistent bleiben.

### Diskretisieren (Binning)

```python
df['preis_kat'] = pd.qcut(df['preis'], q=5,
                          labels=['sehr tief','tief','mittel','hoch','sehr hoch'])
df['alter_kat'] = pd.cut(df['alter'], bins=[0, 30, 60, 100],
                         labels=['jung','mittel','alt'])
```

`qcut` teilt nach **Quantilen** (gleich viele Fälle je Gruppe), `cut` nach **Wertgrenzen** (gleich breite oder selbst gewählte Intervalle).

#### Diskretisierung: eigene Lösung vs. Dozent (Car-Notebook, `price_per_hp`)

Bei schiefen Daten verteilt `pd.cut(bins=5)` fast alles auf eine Klasse (bei `price_per_hp` 3918 von 3971 in „very cheap“, weil ein Oldtimer mit 2125 CHF/PS die Spannweite bestimmt). Deshalb `pd.qcut`.

```python
# eigene Lösung: Kontrolle mit Zahlen
df['price_per_hp_cat'] = pd.qcut(df['price_per_hp'], q=5,
    labels=['very cheap', 'cheap', 'normal', 'expensive', 'very expensive'])
display(df['price_per_hp_cat'].value_counts().sort_index())
display(df[['type', 'price', 'hp', 'price_per_hp']].loc[df['price_per_hp_cat'] == 'very expensive'])

# Dozent: Kontrolle mit Grafiken
df['price_per_hp_bin'] = pd.qcut(df['price_per_hp'], q=5,
    labels=['very cheap', 'cheap', 'normal', 'expensive', 'very expensive'])

plt.figure(figsize=(8, 3))
plt.subplot(1, 2, 1)
sns.histplot(df['price_per_hp'], bins=25, kde=True)
plt.title("Histogram of variable 'price_per_hp'", fontsize=10)
plt.xlabel('Price per HP')
plt.ylabel('Frequency')

plt.subplot(1, 2, 2)
sns.countplot(data=df, x='price_per_hp_bin', orient='v')
plt.title("Barchart of variable 'price_per_hp_bin'", fontsize=10)
plt.xlabel('Price category')
plt.ylabel('Frequency')
plt.xticks(rotation=45)
plt.show()

df[['price_per_hp', 'price_per_hp_bin']].head()
```

| Grafik | Was sie zeigt |
| --- | --- |
| Histogramm von `price_per_hp` | **warum** `qcut` nötig ist: stark rechtsschief, fast alles unter 300, Ausreisser bis über 2000 |
| Balkendiagramm der Kategorien | **dass** `qcut` funktioniert hat: fünf gleich hohe Balken |

**Empfehlung:** Die Kombination begründet die Methodenwahl auf einen Blick und ist stärker als eine Zahlentabelle. Drei Einschränkungen:

1. Das Balkendiagramm zeigt nichts Neues: Bei `qcut` sind gleich hohe Balken per Definition zu erwarten, dieselbe Information liefert `value_counts().sort_index()`. Aussagekräftiger wäre ein Boxplot von `price_per_hp` pro Kategorie, der zeigt, welche Wertebereiche hinter den Klassen stecken.
2. Stil: Der Dozent nutzt `plt.subplot(...)` und `plt.title(...)`. Empfohlen ist `fig, ax = plt.subplots(1, 2, ...)` mit `ax[0].set_title(...)` usw. (siehe „Grundgerüst“), damit klar ist, auf welche Achse sich ein Befehl bezieht; bei Seaborn dann `ax=ax[0]` übergeben.
3. An der Prüfung kosten Grafiken Zeit. Ohne verlangte Visualisierung reicht `value_counts()` als Kontrolle; das Histogramm lohnt sich, wenn die Wahl von `qcut` statt `cut` begründet werden soll.

Die eigene Lösung ergänzt etwas, das die Grafiken nicht zeigen: die konkreten Autos einer Klasse (`.loc[... == 'very expensive']`).

### One-Hot-Encoding (W4 II, S. 28–29)

```python
df = pd.get_dummies(df, columns=['treibstoff'], drop_first=False)
df[df.filter(like='treibstoff').columns] = df.filter(like='treibstoff').astype(int)
```

**Warum:** ML-Algorithmen rechnen mit Zahlen. Würde man Kategorien einfach durchnummerieren (1, 2, 3), unterstellt das Modell eine **Rangordnung**, die bei nominalen Daten nicht existiert. One-Hot vermeidet das, indem jede Kategorie eine eigene 0/1-Spalte bekommt.

**Nachteil (S. 29):** Viele Kategorien führen zu vielen Spalten und dünn besetzten Daten (Curse of Dimensionality).

#### Schritt für Schritt: `pd.cut` und One-Hot-Encoding (Apartment-Notebook)

```python
df['price_per_m2_cat'] = pd.cut(df['price_per_m2'], bins=5,
    labels=['very cheap', 'cheap', 'normal', 'expensive', 'very expensive'])

try:
    df = pd.get_dummies(df, columns=['price_per_m2_cat'], drop_first=False)
except:
    print("Dummy variables already exist")

df[df.filter(like='price_per_m2_cat').columns] = df.filter(like='price_per_m2_cat').astype(int)
```

1. **`pd.cut(bins=5)`**: 5 **gleich breite** Intervalle zwischen Min und Max, nicht gleich viele Wohnungen pro Klasse. Bei schiefen Daten landen die meisten unten.
2. **`pd.get_dummies`**: aus einer Spalte mit 5 Kategorien werden 5 Spalten `price_per_m2_cat_<Kategorie>`, pro Zeile genau eine `True`. Die Originalspalte wird **entfernt**.
3. **`drop_first=False`**: alle 5 Spalten bleiben. Mit `True` fällt die erste weg, weil sie aus den anderen folgt (Dummy-Falle bei Regression).
4. **`try`/`except`**: beim zweiten Ausführen gibt es die Originalspalte nicht mehr, der Fehler wird abgefangen.
5. **`df.filter(like=...)`**: wählt alle Spalten, deren Name den Text **enthält**. `.columns` liefert die Namen, `.astype(int)` macht aus `True`/`False` `1`/`0`, die Zuweisung schreibt zurück.

Kategorien als 1–5 zu codieren würde Abstände vortäuschen („normal“ = 3 × „very cheap“). One-Hot macht jede Kategorie zu einem eigenen Ja/Nein-Merkmal.

### Skalieren (W4 II, S. 31)

```python
# Min-Max von Hand: Ergebnis zwischen 0 und 1
df['area_mm'] = (df['area'] - df['area'].min()) / (df['area'].max() - df['area'].min())

# mit scikit-learn über mehrere Spalten
from sklearn.preprocessing import MinMaxScaler, StandardScaler
spalten = ['area', 'rooms', 'preis']
df[spalten] = MinMaxScaler().fit_transform(df[spalten])
```

| Verfahren | Ergebnis | Wann |
| --- | --- | --- |
| **Min-Max** | Werte zwischen 0 und 1 | Wertebereich soll begrenzt sein; empfindlich gegenüber Ausreissern |
| **Standardisierung** (z-Transformation) | Mittelwert 0, Standardabweichung 1 | bei annähernd normalverteilten Daten, empfindlich gegenüber Ausreissern (Mittelwert und Standardabweichung werden verzerrt) |

**Wann überhaupt:** Nur bei Verfahren, die mit Abständen oder Gewichten rechnen. Bäume und Random Forests brauchen keine Skalierung.

**Fallstrick:** Den Scaler nur auf den **Trainingsdaten** fitten, sonst fliesst Information aus den Testdaten ins Modell (Data Leakage). Am sichersten mit `make_pipeline`.

#### Die vier Skalierungsmethoden im Detail (Apartment-Notebook)

Alle vier sind **linear**: Sie verschieben und stauchen, die **Form** der Verteilung bleibt gleich. Im Histogramm ändert sich nur die x-Achse.

```python
s = df['area']
df['area_scaled_minmax']  = (s - s.min()) / (s.max() - s.min())
df['area_scaled_max_abs'] = s / s.abs().max()
df['area_scaled_robust']  = (s - s.median()) / (s.quantile(0.75) - s.quantile(0.25))
df['area_scaled_z']       = (s - s.mean()) / s.std()
```

|  | Min-Max | Max-Abs | Robust | Z-Score |
| --- | --- | --- | --- | --- |
| Formel | (x − min) / (max − min) | x / max(\|x\|) | (x − Median) / IQR | (x − Mean) / Std |
| Verschiebung | ja (min) | nein | ja (Median) | ja (Mean) |
| Wertebereich | \[0, 1\] | \[−1, 1\] | unbeschränkt | unbeschränkt |
| Wird zu 0 | min | 0 bleibt 0 | Median | Mittelwert |
| Vorzeichen bleibt | nein | ja | nein | nein |
| Ausreisserempfindlich | ja | ja | **nein** | ja |
| Typischer Einsatz | fester Bereich nötig | negative Werte, viele Nullen | Daten mit Ausreissern | annähernd symmetrische Daten, viele ML-Verfahren |

**Min-Max und Max-Abs** (angenommen min = 20, max = 1620):

| area | Min-Max | Max-Abs |
| --- | --- | --- |
| 20 | 0 | 0.012 |
| 100 | 0.05 | 0.062 |
| 1620 | 1 | 1 |

Bei `area` liegt fast alles bei 0–0.15, weil ein Ausreisser (\~1600 m²) das Maximum bestimmt.

**Robust und Z-Score am Mini-Datensatz** `[60, 70, 80, 100, 400]` (Median 80, IQR 30; Mittelwert 142, Std ≈ 145):

| area | − Median | Robust | Z-Score |
| --- | --- | --- | --- |
| 60 | −20 | −0.67 | −0.57 |
| 70 | −10 | −0.33 | −0.50 |
| 80 | 0 | 0 | −0.43 |
| 100 | 20 | 0.67 | −0.29 |
| 400 | 320 | **10.67** | **1.78** |

Der Median wird zu 0, weil er von sich selbst abgezogen wird. Danach zeigt das Vorzeichen die Richtung, der Betrag den Abstand in IQRs. Beim Z-Score zieht der Ausreisser Mittelwert und Std nach oben und wirkt dadurch unauffällig; sogar 100 m² liegen „unter dem Durchschnitt“.

**Robust heisst nicht, dass Ausreisser verschwinden**: Sie bestimmen nur nicht mehr die Skalierung der übrigen Werte. Und trotz des Namens macht Z-Score-„Normalization“ die Daten **nicht** normalverteilt.

### Weitere String-Methoden

Alle arbeiten vektorisiert über den `.str`-Accessor und kommen mit `NaN` zurecht, ohne einen Fehler zu werfen.

**Stolperstein: `.str` vor jeder String-Methode** (Car-Notebook)

```python
df['type'] = df['type'].str.upper().strip()       # AttributeError: 'Series' object has no attribute 'strip'
df['type'] = df['type'].str.upper().str.strip()   # korrekt
```

`.str.upper()` gibt wieder eine **Series** zurück, keinen einzelnen String. Eine Series kennt `strip()` nicht direkt; erst der `.str`-Accessor wendet die String-Methode auf jedes Element an. Bei Ketten deshalb vor **jeder** String-Methode erneut `.str` schreiben.

```python
df['code'].str.strip().str.lower()
df['code'].str.removeprefix('PROD_')     # nur wenn es wirklich am Anfang steht
df['code'].str.removesuffix('_alt')

# in mehrere Spalten zerlegen
teile = df['code'].str.split('_', expand=True)
teile.columns = ['kategorie', 'nummer']

# Spalten zu einem String verbinden
df['id'] = df['kategorie'].str.cat(df['nummer'], sep='-')
```

**Benannte Capture-Groups** sparen das nachträgliche Umbenennen — die Gruppennamen werden direkt zu Spaltennamen:

```python
muster = r'(?P<jahr>\d{4})-(?P<monat>\d{2})'
df[['jahr', 'monat']] = df['datum_raw'].str.extract(muster)
```

`r'...'` (Raw String) verhindert, dass Python die Backslashes vorher interpretiert — bei Regex immer verwenden.

#### Übungen: Textlänge, Teilmengen, Dummy, Zeitstempel (Apartment-Notebook)

**Textlängen als Histogramm lesen** (`.str.len()`): auf Lage, Form und Auffälligkeiten achten. `description_raw` liegt meist bei 20–70 Zeichen und ist leicht rechtsschief. `text_raw` liegt meist bei 600–720 und ist linksschief, mit einer abgetrennten Gruppe bei \~100–150 Zeichen. Bei gescrapten Daten kann das Standardtext, abgeschnittene Seiten oder fehlende Beschreibung sein; prüfen statt raten.

```python
small = df[df['text_raw_len'] < 200]              # boolescher Filter
len(small)                                         # wie viele Zeilen?
print(small['text_raw'].iloc[0])                   # einen Text vollständig lesen
pd.set_option('display.max_colwidth', None)        # Zellen nicht abschneiden
pd.set_option('display.max_columns', None)         # alle Spalten zeigen
```

**Textlänge: eigene Lösung vs. Dozent (Car-Notebook, `type`)**

```python
# eigene Lösung
df['type_len'] = df['type'].str.len()
df[['type', 'type_len']].head(10)

# Dozent
df['type_len'] = df['type'].apply(len)
df[['type', 'type_len']].head()

plt.figure(figsize=(7, 4))
sns.histplot(df['type_len'], bins=25, kde=True)
plt.title("Histogram of variable 'type_len'")
plt.xlabel('Type length')
plt.ylabel('Frequency')
plt.show()
```

|  | `.str.len()` | `.apply(len)` |
| --- | --- | --- |
| Was passiert | pandas-String-Methode, auf jedes Element angewendet | ruft die Python-Funktion `len` für jedes Element auf |
| Bei `NaN` | liefert `NaN`, kein Fehler | `TypeError`, weil `NaN` ein Float ohne Länge ist |
| Ergebnis bei sauberen Strings | identisch | identisch |

`.apply()` ist allgemeiner: Es wendet **jede** Funktion auf jedes Element an, auch eigene. Für Strings ist `.str.len()` die robustere Wahl. Hier sind die `NaN` bereits entfernt, deshalb funktionieren beide.

Zusätzlich zeigt der Dozent die Verteilung als Histogramm mit `sns.histplot(..., kde=True)`; `kde=True` legt eine geglättete Dichtekurve über die Balken. Interpretation: Die meisten Typbezeichnungen sind 30–60 Zeichen lang, der Gipfel liegt bei rund 40, einzelne Ausreisser reichen bis über 120 Zeichen. (Der Kommentar „use .appy()“ im Dozenten-Code ist ein Tippfehler für `.apply()`.)

**Dummy-Variable aus Textsuche**

```python
pattern = 'LOFT|SEESICHT|PENTHOUSE|LUXUS'
df['luxurious'] = df['description_raw'].str.contains(pat=pattern).astype(int)
```

`str.contains` liefert `True`/`False`, `.astype(int)` macht daraus `1`/`0` für Modelle. Das Muster in Grossbuchstaben funktioniert nur, weil die Texte vorher mit `.str.upper()` umgewandelt wurden; sonst `case=False` setzen.

**Zeitstempel**

```python
df['datetime'] = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
```

Hält den Zeitpunkt der **Ausführung** fest, nicht des Scrapings; deshalb haben alle Zeilen denselben Wert. Für Analysen (z. B. Preisänderungen über mehrere Scraping-Durchgänge) zählt der Scraping-Zeitpunkt. `strftime` macht einen **String**; für Sortieren, Filtern und Zeitdifferenzen besser den Typ `datetime64` behalten (zurück mit `pd.to_datetime()`).

### Weitere Optionen bei fehlenden Werten und Duplikaten

```python
df['x'] = df['x'].ffill()        # letzten bekannten Wert nach unten fortschreiben
df['x'] = df['x'].bfill()        # nächsten bekannten Wert nach oben ziehen

df.drop_duplicates(subset=['id'], keep='first')   # erstes Vorkommen behalten
df.drop_duplicates(subset=['id'], keep='last')    # letztes behalten
df.drop_duplicates(subset=['id'], keep=False)     # alle Duplikate entfernen
```

**Gruppenweise imputieren**, wenn das Fehlen von einer anderen Variablen abhängt (MAR):

```python
df['preis'] = df.groupby('quartier')['preis'].transform(lambda x: x.fillna(x.median()))
```

**Niemals `== np.nan` schreiben** — der Vergleich ist immer `False`. Nur `isna()` und `notna()` funktionieren. Das ist dieselbe Logik wie `IS NULL` in SQL.

### Transformationen bei schiefen Verteilungen (W4 II)

Schiefe Variablen lassen sich symmetrischer machen. Das ist ein eigenes Lernziel neben dem Skalieren.

```python
import numpy as np
from scipy import stats

df['preis_log']  = np.log1p(df['preis'])      # ln(1 + x), funktioniert auch bei x = 0
df['preis_sqrt'] = np.sqrt(df['preis'])

# Box-Cox: sucht das beste Lambda selbst, braucht strikt positive Werte
werte, lam = stats.boxcox(df['preis'].dropna())
print('Lambda:', round(lam, 4))
```

| Verfahren | Voraussetzung | Wirkung |
| --- | --- | --- |
| Logarithmus (`np.log1p`) | Werte ≥ 0 | dämpft lange rechte Ausläufer stark |
| Wurzel (`np.sqrt`) | Werte ≥ 0 | dämpft schwächer als der Logarithmus |
| Box-Cox | Werte > 0 | wählt die Stärke der Dämpfung selbst |
| Yeo-Johnson | beliebig, auch negativ | wie Box-Cox, ohne Positivitätsbedingung |

Kontrolle: `df['preis'].skew()` vor und nach der Transformation vergleichen. Eine Transformation verändert die **Daten**; eine logarithmische Achse (`ax.set_xscale('log')`) verändert nur die **Darstellung**. Die beiden nicht verwechseln.

#### Log, Wurzel und Box-Cox im Detail (Apartment-Notebook)

Anders als Scaling sind diese Transformationen **nicht-linear**: Sie verändern die **Form** der Verteilung und reduzieren Schiefe. Grosse Werte werden stärker gestaucht als kleine.

```python
df['area_log']  = np.log(df['area'])     # natürlicher Log, Basis e
df['area_sqrt'] = np.sqrt(df['area'])

from scipy.stats import boxcox
df['area_boxcox'], lam = boxcox(df['area'])  # gibt Daten UND lambda zurück
```

| area | log | sqrt |
| --- | --- | --- |
| 20 | 3.00 | 4.47 |
| 80 | 4.38 | 8.94 |
| 100 | 4.61 | 10 |
| 400 | 5.99 | 20 |
| 1620 | 7.39 | 40.25 |

Beim **Log** wird eine Vervierfachung immer zur gleichen Differenz (20 → 80 und 400 → 1620 je +1.39): Verhältnisse werden zu Abständen. Bei der **Wurzel** wird eine Vervierfachung zur Verdopplung, also schwächere Stauchung.

**Box-Cox** ist eine Familie mit Parameter λ, der automatisch so gewählt wird, dass die Daten möglichst normalverteilt sind:

```latex
x_{\text{boxcox}} = \begin{cases} \dfrac{x^\lambda - 1}{\lambda} & \lambda \neq 0 \\ \ln(x) & \lambda = 0 \end{cases}
```

λ = 1 ändert die Form nicht, λ = 0.5 entspricht der Wurzel, λ = 0 dem Log, λ < 0 staucht stärker als der Log. Im Notebook wird λ mit `_` verworfen; besser speichern, um zurückzurechnen oder neue Daten gleich zu transformieren.

|  | SQRT | Log | Box-Cox |
| --- | --- | --- | --- |
| Formel | √x | ln(x) | (x^λ − 1) / λ |
| Stauchung | schwach | stark | datengetrieben (λ) |
| Erlaubte Werte | x ≥ 0 | x > 0 (`log1p` bei Nullen) | x > 0 |
| Ergebnis bei `area` | noch leicht rechtsschief, Ausreisser bei \~40 | annähernd symmetrisch, Gipfel \~4.4 (≈ 80 m²) | annähernd symmetrisch, Gipfel \~6.5 |

Nach der Transformation haben die Werte keine Einheit mehr; zurück zum Log mit `np.exp()`.

### Den Merge prüfen statt hoffen

```python
df_neu = pd.merge(links, rechts, on='id', how='left',
                  validate='one_to_many',   # bricht ab, wenn 'id' links nicht eindeutig ist
                  indicator=True)           # Spalte _merge: left_only / right_only / both

print(df_neu['_merge'].value_counts())
```

`validate` kennt `'one_to_one'`, `'one_to_many'`, `'many_to_one'`. Es wirft einen `MergeError`, statt still Zeilen zu vervielfachen — der beste Schutz gegen den Fallstrick aus dem Abschnitt «Tabellen zusammenführen». `indicator=True` zeigt danach, welche Zeilen kein Gegenstück hatten.

Bei gleichnamigen Spalten auf beiden Seiten: `suffixes=('_links', '_rechts')`.

### Umformen: wide und long (W4 II)

```python
# long → wide, mit Aggregation
pivot = pd.pivot_table(df, index='filiale', columns='quartal', values='umsatz',
                       aggfunc='sum', fill_value=0, margins=True)

# wide → long
lang = pd.melt(df_wide, id_vars=['filiale'], value_vars=['Q1', 'Q2'],
               var_name='quartal', value_name='umsatz')

# Indexebenen verschieben
df.stack()      # Spalten in den Zeilenindex
df.unstack()    # Zeilenindex in die Spalten
```

| Form | Aufbau | Gut für |
| --- | --- | --- |
| **wide** | eine Zeile je Objekt, viele Messwertspalten | Tabellen zum Lesen |
| **long (tidy)** | eine Zeile je Beobachtung, Spalten `variable` und `value` | Analysen und seaborn |

`pivot()` ohne Aggregation braucht eindeutige Index-Spalten-Kombinationen; `pivot_table()` fasst Duplikate über `aggfunc` zusammen und ist deshalb der robustere Weg. `margins=True` ergänzt Zeilen- und Spaltensummen, `fill_value=0` ersetzt leere Kombinationen.

#### Reshaping im Apartment-Notebook

**`stack` / `unstack`**

```python
df_sub = df3[['bfs_name', 'rooms', 'price', 'area']][:5]   # 4 Spalten, erste 5 Zeilen
df_sub_stacked = df_sub.stack()     # breit → lang
df_sub_stacked.unstack()            # zurück zur Originalform
```

`stack` schiebt die **Spaltennamen** als innere Ebene in den Index. Aus einer Zeile mit 4 Spalten werden 4 Zeilen; Ergebnis ist eine **Series mit MultiIndex** (Zeilenindex, Spaltenname). Weil Text und Zahlen in einer Spalte landen, wird der Datentyp `object`. `unstack` holt die innerste Indexebene wieder als Spalten nach oben. Typisch nach `groupby` über zwei Spalten: `df.groupby(['bfs_name', 'rooms'])['price'].mean().unstack()` ergibt eine Tabelle Gemeinde × Zimmerzahl.

**Achtung, pandas-Version:** Ob `stack()` fehlende Werte behält, hängt von der Version ab.

```python
pd.__version__   # aktive pandas-Version anzeigen
```

| Version | `stack()` mit `NaN` | nach `unstack()` |
| --- | --- | --- |
| pandas 3 (Codespace, erkennbar am Datentyp `str`) | `NaN` bleiben erhalten | Originalform wieder hergestellt |
| vor pandas 3.0 | `NaN` werden standardmässig weggelassen | Zeilen, in denen alle Werte fehlen, verschwinden ganz |

Läuft an der Prüfung eine andere Version, kann sich das Ergebnis deshalb unterscheiden.

**`melt`**

```python
pd.melt(df_sub, id_vars=['rooms'], value_vars=['price', 'area'])
```

`id_vars` bleiben und werden pro Zeile wiederholt, `value_vars` werden untereinander gestapelt. Neue Spalten: `variable` (ehemaliger Spaltenname) und `value`. Gleiches Ziel wie `stack`, aber Ergebnis ist ein normaler DataFrame ohne MultiIndex. Achtung im Notebook: Dort steht `pd.melt(df, …)` statt `df_sub`, deshalb 1722 Zeilen (861 × 2) statt 10.

**`pivot_table`**

```python
pivot_table = pd.pivot_table(df3[['rooms', 'price', 'price_per_m2', 'area']],
                             index=['rooms'],
                             values={'price': np.mean,
                                     'price_per_m2': np.mean,
                                     'area': np.mean}).round(2)
pivot_table = pivot_table.map(lambda x: f"{x:.2f}" if isinstance(x, (int, float)) else x)
```

Eine Zeile pro Zimmerzahl, jede Spalte mit der angegebenen Funktion verdichtet (entspricht `df3.groupby('rooms')[[...]].mean()`). `.map(lambda …)` formatiert jede Zahl als **String** mit genau 2 Nachkommastellen; nur für die Anzeige, danach kann man nicht mehr rechnen. Mittelwerte reagieren auf Ausreisser: Bei 6 Zimmern liegt die mittlere Fläche bei 667.67 m².

**Stolperstein: `values` vs. `aggfunc`** (Car-Notebook)

| Parameter | Frage |
| --- | --- |
| `values` | **Welche** Spalten werden verdichtet? (Liste) |
| `aggfunc` | **Wie** werden sie verdichtet? (mean, count, sum …) |

Steht ein Dictionary bei `values`, nutzt pandas nur die **Schlüssel** und ignoriert die Funktionen, ohne Fehlermeldung. Gerechnet wird mit dem Standard von `aggfunc`, und der ist `mean`. Deshalb wirkt das Apartment-Beispiel oben korrekt, obwohl `np.mean` dort keine Wirkung hat; ein `count` würde dort einfach verschluckt. Korrigiert:

```python
pivot_table = pd.pivot_table(df3[['fuel_type', 'price', 'hp', 'price_per_hp']],
                             index=['fuel_type'],
                             values=['price', 'price_per_hp', 'hp'],
                             aggfunc={'price': ['count', 'mean'],
                                      'price_per_hp': 'mean',
                                      'hp': 'mean'}).round(2)
```

Mit einer Liste wie `['count', 'mean']` entstehen pro Spalte mehrere Unterspalten (MultiIndex in den Spaltenüberschriften).

**Interpretation:** `count` neben den Mittelwerten zeigt die Gruppengrösse. Benzin (2648) und Diesel (1175) sind gut belegt, mehrere Gruppen haben nur 1 bis 5 Autos. Ein Mittelwert aus einem einzigen Auto ist nur dessen Wert und nicht aussagekräftig. Zudem enthält `fuel_type` Getriebe-Werte (z. B. „Automat“, „Schaltgetriebe“) und `transmission` Antriebe („Allrad“): Beim Scraping sind Werte in die falsche Spalte gerutscht, vermutlich weil der Scraper Felder nach ihrer Position liest und bei fehlenden Angaben alles nachrückt. Vor einer Analyse also Kategorien mit `value_counts()` prüfen.

Hinweis: Die `.map(lambda …)`-Formatierung macht auch aus Anzahlen `1.00`; für `count` wäre eine ganze Zahl sauberer.

|  | `melt` | `stack` / `unstack` | `pivot_table` |
| --- | --- | --- | --- |
| Richtung | breit → lang | Spalten ↔ Index | lang → breit mit Aggregation |
| Aggregiert? | nein | nein | ja (mean, sum, count …) |
| Zeilenzahl | wächst | wächst / schrumpft | schrumpft auf Anzahl Gruppen |
| Typischer Einsatz | Daten für Plots oder Modelle umformen | MultiIndex umbauen, z. B. nach `groupby` | Kennzahlen- und Übersichtstabellen |

Faustregel: Nur die **Form** ändern → `melt` oder `stack`/`unstack`. **Zusammenfassen** → `pivot_table`.

## EDA (Woche 5)

Quelle: Foliensatz Woche 5 (Gellrich, HS2026), Foliennummern in Klammern.

### Systematik: vier Felder (F. 7)

Jede EDA-Frage lässt sich in dieses Raster einordnen. In Teil A lohnt es sich, die Einordnung explizit zu benennen.

|  | **Non-Graphical** | **Graphical** |
| --- | --- | --- |
| **Univariat** (eine Variable) | Mittelwert, Median, Standardabweichung, Schiefe | Histogramm, Boxplot, Balkendiagramm |
| **Multivariat** (mehrere Variablen) | Kontingenztabelle, Korrelation, Kovarianz | Streudiagramm, Streudiagramm-Matrix, Korrelationsplot |

Merksatz aus den Lernzielen: Kennzahlen sollen **immer** durch Grafiken ergänzt werden. Gleiche Mittelwerte und Standardabweichungen können völlig verschiedene Verteilungen verbergen.

**Anscombes Quartett** ist das Standardbeispiel dazu (Anscombe 1973, zitiert in den Folien der Woche 5): Vier Datensätze mit praktisch identischem Mittelwert, identischer Varianz, identischer Korrelation (0.816) und identischer Regressionsgerade — aber völlig verschiedenen Mustern. Einer ist linear, einer gekrümmt, einer linear mit einem Ausreisser, einer besteht fast nur aus einem einzigen x-Wert. Wer nur die Kennzahlen betrachtet, sieht keinen Unterschied.

Daraus folgt die Prüfungsantwort: Kennzahlen können die Struktur von Daten nicht vollständig beschreiben, deshalb gehört zu jeder Kennzahl eine Grafik.

**Quantile genauer:** Zwischen zwei Datenpunkten wird standardmässig linear interpoliert.

```python
s = pd.Series([10, 20, 30, 40])
s.quantile(0.25)                           # 17.5 (Standard: linear)
s.quantile(0.25, interpolation='lower')    # 10
s.quantile(0.25, interpolation='higher')   # 20
s.quantile(0.25, interpolation='midpoint') # 15
```

Rechenweg: Position = q × (n − 1) = 0.25 × 3 = 0.75, also zwischen dem ersten Wert (10) und dem zweiten (20): 10 + 0.75 × 10 = 17.5.

Der Parameter heisst `interpolation`, **nicht** `method`. Und Quantile laufen von 0 bis 1, Perzentile von 0 bis 100 — `quantile(0.25)`, aber `np.percentile(arr, 25)`.

### Schnelleinstieg in einen neuen Datensatz

```python
df.shape          # (Zeilen, Spalten)
df.info()         # Datentypen + Anzahl Nicht-NULL je Spalte
df.head()
df.describe()                  # nur numerische Spalten
df.describe(include='all')     # auch kategoriale Spalten
df.isna().sum()                # fehlende Werte je Spalte
```

`describe()` liefert count, mean, std, min, 25 %, 50 %, 75 %, max. Achtung: `count` zählt die **Nicht-fehlenden** Werte — eine Differenz zu `df.shape[0]` zeigt sofort Lücken an.

### Lagemasse (measures of central tendency)

```python
df['var'].mean()        # Mittelwert – empfindlich gegenüber Ausreissern
df['var'].median()      # Median – robust
df['var'].mode()        # Modus – gibt eine Series zurück (mehrere möglich)
```

Welches Mass passt: Der Median ist robust gegenüber Ausreissern und darum bei schiefen Verteilungen (Mieten, Preise, Einkommen) der bessere Repräsentant. Der Modus ist das einzige Lagemass für **nominale** Daten.

### Streuungsmasse (measures of dispersion) (F. 17)

```python
df['var'].var()                     # Stichprobenvarianz s²
df['var'].std()                     # Stichproben-Standardabweichung s
df['var'].max() - df['var'].min()   # Spannweite
df['var'].quantile([0.25, 0.75])    # Quartile
```

IQR und Ausreissergrenzen, die auch dem Boxplot zugrunde liegen:

```python
q1, q3 = df['var'].quantile([0.25, 0.75])
iqr = q3 - q1
unten, oben = q1 - 1.5 * iqr, q3 + 1.5 * iqr
```

**Fallstrick:** pandas rechnet standardmässig mit `ddof=1` (Stichprobe, Nenner n−1), NumPy dagegen mit `ddof=0` (Population, Nenner n). `df.std()` und `np.std(df)` liefern deshalb unterschiedliche Werte.

Kontrollbeispiel aus den Folien: `[1,2,3,4,5,5,42]` ergibt `var()` = 215,81 und `std()` = 14,69.

### Schiefe und Kurtosis (F. 18–20)

```python
df['var'].skew()        # Schiefe
df['var'].kurtosis()    # Exzess-Kurtosis
```

| Wert | Bedeutung |
| --- | --- |
| `skew() > 0` | rechtsschief, langer Ausläufer nach rechts, Mittelwert > Median |
| `skew() = 0` | symmetrisch |
| `skew() < 0` | linksschief, Mittelwert < Median |

**Faustregel (F. 19):** Mittelwert mit Median vergleichen. Liegt der Mittelwert höher, ist die Verteilung rechtsschief. Das ist in Teil A oft die erwartete Begründung — mit den konkreten Zahlen des Datensatzes.

Kurtosis beschreibt die **Ausläufer**, nicht die Höhe des Gipfels. pandas liefert die **Exzess**-Kurtosis nach Fisher: Normalverteilung = 0, positiv = schwerere Ausläufer, negativ = leichtere (F. 20).

Kontrollbeispiele aus den Folien: `[1,2,3,4,5,5,42]` → `skew()` = 2,588; `[-6,…,6]` → `kurtosis()` = −1,2.

Weiterführend (Abbildung + Erklärung): [Difference between Skewness and Kurtosis – GeeksforGeeks](https://www.geeksforgeeks.org/data-science/difference-between-skewness-and-kurtosis/)

### Kategoriale Variablen und Kontingenztabellen

```python
df['kat'].value_counts()                   # absolute Häufigkeiten
df['kat'].value_counts(normalize=True)     # relative Anteile
df['kat'].nunique()

pd.crosstab(df['kat_a'], df['kat_b'])                  # Kontingenztabelle
pd.crosstab(df['kat_a'], df['kat_b'], normalize='index')
```

Eine **Kontingenztabelle** zählt die gemeinsamen Häufigkeiten zweier kategorialer Variablen und zeigt, ob sich die Verteilung der einen je nach Ausprägung der anderen verschiebt.

**Fallstrick:** `value_counts()` lässt NaN standardmässig weg. Mit `dropna=False` werden fehlende Werte mitgezählt — nützlich, um Lücken zu entdecken.

### Korrelation und Kovarianz

```python
df['a'].corr(df['b'])              # Pearson (Standard)
df['a'].corr(df['b'], method='spearman')
df.corr(numeric_only=True)         # Korrelationsmatrix
df['a'].cov(df['b'])
```

|  | Kovarianz | Korrelation |
| --- | --- | --- |
| Wertebereich | unbegrenzt | −1 bis +1 |
| Einheit | Produkt beider Einheiten | einheitenlos |
| Vergleichbar | nein | ja |

Die Korrelation ist die normierte Kovarianz und deshalb zwischen Variablenpaaren vergleichbar.

**Pearson oder Spearman:** Pearson misst den **linearen** Zusammenhang und setzt metrische Daten voraus. Spearman rechnet auf Rängen, erfasst jeden **monotonen** Zusammenhang und eignet sich für ordinale Daten oder bei Ausreissern.

**Drei Fallstricke, die in Teil A und B regelmässig geprüft werden:**

- Korrelation ist **kein** Kausalzusammenhang. Eine dritte Variable kann beides treiben.
- Pearson nahe 0 schliesst einen Zusammenhang **nicht** aus — ein u-förmiger Zusammenhang ist stark, aber nicht linear. Deshalb immer ein Streudiagramm dazu.
- `df.corr()` ignoriert nicht-numerische Spalten stillschweigend. Prüfen, ob eine erwartete Spalte fehlt, weil sie fälschlich als `object` eingelesen wurde.

### Grafische EDA: welche Grafik wofür (W5, S. 29 ff.)

| Frage | Grafik |
| --- | --- |
| Wie ist **eine** numerische Variable verteilt? | Histogramm |
| Lage, Streuung, Ausreisser einer Variablen? | Boxplot |
| Verteilung **pro Gruppe** vergleichen? | Boxplot oder Violinplot nach Gruppe |
| Häufigkeit einer **kategorialen** Variablen? | Balkendiagramm / Countplot |
| Anteile an einem Ganzen? | Kreisdiagramm (nur bei wenigen Kategorien) |
| Ist eine Variable normalverteilt? | QQ-Plot |
| Zusammenhang **zweier** numerischer Variablen? | Streudiagramm |
| Zusammenhang bei sehr vielen Punkten? | Hexbin-Plot |
| Alle Paare auf einmal? | Streudiagramm-Matrix (`pairplot`) |
| Korrelationen als Überblick? | Heatmap |

### Grundgerüst (objektorientiert)

Immer `fig, ax = plt.subplots()` verwenden, nicht `plt.hist(...)` direkt. Damit sind Achsenbeschriftung und Titel eindeutig zuzuordnen — und fehlende Labels kosten in der Bewertung Punkte.

```python
import matplotlib.pyplot as plt
import seaborn as sns
sns.set_theme(style='whitegrid')

fig, ax = plt.subplots(figsize=(8, 4))
# ... zeichnen ...
ax.set_xlabel('...')
ax.set_ylabel('...')
ax.set_title('...')
plt.tight_layout()
plt.show()
```

**`fig` und `ax` auseinanderhalten:**

| Objekt | Rolle | Zuständig für |
| --- | --- | --- |
| `fig` (Figure) | die ganze Abbildung | Grösse, Speichern, Gesamtüberschrift |
| `ax` (Axes) | die Zeichenfläche mit x- und y-Achse | Daten, Labels, Titel, Achsengrenzen |

Deshalb `ax.set_xlabel(...)` statt `plt.xlabel(...)`. Beides funktioniert, aber `plt.` wirkt immer auf «die gerade aktive Achse» und wird mehrdeutig, sobald mehrere Subplots im Spiel sind.

### Histogramm, mit Mittelwert und Median

```python
fig, ax = plt.subplots(figsize=(8, 4))
ax.hist(df['power_kw'].dropna(), bins=40, color='steelblue', edgecolor='white')
ax.axvline(df['power_kw'].mean(), color='orange', linestyle='--', label='Mean')
ax.axvline(df['power_kw'].median(), color='tomato', label='Median')
ax.set_xlabel('Power in kW'); ax.set_ylabel('Frequency')
ax.set_title('Distribution of Power in kW')
ax.legend()
plt.tight_layout(); plt.show()
```

Die beiden Linien machen die Schiefe sofort sichtbar: Liegt der Mittelwert rechts vom Median, ist die Verteilung rechtsschief.

### Boxplot nach Gruppe

```python
# matplotlib: Daten je Gruppe als Liste vorbereiten
gruppen = sorted(df['power_type'].unique())
daten = [df[df['power_type'] == g]['power_kw'].dropna().values for g in gruppen]

fig, ax = plt.subplots(figsize=(10, 5))
ax.boxplot(daten, tick_labels=[str(g) for g in gruppen], patch_artist=True,
           boxprops=dict(facecolor='steelblue', alpha=0.6))

# seaborn: kürzer, nimmt den DataFrame direkt
sns.boxplot(data=df, x='power_kw', y='power_type', order=gruppen, ax=ax)
```

Die Datenaufbereitung in der ersten Zeile ist eine **List Comprehension**: Für jede Gruppe `g` wird gefiltert (`df[df['power_type'] == g]`), die Zielspalte gewählt, `dropna()` angewendet und mit `.values` in ein NumPy-Array umgewandelt. Ergebnis ist eine Liste von Arrays — eine Position entspricht einer Box.

**Zwei Parameter, die oft vergessen gehen:**

- `patch_artist=True` schaltet die Füllung überhaupt erst frei. Ohne ihn ignoriert matplotlib `facecolor` vollständig und die Boxen bleiben weiss.
- Der Parameter für die Achsenbeschriftung heisst seit matplotlib 3.9 `tick_labels=`; in älteren Versionen hiess er `labels=`. Bei einer Fehlermeldung `matplotlib.__version__` prüfen.

**Aufbau eines Boxplots:**

```
      ○        Ausreisser (ausserhalb der Whisker)
      │
    ─────      oberer Whisker: grösster Wert innerhalb Q3 + 1.5 × IQR
      │
   ┌─────┐     Q3   (75. Perzentil)
   │     │
   ├─────┤     Median (50. Perzentil)
   │     │
   └─────┘     Q1   (25. Perzentil)
      │
    ─────      unterer Whisker: kleinster Wert innerhalb Q1 − 1.5 × IQR
```

Die Box umfasst die mittleren 50 % der Daten, ihre Höhe ist der IQR. Der Median ist robust gegen Ausreisser, deshalb liegt er nicht zwingend in der Mitte der Box — eine aussermittige Linie zeigt bereits Schiefe an.

### Violinplot

```python
sns.violinplot(data=df, x='power_kw', y='power_type', order=gruppen, cut=0, ax=ax)
```

Der Violinplot **ergänzt** den Boxplot, er ersetzt ihn nicht: Er zeigt die Dichte der Verteilung, die dunkle Mitte enthält weiterhin Median und IQR. Eine zweite Häufung, die im Boxplot wie Ausreisser aussieht, wird hier als eigene Gruppe erkennbar. `cut=0` verhindert, dass die Kurve über den Wertebereich hinausgezeichnet wird.

### Balkendiagramm und Countplot

```python
# Top-10 nach Anzahl eindeutiger Stationen
top10 = (df.groupby('city')['station_name'].nunique()
           .sort_values(ascending=False).head(10))

fig, ax = plt.subplots(figsize=(8, 4))
ax.barh(top10.index.astype(str), top10.values, color='steelblue', edgecolor='white')
ax.yaxis.set_inverted(True)      # grösster Wert oben

# seaborn, direkt aus den Rohdaten gezählt
sns.countplot(data=df, x='plug_type', order=df['plug_type'].value_counts().index, ax=ax)
ax.tick_params(axis='x', labelrotation=25)
```

**Fallstrick:** `value_counts()` zählt **Zeilen**, `nunique()` zählt **verschiedene Werte**. Bei mehreren Ladepunkten pro Station sind das zwei verschiedene Fragen — im Achsentitel benennen, was tatsächlich gezählt wurde.

### Kreisdiagramm mit Restkategorie

```python
anteile = df['plug_type'].value_counts()
top4 = anteile.head(4).copy()
rest = anteile.iloc[4:].sum()
if rest > 0:
    top4.loc['Other'] = rest

fig, ax = plt.subplots(figsize=(7, 7))
ax.pie(top4.values, labels=top4.index, autopct='%1.1f%%', startangle=90)
ax.axis('equal')
```

### QQ-Plot

```python
import scipy.stats as stats

fig, ax = plt.subplots(figsize=(6, 6))
stats.probplot(df['power_kw'].dropna(), dist='norm', plot=ax)
ax.set_title('QQ Plot — Power in kW')
```

**Lesen:** Die Gerade zeigt, wo die Punkte bei Normalverteilung lägen. Jeder Punkt vergleicht einen Datenwert mit dem Wert, den eine Normalverteilung an dieser Position erwarten würde. Abweichungen oben rechts bedeuten einen längeren rechten Ausläufer. Treppenstufen entstehen bei **diskreten** Daten mit wenigen festen Stufen.

### Streudiagramm

```python
# matplotlib: Schleife über die Gruppen
for typ, gruppe in df.groupby('power_type'):
    ax.scatter(gruppe['voltage'], gruppe['amperage'], alpha=0.3, s=20, label=typ)
ax.legend(title='power_type')

# seaborn: hue und size übernehmen das
sns.scatterplot(data=df, x='voltage', y='amperage', hue='power_type',
                size='power_kw', sizes=(20, 200), alpha=0.6, ax=ax)
```

`alpha` ist wichtig, sobald sich Punkte überlagern — sonst verbirgt ein scheinbar einzelner Punkt Hunderte identischer Werte.

### Streudiagramm-Matrix

```python
num_cols = ['power_kw', 'amperage', 'voltage']
g = sns.pairplot(df[num_cols + ['power_type']].dropna(), hue='power_type',
                 diag_kind='hist', plot_kws={'alpha': 0.4, 's': 15})
g.figure.suptitle('Scatter Plot Matrix', y=1.02)
```

**Lesen:** Diagonale = Verteilung der einzelnen Variablen. Ausserhalb = Streudiagramm zweier Variablen, Zeile bestimmt die y-Achse, Spalte die x-Achse. Die Matrix ist symmetrisch, eine Hälfte genügt. Bei vielen Zeilen vorher `sample(500, random_state=42)` ziehen.

### Hexbin

```python
df_xy = df[['amperage', 'voltage']].dropna()
hb = ax.hexbin(df_xy['amperage'], df_xy['voltage'], gridsize=30,
               bins='log', cmap='Blues', mincnt=1)
plt.colorbar(hb, ax=ax, label='Count (log scale)')
```

`dropna()` auf dem **Teil-DataFrame**, nicht je Spalte einzeln — sonst können die beiden Reihen unterschiedlich lang werden.

### Korrelations-Heatmap

```python
corr = df[num_cols].corr(method='pearson')
mask = np.triu(np.ones_like(corr, dtype=bool))   # nur untere Hälfte zeigen

fig, ax = plt.subplots(figsize=(5, 4))
sns.heatmap(corr, mask=mask, annot=True, fmt='.2f', cmap='RdBu_r',
            center=0, vmin=-1, vmax=1, linewidths=0.5, ax=ax)
ax.grid(False)
```

`center=0` mit `vmin=-1, vmax=1` sorgt dafür, dass die Farbe das Vorzeichen korrekt abbildet.

### Mehrere Grafiken in einer Figur

```python
fig, ax = plt.subplots(2, 2, figsize=(14, 8))

ax[0, 0].hist(...)          # Zeile 0, Spalte 0
ax[0, 1].boxplot(...)
ax[1, 0].barh(...)
ax[1, 1].scatter(...)

ax[0, 0].set_title('...'); ax[0, 0].set_xlabel('...'); ax[0, 0].set_ylabel('...')
plt.tight_layout(); plt.show()
```

### Vier Fallstricke bei Grafiken

- **KDE bei diskreten Daten:** `kde=True` legt eine glatte Kurve über Werte, die nur wenige feste Stufen kennen, und täuscht so einen Verlauf vor. Bei konstanten Spalten oder einer Gruppe mit einem einzigen Datenpunkt ist die Streuung 0 — dann zeichnet seaborn gar keine Kurve. Für solche Variablen ist `diag_kind='hist'` ehrlicher.
- **Heatmap zeigt keine Struktur:** Sie bildet nur Kennzahlen ab. Ein Streudiagramm kann daneben zeigen, dass der scheinbar starke Zusammenhang aus zwei Punktwolken besteht. Deshalb Heatmap immer mit Streudiagrammen kombinieren.
- **Konstante Spalten:** Eine Spalte mit nur einem Wert hat Standardabweichung 0, ihre Korrelation ist `NaN`. Solche Spalten vor `corr()` aussortieren.
- **Unsinnige Korrelationen:** Koordinaten wie `lat` und `lon` lassen sich inhaltlich nicht als Korrelation deuten. Nur Spalten in die Matrix nehmen, deren Zusammenhang eine Bedeutung hat.

### Interpretieren: Aufbau einer Antwort

In Teil A wird nicht die Definition bewertet, sondern die Begründung am Datensatz. Ein tragfähiges Muster:

1. **Befund mit Zahl**: Die Verteilung von `power_kw` ist rechtsschief (Skewness 3.00).
2. **Beleg**: Der Mittelwert (50.50) liegt deutlich über dem Median (22.00), das Maximum beträgt 400.
3. **Erklärung in der Sache**: Die meisten Ladepunkte sind AC mit 22 kW, einzelne DC-Schnelllader reichen bis 400 kW.
4. **Konsequenz**: Als typischer Wert eignet sich deshalb der Median, nicht der Mittelwert.

Immer die **Spaltennamen** nennen. Eine Antwort ohne Bezug zu den vorliegenden Daten wird nicht gewertet.

### Verteilung beschreiben

```python
df['power_kw'].skew()        #  3.002 → rechtsschief
df['power_kw'].kurtosis()    #  8.947 → leptokurtisch
```

**Faustregel über Mittelwert und Median**, mit Toleranz, damit kleine Abweichungen nicht überinterpretiert werden:

```python
mean, median, std = df[col].mean(), df[col].median(), df[col].std()
ratio = abs(mean - median) / std
# ratio < 0.1  → annähernd symmetrisch
# mean > median → rechtsschief, sonst linksschief
```

**Pearsons zweiter Schiefekoeffizient** als Zahl für dieselbe Faustregel:

```python
3 * (mean - median) / std      # power_kw: 1.11 → deutlich rechtsschief
```

**Kurtosis** (pandas liefert die Exzess-Kurtosis, Normalverteilung = 0):

| Wert | Bezeichnung | Bedeutung |
| --- | --- | --- |
| > 0 | leptokurtisch | schwerere Ausläufer, mehr Extremwerte als bei Normalverteilung |
| = 0 | mesokurtisch | wie Normalverteilung |
| < 0 | platykurtisch | leichtere Ausläufer, weniger Extremwerte |

Formulierung: «Die Exzess-Kurtosis von 8.95 ist deutlich grösser als 0. Die Verteilung ist leptokurtisch, es gibt mehr Extremwerte als eine Normalverteilung erwarten lässt — hier die Schnelllader.»

### Scheinbare Widersprüche auflösen

Ein IQR von 0 bei gleichzeitig grosser Standardabweichung wirkt widersprüchlich, ist es aber nicht:

```python
df['power_kw'].quantile([0.25, 0.75])   # beide 22.0 → IQR = 0
df['power_kw'].std()                     # 77.31
```

**Erklärung:** Der IQR beschreibt nur die mittleren 50 % der Werte. Liegen davon fast alle auf demselben Wert, ist er 0. Die Standardabweichung dagegen berücksichtigt **alle** Werte, auch die weit entfernten. Beide Masse sind korrekt, sie beantworten verschiedene Fragen. Genau deshalb ergänzen sich robuste und nicht-robuste Masse.

Dasselbe Prinzip bei einem Sprung zwischen Perzentilen: Der Sprung von 22 (75 %) auf 225 (95 %) zeigt, dass die oberen Werte nicht gleichmässig streuen, sondern eine eigene Gruppe bilden.

### Plausibilität prüfen, bevor etwas als Fehler gilt

Ein extremer Wert ist nicht automatisch falsch. Prüfe ihn gegen eine **fachliche Regel**:

```python
# Leistung = Spannung × Stromstärke
400 * 563   # = 225'200 W ≈ 225 kW → der Wert ist technisch stimmig
230 * 16    # =   3'680 W ≈   4 kW → ebenfalls stimmig
```

Weitere Prüfungen dieser Art: Koordinaten gegen den geografischen Rahmen halten (Schweiz liegt rund um 46.8 / 8.2), Datumsangaben gegen den Erhebungszeitraum, Preise gegen bekannte Grössenordnungen.

**Formulierung, wenn die Werte stimmig sind, aber etwas anderes auffällt:** «Die technischen Werte sind in sich konsistent (400 V × 125 A = 50 kW) und entsprechen einem DC-Ladepunkt. Unpassend ist nur der Steckertyp. Am wahrscheinlichsten ist ein Fehler in `plug_type`; aus den Daten allein lässt sich das nicht abschliessend klären. Der Datensatz wird deshalb behalten und die Auffälligkeit dokumentiert.»

Das ist die erwartete Haltung: nicht vorschnell löschen, sondern prüfen, begründen und die Unsicherheit benennen.

### Kontingenztabelle lesen

```python
pd.crosstab(df['power_type'], df['plug_type'], normalize='index')
```

Mit `normalize='index'` ergibt **jede Zeile** zusammen 100 %. Lesart: «Von allen Ladepunkten dieses `power_type` haben X % diesen Stecker.» Mit `normalize='columns'` dreht sich die Blickrichtung um, mit `normalize='all'` beziehen sich alle Werte auf die Gesamtzahl.

**Fallstrick:** Prozentwerte bei sehr kleinen Gruppen sind nicht aussagekräftig. Eine Zeile mit 100 % kann auf einer einzigen Beobachtung beruhen. Deshalb immer zusätzlich die **absoluten** Häufigkeiten ansehen (`margins=True`) und bei n = 1 ausdrücklich darauf hinweisen.

### Kovarianz und Korrelation lesen

**Kovarianz** zeigt die **Richtung** eines Zusammenhangs, nicht seine vergleichbare Stärke: Ihr Wert hängt von den Einheiten ab. Eine Variable in CHF erzeugt grosse Kovarianzen, ohne dass der Zusammenhang stärker wäre. Die **Korrelation** ist die normierte Kovarianz und deshalb zwischen Variablenpaaren vergleichbar — ein Paar mit kleinerer Kovarianz kann die höhere Korrelation haben.

Leseregeln für beide Matrizen:

- **Diagonale**: Jede Variable mit sich selbst, bei der Korrelation immer 1.
- **Symmetrisch**: Eine Hälfte genügt, deshalb die Maske in der Heatmap.
- **Vorzeichen**: Richtung des linearen Zusammenhangs.
- **Betrag** (nur Korrelation, −1 bis +1): gängige Faustregel — unter 0.3 schwach, 0.3 bis 0.7 mittel, über 0.7 stark.

Formulierung: «Der stärkste Zusammenhang besteht zwischen `amperage` und `power_kw` (r = 0.997). Das ist zu erwarten, weil Leistung = Spannung × Stromstärke gilt — beide Variablen tragen praktisch dieselbe Information.»

Dieser Hinweis gehört dazu: Zwei fast perfekt korrelierte Merkmale sind **redundant**. Für ein Modell wäre es sinnvoll, nur eines davon zu verwenden.

### Was die KDE-Linie zeigt — und wann sie täuscht

KDE steht für Kernel Density Estimation: Um jeden Datenpunkt wird eine kleine Glockenkurve gelegt, alle werden aufsummiert. Wo viele Punkte nahe beieinanderliegen, entsteht ein Gipfel. Die **Bandbreite** der Glocken wird aus der Streuung der Daten berechnet; in `histplot` wird die Kurve so skaliert, dass ihre Fläche zur Anzahl Datenpunkte passt.

Daraus folgen zwei Beobachtungen, die gute Prüfungsantworten ergeben:

- **Sehr hohe, schmale Spitze**: Viele identische Werte bei kleiner Streuung ergeben eine schmale Bandbreite. Die gesamte Fläche konzentriert sich auf einen engen Bereich und muss darum hoch sein — kein Fehler, sondern eine Folge der Skalierung.
- **Gar keine Kurve**: Bei Streuung 0 (eine konstante Spalte oder eine Gruppe mit nur einem Datenpunkt) ist die Bandbreite 0, und seaborn lässt die Kurve weg.

**Grundsatz:** Die KDE setzt **stetige** Daten voraus. Bei diskreten Variablen mit wenigen festen Stufen täuscht die glatte Kurve einen Verlauf vor, den es nicht gibt. Dort ist das Histogramm allein aussagekräftiger.

### Befunde zusammenführen

Die stärkste Antwort zeigt, dass mehrere Methoden zum selben Ergebnis führen. Beispiel `power_kw`:

| Methode | Befund |
| --- | --- |
| Kennzahlen | Mittelwert 50.50 > Median 22.00, Skewness 3.00 |
| Histogramm | Masse links bei 22, langer Ausläufer nach rechts |
| Boxplot nach Gruppe | AC konzentriert bei 22 kW, DC breit gestreut bis 400 kW |
| QQ-Plot | Punkte weichen rechts oben nach oben ab, Treppenstufen durch diskrete Werte |

Gemeinsame Deutung: Die vielen AC-Ladepunkte bilden den Gipfel, die wenigen DC-Schnelllader den rechten Ausläufer. Das erklärt Rechtsschiefe und hohe Kurtosis zugleich. Genau das ist der Zweck der grafischen EDA — sie bestätigt und ergänzt die Kennzahlen.

## Machine Learning: Formeln (Woche 6, Supervised Learning)

Quelle: Foliensatz Woche 6 (Gellrich, HS2026), Foliennummern in Klammern.

### Training und Evaluation

- **Trainingsfehler** = (1/n) · Σ L(yᵢ, ŷᵢ). Der Trainingsfehler ist zu optimistisch, deshalb wird auf Testdaten oder per CV bewertet. (F. 11)
- **Quadratischer Verlust** L = (y − ŷ)², **0-1-Verlust** L = 1 bei falscher Klasse, sonst 0. (F. 11)
- **Kreuzvalidierung**: CV₍ₖ₎ = (1/k) · Σⱼ MSEⱼ, also der Mittelwert der k Validierungsfehler. (F. 15)
- **Bias-Varianz**: erwarteter Testfehler = Bias² + Varianz + Rauschen (gilt für quadratischen Verlust). (F. 17)

### Lineare Regression

- **Modell**: y = β₀ + β₁x₁ + … + βₚxₚ + ε. «Linear» heisst linear in β. (F. 19)
- **OLS-Ziel**: RSS = Σ (yᵢ − (β₀ + β₁xᵢ))² → min. (F. 20)
- **OLS-Lösung**: β̂₁ = Σ(xᵢ − x̄)(yᵢ − ȳ) / Σ(xᵢ − x̄)², β̂₀ = ȳ − β̂₁ · x̄. Die Gerade geht durch (x̄, ȳ). (F. 20)
- **Interpretation**: β̂ⱼ = Änderung von E\[y\] bei +1 in xⱼ, übrige Prädiktoren konstant. Das ist ein Zusammenhang, kein Kausaleffekt. β̂₀ liegt oft ausserhalb der Daten und hat dann keine Bedeutung. (F. 21, 25)
- **Beispiel**: Miete = 166,79 + 30,84 · Fläche → 95 m² ergibt 3096,59 CHF. (F. 21)
- **Streuungszerlegung**: SST = SSR + SSE, mit SST = Σ(yᵢ − ȳ)², SSR = Σ(ŷᵢ − ȳ)², SSE = Σ(yᵢ − ŷᵢ)². (F. 22)
- **R²** = 1 − SSE / SST, der Anteil erklärter Streuung (0 = nichts, 1 = perfekt). Beispiel: SSE 20, SST 100 → 0,8. (F. 22)
- **RMSE** = √((1/n) · Σ (yᵢ − ŷᵢ)²), der typische Fehler in Einheiten von y. Beispiel: Residuen 10, 5, 2, 3, 4 → √30,8 = 5,55. (F. 22)
- **KI vs. PI**: Das KI gilt für die durchschnittliche Miete aller 95-m²-Wohnungen, das PI für eine einzelne neue Wohnung. Das PI ist immer breiter. (F. 23)
- **Gradientenabstieg**: β\_neu = β\_alt − η · (Steigung des Verlusts). (F. 27)

#### Modell, Koeffizienten und Fehlerterm

Quelle: ML Basics 02, `linear_regression_concept.ipynb`, Block 1.

```latex
y = \beta_0 + \beta_1 x + \varepsilon \qquad \hat y = \hat\beta_0 + \hat\beta_1 x
```

| Zeichen | Name | Bedeutung |
| --- | --- | --- |
| β₀ | Beta null | Intercept: Wert von ŷ bei x = 0 |
| β₁ | Beta eins | Steigung: Veränderung von ŷ pro Einheit x |
| ε | Epsilon | Fehlerterm: alles, was y beeinflusst, aber nicht im Modell ist (Lage, Baujahr, Zufall …); unbekannt |
| e | Residuum | geschätzte Version von ε: beobachtet minus vorhergesagt |
| ^ (z. B. ŷ, β̂₁) | «Hut» | geschätzt bzw. vorhergesagt |

**Warum «im Durchschnitt»:** Jede Wohnung weicht durch ihr eigenes ε von der Geraden ab. OLS schätzt die Steigung über alle Wohnungen, und die Abweichungen gleichen sich im Mittel aus (Residuen summieren sich bei OLS mit Intercept zu 0). Deshalb gilt «Steigung 20 = +20 CHF pro m²» nur im Durchschnitt, nicht exakt für jede einzelne Wohnung.

**Intercept interpretieren:** Im Beispiel ŷ = 400 + 20 · x bedeutet β₀ = 400 wörtlich «eine Wohnung mit 0 m² kostet 400 CHF». Das ist unsinnig: 0 m² gibt es nicht, und der Wert liegt weit ausserhalb der Daten (Extrapolation). Der Intercept wird trotzdem gebraucht, weil er die Höhe der Geraden festlegt; inhaltlich interpretiert wird er nicht.

**Wann der Intercept sinnvoll ist:** wenn x = 0 realistisch ist und im Bereich der Daten liegt, z. B. bei einer Grundgebühr.

- Taxi: Preis = 6 CHF + 4 CHF · km → Intercept 6 CHF = Grundtaxe bei 0 km, Steigung 4 CHF = Preis pro km
- Weitere: Handyabo (Grundgebühr + Preis pro Minute), Strom (Grundpreis + Preis pro kWh)
- Kein Intercept-Fall: «bis zu einer Menge gratis, danach kostenpflichtig» ergibt einen Knick, den eine einzelne Gerade nicht abbildet.

#### SSE, SST und R²

Quelle: ML Basics 02, `linear_regression_concept.ipynb`, Block 3.

```latex
\mathrm{SSE}=\sum(y_i-\hat y_i)^2 \qquad \mathrm{SST}=\sum(y_i-\bar y)^2 \qquad R^2 = 1-\frac{\mathrm{SSE}}{\mathrm{SST}}
```

| Grösse | Name | Abstand zu | Bedeutung |
| --- | --- | --- | --- |
| SSE | Sum of Squared Errors | Vorhersage ŷ des Modells | Fehler des Modells; wird von OLS minimiert |
| SST | Total Sum of Squares | Mittelwert ȳ | Fehler ohne Modell (immer den Mittelwert vorhersagen) = gesamte Streuung von y |
| R² | Bestimmtheitsmass | – | um wie viel das Modell den quadrierten Fehler gegenüber dem Mittelwert reduziert |

**Beispiel:** y = 3, 5, 7 (ȳ = 5), ŷ = 4, 5, 6 → SSE = 1 + 0 + 1 = 2, SST = 4 + 0 + 4 = 8, R² = 1 − 2/8 = 0.75.

**Grenzfälle:** SSE = 0 → R² = 1 (perfekt) · SSE = SST → R² = 0 (nicht besser als der Mittelwert) · SSE > SST → R² < 0 (schlechter als der Mittelwert, nur auf Testdaten möglich).

**Warum Training-R² bei OLS mit Intercept nie negativ ist:**

1. OLS darf auch die flache Gerade wählen (β₁ = 0, β₀ = ȳ). Sie sagt immer den Mittelwert voraus, also SSE = SST und R² = 0.
2. OLS wählt die Gerade mit dem kleinsten SSE, also eine bessere oder im schlimmsten Fall genau diese.
3. Daraus folgt SSE ≤ SST und damit R² ≥ 0.

**Warum Test-R² negativ sein kann:** Die Gerade wird auf den Trainingsdaten optimiert und auf den Testdaten nicht neu angepasst; SST wird dort mit dem Mittelwert der Testdaten berechnet. Passt die Trainingsgerade schlecht, wird SSE > SST. Gleiche Logik wie Training- vs. Test-Error: Auf bekannten Daten sieht ein Modell immer mindestens so gut aus wie auf neuen.

#### Normalverteilung, OLS und Gradient Descent

Quelle: ML Basics 02, `linear_regression_concept.ipynb`, Block 5 und 6.

**Warum OLS keine Normalverteilung braucht:** OLS minimiert die Summe der quadrierten Fehler (SSE). Dafür braucht es nur die Datenpunkte und die Formel, also reine Rechnung. Die Normalverteilung der Fehler wird erst für Aussagen über Unsicherheit gebraucht: p-Werte, t/F-Tests und Intervalle (exakt bei kleinen Stichproben).

| Verfahren | Vorgehen |
| --- | --- |
| OLS | berechnet das Minimum der SSE direkt per Formel, in einem Schritt |
| Gradient Descent | nähert sich dem Minimum der Loss-Kurve bzw. -Fläche iterativ, Schritt für Schritt |
| Maximum Likelihood | wählt die Parameter, unter denen die beobachteten Daten am plausibelsten sind (Beispiel 7× Kopf, 3× Zahl: L(p) = p⁷(1−p)³ ist bei p = 0.7 am grössten) |

Bei unabhängigen, normalverteilten Fehlern mit konstanter Varianz liefern Maximum Likelihood und OLS dieselbe Gerade.

**Gradient Descent lesen (Demo: Loss = (b − 3)², Start b = 0, Lernrate 0.2):**

```python
gradient = 2 * (b - 3)      # Steigung der Kurve an der aktuellen Stelle
b = b - 0.2 * gradient      # Schritt entgegen der Steigung (bergab)
```

| Schritt | b vorher | Gradient 2·(b−3) | Schritt −0.2·Gradient | b nachher |
| --- | --- | --- | --- | --- |
| 1 | 0 | −6.0 | +1.2 | 1.2 |
| 2 | 1.2 | −3.6 | +0.72 | 1.92 |
| 3 | 1.92 | −2.16 | +0.43 | 2.35 |

- Blaue Kurve = Loss in Abhängigkeit von b; Minimum bei b = 3. Rote Punkte = Position von b nach jedem Schritt.
- **Warum die Schritte kleiner werden:** Die Lernrate bleibt 0.2, aber der Gradient schrumpft, je näher b am Minimum ist (Kurve wird flacher). Schritt = Lernrate × Gradient.
- **Zu grosse Lernrate** (z. B. 1.1): b springt über das Minimum hinaus und entfernt sich immer weiter (overshoot).
- **Stochastic Gradient Descent:** pro Schritt nur eine Beobachtung oder ein kleiner Batch.
- **Bezug zur Regression:** Loss = SSE, gesucht sind β₀ und β₁. Gleiches Prinzip, auf der Loss-Fläche bergab; OLS kommt per Formel direkt zum gleichen Ergebnis.

#### Multiple Regression: ceteris paribus und Multikollinearität

Quelle: ML Basics 02, `linear_regression_exercise.ipynb`, Aufgabe 5; Concept Block 1 und 5.

```python
multiple = smf.ols("price ~ area + rooms", data=train).fit()
print(multiple.params.round(2))
print(train[['area', 'rooms']].corr().round(2))
```

| Modell | Intercept | area | rooms | Training R² |
| --- | --- | --- | --- | --- |
| simple (`price ~ area`) | 1248.20 | 13.87 | – | 0.368 |
| multiple (`price ~ area + rooms`) | 1294.87 | 15.48 | −54.42 | 0.369 |

Korrelation area–rooms: 0.86.

**Ceteris paribus:** Im multiplen Modell gilt jeder Koeffizient «unter sonst gleichen Bedingungen». area 15.48 = +15.48 CHF pro m² **bei gleicher Zimmerzahl**; im simplen Modell galt 13.87 ohne Rücksicht auf die Zimmerzahl.

**Negativer rooms-Koeffizient:** Bedeutet nicht «mehr Zimmer = billiger», sondern: **bei gleicher Fläche** ein Zimmer mehr. Beispiel: 90 m² mit 3 vs. 4 Zimmern → die 4-Zimmer-Wohnung hat kleinere Zimmer und ist im Durchschnitt 54 CHF günstiger. Solche Vergleichspaare sind selten, weil Fläche und Zimmer fast immer zusammen steigen; der Koeffizient ist deshalb unsicher.

**Multikollinearität:**

- Verletzt ist die Annahme nur bei **perfekter** Multikollinearität (ein Input bestimmt den anderen exakt).
- Bei starker Korrelation (hier 0.86) werden die **einzelnen Koeffizienten unsicher**: Das Modell kann schlecht trennen, welcher Teil der Miete auf area und welcher auf rooms entfällt. Deshalb verschiebt sich area (13.87 → 15.48) und rooms wird negativ.
- Die **Vorhersagen** können trotzdem brauchbar sein. Gemeinsam verwenden ist erlaubt; VIF misst das Problem (Berechnung nicht verlangt).
- R² steigt kaum (0.368 → 0.369), weil rooms fast dieselbe Information enthält wie area.

**Interpretation (Vorschlag):**

> Area: 15.48, Rooms: −54.42. Each additional m² is now associated with CHF 15.48 more monthly rent on average, holding the number of rooms constant (ceteris paribus). The negative rooms coefficient does not mean that more rooms make an apartment cheaper: for the same area, one more room means smaller rooms, which is associated with CHF 54 less rent on average.
>
> Area and rooms are strongly correlated (0.86), so the model can hardly separate their effects. The individual coefficients are therefore uncertain, which also explains why the area coefficient changes from 13.87 to 15.48. Adding rooms barely improves the training R² (0.368 → 0.369), because rooms adds little information beyond area.

#### Residuen, Residual-Plot und Q–Q-Plot

Quelle: ML Basics 02, `linear_regression_exercise.ipynb`, Aufgabe 6; Concept Block 5.

```python
plt.scatter(simple.fittedvalues, simple.resid, alpha=0.4)
plt.axhline(0, color='black')
sm.qqplot(simple.resid, line='s')
```

**Residuum:** e = y − ŷ = tatsächliche minus vorhergesagte Miete. Im Scatterplot (Fläche vs. Miete) ist es der senkrechte Abstand eines Punktes zur Regressionsgeraden.

- e positiv: Punkt über der Geraden, Modell hat die Miete **unterschätzt**
- e negativ: Punkt unter der Geraden, Modell hat sie **überschätzt**

**Welche Linie ist was:**

| Plot | Linie | Bedeutung |
| --- | --- | --- |
| Scatterplot Fläche vs. Miete (Aufgabe 3) | rot | Regressionsgerade ŷ = 1248.20 + 13.87 · area |
| Residual-Plot (Aufgabe 6) | schwarz | Nulllinie (e = 0) = die waagrecht «gekippte» Regressionsgerade |
| Q–Q-Plot (Aufgabe 6) | rot | Referenz für eine perfekte Normalverteilung; nichts mit der Regressionsgeraden zu tun |

**Residual-Plot lesen** (x = vorhergesagte Miete ŷ, y = Residuum):

| Muster | Bedeutung | Verletzte Annahme |
| --- | --- | --- |
| gleichmässiges Band um 0, ohne Struktur | alles in Ordnung | – |
| Kurve (z. B. aussen über 0, Mitte darunter) | Gerade passt systematisch nicht | Linearität |
| Trichter (Streuung wird breiter oder schmaler) | Fehler sind nicht überall gleich gross | gleiche Varianz |

Ausserdem auf **Symmetrie** achten: Reichen die Residuen nach oben gleich weit wie nach unten?

**Q–Q-Plot lesen:** Liegen die Punkte auf der roten Linie, sind die Residuen ungefähr normalverteilt. Abweichungen an den Enden zeigen schiefe Verteilungen oder schwere Ränder: Punkte rechts oben über der Linie = mehr grosse positive Residuen als erwartet (rechtsschief).

**Was ein Plot nicht kann:** Unabhängigkeit lässt sich weder mit dem Q–Q-Plot noch mit dem Residual-Plot nachweisen; sie wird über die Datenerhebung (und eine allfällige zeitliche Reihenfolge) beurteilt. Ein Plot kann Probleme andeuten, aber keine Annahme beweisen.

**Befund im Apartment-Modell (`price ~ area`):**

- Keine klare Kurve → Linearität plausibel; die Gerade beschreibt den Durchschnittstrend vernünftig.
- **Kein starker Trichter** (Musterlösung): Die Streuung ist über die vorhergesagten Mieten ungefähr ähnlich (etwa −1500 bis +2800 CHF). Achtung: Links *scheint* die Streuung kleiner, aber das ist teilweise ein **Artefakt des Preisfilters** (1000–5000 CHF). Bei ŷ = 1500 CHF kann das Residuum nicht unter −500 fallen, weil Mieten unter 1000 CHF entfernt wurden.
- **Hauptbefund = Schiefe:** Positive Residuen reichen bis ca. +2800, negative nur bis ca. −1500. Einige Wohnungen sind viel teurer, als ihre Fläche erwarten lässt, aber wenige viel billiger.
- Q–Q-Plot: beide Enden liegen über der roten Linie → rechtsschief, Fehler nicht normalverteilt. Für die OLS-Berechnung kein Problem; betrifft nur exakte p-Werte und Intervalle.
- Unabhängigkeit: mögliche Verletzung z. B. durch Wohnungen in **derselben Gemeinde oder im selben Gebäude**, die sich ähnlich sind.

#### Tipps aus der Musterlösung (Linear Regression)

Quelle: ML Basics 02, `linear_regression_solution.ipynb`.

**Aufgabe 1, OLS von Hand** (x = 40, 60, 80; y = 1200, 1600, 2000; x̄ = 60, ȳ = 1600):

- Zähler: (−20)(−400) + 0 · 0 + 20 · 400 = 16 000
- Nenner: 400 + 0 + 400 = 800
- Steigung 16 000 / 800 = 20; Intercept 1600 − 20 · 60 = 400

**Aufgaben 3 und 5, Koeffizienten mit Beispielen greifbar machen:**

- simple: 100 m² → 1248.20 + 13.87 · 100 = 2635 CHF; 50 m² → 1942 CHF
- multiple (ceteris paribus in Zahlen): zwei 3.5-Zimmer-Wohnungen, eine 10 m² grösser → 10 · 15.48 = 154.80 CHF Unterschied

**Aufgabe 4, Intervalle quantifizieren:** Konfidenzintervall 2513–2620 CHF (± 53), Prognoseintervall 1319–3814 CHF (± 1248), also etwa **23-mal breiter**. Das Konfidenzintervall ist schmal, weil 571 Wohnungen die Gerade gut bestimmen; einzelne Wohnungen streuen stark um den Durchschnitt.

**Aufgabe 7, RMSE einordnen:**

- RMSE 705.5 CHF = typischer Vorhersagefehler für eine neue Wohnung von etwa 700 CHF/Monat.
- **Baseline:** Für jede Wohnung die Durchschnittsmiete vorhersagen ergibt einen Fehler nahe der Standardabweichung (ca. 800 CHF, aus `describe()`). Gleiche Idee wie in Ordner 01 (2.91 vs. 1.85 L/100 km).
- Ein RMSE ist **keine Fehlergrenze** für jede einzelne Wohnung; einzelne können viel weiter danebenliegen.
- Test-R² < Training-R² (0.312 vs. 0.368) ist bei neuen Daten zu erwarten.

#### Regressionsbaum: Split berechnen (Schritt für Schritt)

Quelle: ML Basics 03, `regression_trees_ensembles_concept.ipynb`, Block 1; Übung Aufgabe 1. Zielwerte: 10, 12, 14, 30, 34.

**1. Ausgangssituation (Parent Node, vor dem Split)**

```latex
\bar{y} = \frac{10 + 12 + 14 + 30 + 34}{5} = \frac{100}{5} = 20
```

```latex
\text{Parent SSE} = (-10)^2 + (-8)^2 + (-6)^2 + 10^2 + 14^2 = 100 + 64 + 36 + 100 + 196 = 496
```

**2. Split nach 14** (`left = [10, 12, 14]`, `right = [30, 34]`)

- Linkes Blatt: Mittelwert (10 + 12 + 14) / 3 = **12**; SSE (−2)² + 0² + 2² = 4 + 0 + 4 = **8**
- Rechtes Blatt: Mittelwert (30 + 34) / 2 = **32**; SSE (−2)² + 2² = 4 + 4 = **8**
- Code-Ausgabe: `Predictions: 12.0 32.0`, `Total split SSE: 16.0`

**3. Alternativer Split nach 12** (`alternative_left = [10, 12]`, `alternative_right = [14, 30, 34]`)

- Linkes Blatt: Mittelwert (10 + 12) / 2 = **11**; SSE (−1)² + 1² = **2**
- Rechtes Blatt: Mittelwert 78 / 3 = **26**; SSE (−12)² + 4² + 8² = 144 + 16 + 64 = **224**
- Code-Ausgabe: `Alternative split SSE: 226.0`

**Fazit**

| Split | Vorhersagen | SSE |
| --- | --- | --- |
| kein Split (Parent) | 20 | 496 |
| nach 10 | 10 und 22.5 | 371 |
| nach 12 | 11 und 26 | 226 |
| nach 14 | 12 und 32 | **16** |
| nach 30 | 16.5 und 34 | 251 |

Der Baum prüft alle möglichen Trennpunkte und wählt den mit der kleinsten SSE (**greedy**): den Split nach 14, der die SSE von 496 auf 16 senkt. Die 14 gehört inhaltlich zu 10 und 12; im Split nach 12 erzeugt sie im rechten Blatt grosse Fehler. Danach wird in jedem Kind gleich weitergesplittet (**rekursiv**).

**Warum jedes Blatt den Mittelwert vorhersagt:** Der Mittelwert ist der einzelne Wert mit der kleinsten SSE innerhalb eines Blatts. Für (10, 12, 14): Vorhersage 12 → SSE 8; Vorhersage 11 → 1 + 1 + 9 = 11; Vorhersage 13 → 9 + 1 + 1 = 11. Da der Baum Splits nach SSE bewertet, ist der Mittelwert die beste konstante Vorhersage.

#### Regressionsbaum lesen (`plot_tree`)

Quelle: ML Basics 03, `regression_trees_ensembles_exercise.ipynb`, Aufgaben 2 und 3.

**Datensatz:** gleicher Auto-Datensatz und gleicher Split wie in Ordner 01 (560 Training, 141 Test), damit die Modelle vergleichbar sind (lineare Regression: Test-RMSE 1.85). Target y = `combined`: kombinierter Verbrauch Stadt/Autobahn (gewichteter Mittelwert, typische gemischte Fahrweise) in L/100 km; tiefer = sparsamer. Inputs X = `engine_size`, `cylinders`.

```python
tree = DecisionTreeRegressor(max_depth=2, random_state=42)
tree.fit(X_train, y_train)
plot_tree(tree, feature_names=list(X.columns), filled=True, rounded=True, precision=2)
```

| Angabe im Knoten | Bedeutung |
| --- | --- |
| `engine_size <= 2.6` | Frage/Split: True → links, False → rechts (nur in inneren Knoten) |
| `squared_error` | mittlerer quadrierter Fehler um den Knotenmittelwert (Streuung im Knoten) |
| `samples` | Anzahl Trainingszeilen, die diesen Knoten erreichen |
| `value` | Mittelwert des Targets dieser Zeilen; im Blatt = Vorhersage |
| Farbe (`filled=True`) | je dunkler, desto höher `value` |

**Beispiel 2.0 L, 4 Zylinder:** 2.0 ≤ 2.6? Ja → links · 2.0 ≤ 1.9? Nein → rechts · Blatt `value = 8.95`, `samples = 224` → Vorhersage 8.95 L/100 km (= Mittelwert der 224 Trainingsautos mit 1.9–2.6 L).

| Blatt | Hubraum | Autos | Vorhersage \[L/100 km\] |
| --- | --- | --- | --- |
| 1 | ≤ 1.9 L | 41 | 7.71 |
| 2 | 1.9–2.6 L | 224 | 8.95 |
| 3 | 2.6–3.65 L | 178 | 11.73 |
| 4 | > 3.65 L | 117 | 14.34 |

**Warum `cylinders` nie vorkommt:** An jedem Knoten prüft der Baum alle Inputs und Schwellen und wählt den Split mit der kleinsten SSE (greedy). Ein Schnitt bei `engine_size` war jedes Mal besser. Hubraum und Zylinder sind stark korreliert; kennt man den Hubraum, liefern Zylinder kaum zusätzliche Information (gleiches Muster wie area/rooms in Ordner 02). Mit `max_depth=2` gibt es nur 3 Splits; ein tieferer Baum könnte `cylinders` weiter unten noch nutzen.

**Interpretation (Vorschlag):**

> The car with 2.0 L engine size and 4 cylinders is predicted to use 8.95 L/100 km. At the root, 2.0 ≤ 2.6 is true, so we go left; at the next node, 2.0 ≤ 1.9 is false, so we go right. This leaf contains 224 training cars with engine sizes between 1.9 and 2.6 L; their mean consumption of 8.95 L/100 km is the prediction.
>
> All splits use engine size; cylinders never appear in this depth-2 tree. Because engine size and cylinders are strongly correlated, cylinders add little information once engine size is known.

#### Ensembles: Bagging, Random Forest, Boosting und OOB

Quelle: ML Basics 03, `regression_trees_ensembles_concept.ipynb`, Block 3–5; Übung Aufgabe 5.

```python
bagging = BaggingRegressor(n_estimators=50, random_state=42)
forest = RandomForestRegressor(n_estimators=100, max_features=1,
                               oob_score=True, random_state=42)
boosting = GradientBoostingRegressor(n_estimators=100, max_depth=2,
                                     learning_rate=0.1, random_state=42)
print('Forest OOB R²:', round(forest.oob_score_, 3))
```

|  | Bagging / Forest | Boosting |
| --- | --- | --- |
| Aufbau | unabhängig, parallel | nacheinander |
| Jeder Baum lernt | eine Bootstrap-Stichprobe der Daten | die Residuen des bisherigen Modells |
| Kombination | Mittelwert aller Bäume | Summe kleiner Korrekturen (× Lernrate) |
| Wirkung | reduziert vor allem Varianz | reduziert systematischen Fehler schrittweise (kann Bias und Varianz beeinflussen) |

- **Bootstrap:** Trainingszeilen **mit Zurücklegen** ziehen; manche kommen mehrfach vor, andere fehlen.
- **Random Forest = Bagging + zufällige Feature-Auswahl pro Split** (`max_features=1`: nur ein zufälliger Input pro Split). Zweck: Bäume werden unterschiedlicher, Mitteln hilft mehr. Default Regression `max_features=1.0` (alle Inputs), Klassifikation `"sqrt"`.
- **Boosting-Update:** Fₘ(x) = Fₘ₋₁(x) + ν · hₘ(x). Beispiel: aktuelle Vorhersage 7, nächster Baum sagt Residuum 3, Lernrate 0.1 → 7 + 0.1 · 3 = 7.3.

**OOB R² (Out-of-Bag):**

- Pro Baum fehlen rund 37 % der Trainingsautos in der Bootstrap-Stichprobe (= OOB-Zeilen).
- Jedes Auto wird nur von den Bäumen vorhergesagt, die es **nicht** gesehen haben.
- OOB R² = 0.69: Auf diesen «ungesehenen» Vorhersagen erklärt der Forest 69 % der Streuung im Verbrauch → Schätzung der Verallgemeinerungsfähigkeit.
- Eingebaute Validierung ähnlich wie CV, ohne Zusatzaufwand; **ersetzt den finalen Test nicht**.

**Interpretation (Vorschlag):**

> Bagging fits 50 trees independently, each on a bootstrap sample of the 560 training cars (drawn with replacement), and averages their predictions. The random forest does the same with 100 trees, but each split considers only one randomly chosen input (`max_features=1`); this makes the trees more different, so averaging helps more. Boosting fits 100 small trees (depth 2) one after another; each new tree learns the remaining residuals of the current model, scaled by the learning rate 0.1. Bagging and forests mainly reduce variance, boosting reduces systematic error step by step.
>
> For the 2.0 L, 4-cylinder car, all three predict about 8.9 L/100 km (8.91, 8.92, 8.93), close to the single tree's 8.95.
>
> OOB R² = 0.69: each car is predicted only by the trees that did not see it in their bootstrap sample. On these out-of-bag predictions, the forest explains 69% of the variation in consumption. This works like a built-in validation, but it does not replace the final test.

#### Pruning (`ccp_alpha`)

Quelle: ML Basics 03, Concept Block 2; Übung Aufgabe 4.

```latex
\text{pruning objective} = \text{tree error} + \alpha \times \text{number of leaves}
```

| alpha | Blätter | Training-RMSE \[L/100 km\] |
| --- | --- | --- |
| 0.0 | 37 | 1.43 |
| 0.05 | 8 | 1.52 |

- Jedes Blatt kostet eine «Gebühr» α. Ein Blatt lohnt sich nur, wenn es den Fehler um **mehr als α** senkt; sonst wird der Ast weggeschnitten. Bei α = 0 ist jedes Blatt gratis.
- 29 zusätzliche Blätter senken den Training-RMSE nur um 0.09 → sie beschreiben wahrscheinlich Zufälligkeiten der Trainingsautos (Noise).
- Tieferer Training-Error ≠ bessere Vorhersage für neue Autos; das zeigt nur die Validierung (CV). In Aufgabe 6 erreicht der geprunte Baum einen CV-RMSE von 1.61.

**Interpretation (Vorschlag):**

> The pruned tree (alpha = 0.05) is much easier to describe: it has 8 leaves instead of 37. Its training RMSE rises only slightly, from 1.43 to 1.52 L/100 km. So 29 of the 37 leaves reduce the training error by only 0.09 L/100 km; they probably describe random details of the training cars. Pruning removes leaves whose error reduction is smaller than the penalty alpha per leaf. A lower training error does not mean better predictions for new cars; only validation can show that (CV comparison in step 6).

#### Modellvergleich mit CV und finaler Test

Quelle: ML Basics 03, Übung Aufgabe 6.

| Modell | CV-RMSE \[L/100 km\] |
| --- | --- |
| Random Forest | **1.55** |
| Bagging | 1.56 |
| Boosting | 1.57 |
| Pruned tree | 1.61 |
| Linear | 1.73 |

- Die drei Ensembles liegen nur 0.02 auseinander → praktisch gleichwertig; alle klar besser als Pruned tree und lineare Regression.
- **Ablauf:** Auswahl nur per CV auf den Trainingsdaten (`best_name = min(cv_rmse, key=cv_rmse.get)`), ohne Blick auf die Testdaten. Erst danach wird das gewählte Modell **einmal** auf den Testdaten evaluiert: Test-RMSE 1.51.
- Einordnung des Test-RMSE (Musterlösung, siehe auch Q15): Die lineare Regression aus Ordner 01 hatte auf denselben 141 Testautos 1.85 → der Forest senkt den typischen Fehler um rund 0.34 L/100 km. Test-RMSE (1.51) und CV-RMSE (1.55) weichen leicht ab, weil der Test-RMSE eine einzelne Schätzung aus nur 141 Autos ist; beide sind Schätzungen mit Zufallsschwankung (vgl. Streuung der Fold-RMSE, Q13).

**Interpretation (Vorschlag):**

> The random forest has the lowest CV RMSE: 1.55 L/100 km. Ranking by CV RMSE: forest 1.55, bagging 1.56, boosting 1.57, pruned tree 1.61, linear regression 1.73. The three ensembles are within 0.02 L/100 km of each other, so they perform practically the same; all are clearly better than the pruned tree and the linear model. The forest is chosen based on CV on the training data only, without looking at the test rows. Only after this choice is it evaluated once on the test set, giving a final test RMSE of 1.51 L/100 km.

#### Permutation Importance

Quelle: ML Basics 03, Concept Block 4; Übung Aufgabe 7.

```python
importance = permutation_importance(forest, X_train, y_train,
                                    n_repeats=5, random_state=42)
```

- Die Werte **eines** Inputs werden zufällig durchmischt; sein Zusammenhang mit dem Target geht verloren, die anderen Inputs bleiben unverändert.
- Gemessen wird, wie stark das R² sinkt. Grösserer Verlust = Modell stützt sich stärker auf diesen Input. `n_repeats=5`: 5-mal mischen, Mittelwert.
- Ergebnis: engine\_size 0.839, cylinders 0.248.
- **Vorbehalte:** korrelierte Inputs können sich die Wichtigkeit teilen · auf Trainingsdaten berechnet → kann optimistisch sein · zeigt, was das Modell **nutzt**, nicht was den Verbrauch **verursacht** (keine Kausalität). Impurity Importance kann manche Inputs unfair bevorzugen.

**Interpretation (Vorschlag):**

> Engine size causes the much larger loss in R²: shuffling it lowers the training R² by 0.839, shuffling cylinders only by 0.248. The forest therefore relies mainly on engine size, which agrees with the small tree in step 3, where every split used engine size. Engine size and cylinders are correlated (large engines usually have more cylinders), so they can share importance; the cylinders value may partly reflect engine size. The importance is computed on training rows and can be optimistic. It shows which inputs the model uses for prediction, not what causes fuel consumption.

#### Logistische Regression: vom Score zur Wahrscheinlichkeit

Quelle: ML Basics 04, `logistic_regression_evaluation_concept.ipynb`, Block 1; Übung Aufgaben 1–3. Datensatz: Schweizer Lawinenunfälle seit 2000/01; `fatal = 1`, wenn mindestens eine Person starb.

```latex
z = \beta_0 + \beta_1 x \qquad p = P(y=1 \mid x) = \frac{1}{1+e^{-z}}
```

- **z** = linearer Score (wie bei der linearen Regression), kann jeden Wert annehmen.
- **Sigmoid** drückt z in eine Wahrscheinlichkeit zwischen 0 und 1 (S-Kurve). z = 0 → p = 0.5.
- **Positiver Koeffizient:** grösserer Input → höhere Wahrscheinlichkeit (bei sonst gleichen Inputs).
- **Fitting:** Maximum Likelihood = Log-Loss minimieren (numerischer Optimierer, `fit`).

**Sigmoid-Plot lesen** (x = linearer Score z, y = Wahrscheinlichkeit für Klasse 1):

| Score z | p | Bedeutung |
| --- | --- | --- |
| −6 | ≈ 0.00 | fast sicher Klasse 0 |
| −2 | ≈ 0.12 | eher Klasse 0 |
| 0 | 0.50 | unentschieden (Wendepunkt) |
| 1 | ≈ 0.73 | eher Klasse 1 (Beispiel Aufgabe 1) |
| 2 | ≈ 0.88 | eher Klasse 1 |
| 6 | ≈ 1.00 | fast sicher Klasse 1 |

- Kurve steigt immer (monoton): höherer Score → höhere Wahrscheinlichkeit; bleibt stets zwischen 0 und 1.
- **Symmetrisch um z = 0:** p(−z) = 1 − p(z), z. B. p(−1) ≈ 0.27.
- **Steil in der Mitte, flach an den Rändern:** Nahe z = 0 verändert eine kleine Score-Änderung p stark; bei sehr hohen oder tiefen Scores kaum noch. Deshalb steigt p nicht um einen festen Betrag pro Einheit Input.
- **Schwelle 0.5 entspricht z = 0:** positiver Score → Klasse 1, negativer → Klasse 0.

```latex
L(y,p) = -[\,y\log(p) + (1-y)\log(1-p)\,]
```

Für ein echtes Positiv (y = 1) ist p = 0.9 besser (kleiner Loss) als p = 0.1. Sicher falsche Vorhersagen werden stark bestraft.

**Aufgabe 1 von Hand:** z = 1 → e⁻¹ ≈ 0.368 → p = 1 / 1.368 ≈ **0.731** ≥ 0.5 → Klasse **1**.

```python
p = 1 / (1 + np.exp(-score))
```

**Aufgabe 2, Daten und Split:**

```python
X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, stratify=y, random_state=42)
```

- 2876 Unfälle, 13.2 % tödlich (→ **unausgeglichene Klassen**).
- `stratify=y`: Training (2300) und Test (576) behalten beide den Anteil von 13.2 %; Test enthält 76 tödliche Unfälle.
- **Zeitpunkt der Information (Block 5):** `fully_buried` ist erst **nach** dem Unfall bekannt. Das Modell sagt den Ausgang erfasster Unfälle voraus, **keine** Lawinenprognose vor einer Tour. Inputs müssen zum Zeitpunkt der Vorhersage verfügbar sein. Auch fehlende Daten und Änderungen in der Erfassung (Reporting) über die Jahre beeinflussen die Interpretation.

**Aufgabe 3, Modell und Sigmoid:**

```python
model = LogisticRegression()
model.fit(X_train, y_train)
print(model.intercept_, model.coef_)
probability = model.predict_proba(X_test)[:, 1]   # Spalte 1 = P(Klasse 1)
```

| Voll verschüttete x | Score z = −3.10 + 2.26 · x | p(tödlich) = 1 / (1 + e⁻ᶻ) |
| --- | --- | --- |
| 0 | −3.10 | 0.043 |
| 1 | −0.84 | 0.302 |
| 2 | 1.42 | 0.805 |
| 3 | 3.67 | 0.975 |

**Plot `P(fatal accident)` lesen:** gleiche S-Kurve wie im Concept, x = Anzahl Verschüttete. Sie überschreitet 0.5 bei z = 0, also bei x = 3.10 / 2.26 ≈ 1.4 Personen → bei Schwelle 0.5 wird erst ab **2** Verschütteten «tödlich» vorhergesagt. `predict_proba` liefert zwei Spalten (P(0), P(1)); `[:, 1]` = P(tödlich).

- Intercept −3.10, Steigung **2.26** (positiv) → mehr Verschüttete, höhere Wahrscheinlichkeit.
- Jede zusätzliche Person erhöht den **Score** um 2.26 und **multipliziert die Odds** mit e²·²⁶ ≈ 9.6. Die Wirkung auf p ist nicht konstant: steil zwischen 1 und 2, flach nahe 1 ab 3.
- Zusammenhang innerhalb erfasster Unfälle, **keine Kausalität**.

#### Konfusionsmatrix und Metriken

Quelle: ML Basics 04, Concept Block 2; Übung Aufgaben 4 und 5.

|  | Predicted 0 | Predicted 1 |
| --- | --- | --- |
| **Actual 0** | TN: richtig negativ | FP: Fehlalarm |
| **Actual 1** | FN: verpasster Positivfall | TP: richtig positiv |

**Lesen:** Zeilen = tatsächliche Klasse, Spalten = vorhergesagte Klasse (sklearn-Konvention). Diagonale = richtig.

| Metrik | Formel | Frage |
| --- | --- | --- |
| Accuracy | (TP + TN) / alle | Wie viele insgesamt richtig? |
| Precision | TP / (TP + FP) | Wie viele der Alarme sind echt? (Blick auf **vorhergesagte** Positive) |
| Recall (TPR) | TP / (TP + FN) | Wie viele echte Positive gefunden? (Blick auf **tatsächliche** Positive) |
| FPR | FP / (FP + TN) | Wie viele echte Negative fälschlich markiert? |
| F1 | 2 · P · R / (P + R) | Balance aus Precision und Recall |

**Aufgabe 4 von Hand** (TN 75, FP 22, FN 24, TP 50; total 171):

| Metrik | Rechnung | Wert | Bedeutung |
| --- | --- | --- | --- |
| Accuracy | (50 + 75) / 171 | 0.731 | 73 % aller Fälle richtig |
| Precision | 50 / (50 + 22) = 50 / 72 | **0.694** | Von 72 vorhergesagten Positiven sind 50 echt; ein Alarm stimmt in ca. 69 % |
| Recall | 50 / (50 + 24) = 50 / 74 | **0.676** | Von 74 echten Positiven werden 50 gefunden, 24 verpasst |
| FPR | 22 / (22 + 75) = 22 / 97 | **0.227** | Ca. 23 % der echten Negativen fälschlich markiert |

**Kernunterschied = der Nenner:**

- **Precision** schaut auf die **Vorhersagen**: Spalte «Predicted 1» (TP + FP). Frage: Kann ich einem Alarm trauen?
- **Recall** schaut auf die **Realität**: Zeile «Actual 1» (TP + FN). Frage: Wie viel habe ich gefunden?

**Merkhilfe:** **P**recision = **P**redicted (Spalte), **R**ecall = **R**eal (Zeile).

```python
recall = TP / (TP + FN)
```

**Aufgabe 5, Modell bei Schwelle 0.5** (Test, 576 Unfälle): TN 489, FP 11, FN 56, TP 20.

| Metrik | Wert | Rechnung |
| --- | --- | --- |
| Accuracy | 0.884 | (489 + 20) / 576 |
| Always-negative-Baseline | 0.868 | 500 / 576 |
| Precision | 0.645 | 20 / 31 |
| Recall | 0.263 | 20 / 76 |
| F1 | 0.374 | tief, weil Recall tief |

- Schwelle 0.5 heisst hier: «tödlich» erst ab 2 Verschütteten (p(1) = 0.302 < 0.5).
- **Accuracy-Falle bei seltenen Positiven:** Immer «nicht tödlich» sagen gibt schon 86.8 %; das Modell ist nur 0.016 besser. Accuracy versteckt die verpassten Fälle.
- **Recall** zeigt, dass nur etwa jeder vierte tödliche Unfall gefunden wird (Baseline: Recall 0). 43 der 56 verpassten hatten genau 1 Verschütteten.

**`ConfusionMatrixDisplay` lesen:**

- Y-Achse «True label» = Zeilen = Realität; x-Achse «Predicted label» = Spalten = Vorhersage.
- Oben links TN (489), oben rechts FP (11), unten links FN (56), unten rechts TP (20). Diagonale = richtig.
- Farbe = Anzahl (Farbskala rechts); hell = viele. Hier dominiert TN, weil die meisten Unfälle nicht tödlich sind.
- Zeilensummen = tatsächliche Klassen: 489 + 11 = 500 nicht tödlich, 56 + 20 = 76 tödlich.

**Code-Details:**

```python
predicted = (probability >= 0.5).astype(int)   # Schwelle anwenden, True/False -> 1/0
cm = confusion_matrix(y_test, predicted, labels=[0, 1])   # Reihenfolge der Klassen fixieren
precision_score(y_test, predicted, zero_division=0)   # 0 statt Warnung, falls nie positiv vorhergesagt
1 - y_test.mean()   # Always-negative-Accuracy = Anteil der Negativen
```

- `y_test.mean()` = Anteil der Einsen (0.132), weil y nur 0/1 enthält; 1 minus dieser Anteil = Accuracy, wenn man immer 0 vorhersagt.

**Welche Metrik zählt? (hängt von Klassenverteilung und Fehlerkosten ab)**

| Situation | Wichtigste Metrik | Beispiel |
| --- | --- | --- |
| Klassen ausgeglichen, FN und FP ähnlich teuer | Accuracy reicht weitgehend (Baseline «immer negativ» nur ca. 50 %) | Münzwurf-ähnliche Aufgaben |
| Fehlalarm (FP) teuer, verpasster Fall (FN) billig | **Precision** | Spamfilter: wichtige Mail im Spam ist schlimmer als durchrutschender Spam |
| Positive selten, verpasster Fall (FN) teuer | **Recall** | tödliche Unfälle, Diagnosen, Betrugserkennung (Kosten 10 : 1 in Aufgabe 6) |

Recall ist trotzdem immer eine nützliche Zusatzinformation. Formal entscheidet die Kostenformel c\_FN · FN + c\_FP · FP (Concept Block 3).

#### Schwelle, Kosten, ROC und AUC

Quelle: ML Basics 04, Concept Block 3 und 4; Übung Aufgaben 6 und 7.

```latex
\hat y = 1 \ \text{falls}\ p \ge \tau \qquad \text{total cost} = c_{FN}\,FN + c_{FP}\,FP
```

```python
labels = (probability >= threshold).astype(int)
TN, FP, FN, TP = confusion_matrix(y_test, labels, labels=[0, 1]).ravel()
```

**Reihenfolge von `.ravel()`:** TN, FP, FN, TP (Matrix zeilenweise gelesen).

| Schwelle | Regel | FP | FN | Recall | Kosten (10 · FN + FP) |
| --- | --- | --- | --- | --- | --- |
| 0.5 | tödlich ab 2 Verschütteten | 11 | 56 | 0.263 | 571 |
| 0.3 | tödlich ab 1 Verschüttetem | 88 | 13 | 0.829 | 218 |

- **Schwelle senken** → mehr Positive gefunden (Recall ↑, FN ↓), aber mehr Fehlalarme (FP ↑). Recall und FPR können beim Senken nicht sinken; Precision kann sich in beide Richtungen bewegen.
- Mit Kosten 10 : 1 ist 0.3 viel günstiger. Die 13 restlichen Verpassten hatten 0 Verschüttete, wie 412 nicht-tödliche Unfälle → mit diesem einen Input nicht trennbar.
- **Schwelle nie auf den Testdaten wählen**, sondern auf Validierungsdaten und nach Fehlerkosten (gleiche Logik wie CV in Ordner 01).

**ROC-Kurve lesen:** x = FPR, y = Recall (TPR); jeder Punkt = eine Schwelle. Diagonale = zufälliges Ranking. Je näher an der linken oberen Ecke, desto besser. Wenige Ecken, weil der Input nur wenige Werte hat (0, 1, 2, …).

```python
RocCurveDisplay.from_predictions(y_test, probability)
roc_auc_score(y_test, probability)   # Wahrscheinlichkeiten, nicht 0/1-Labels!
```

**AUC = 0.841:** Nimmt man zufällig einen tödlichen und einen nicht-tödlichen Unfall, gibt das Modell dem tödlichen in etwa 84 % der Fälle die höhere Wahrscheinlichkeit (Gleichstand zählt halb). 0.5 = zufällig, 1 = perfekt. AUC bewertet das **Ranking über alle Schwellen**, nicht den Anteil richtiger Labels: Gutes Ranking (0.841) und trotzdem nur 26 % Recall bei 0.5 sind kein Widerspruch.

**Ecken der ROC-Kurve = Schwellen aus Aufgabe 6** (500 echte Negative, 76 echte Positive):

| Ecke (FPR, Recall) | Rechnung | Schwelle / Regel |
| --- | --- | --- |
| (0, 0) | nichts positiv vorhergesagt | sehr hohe Schwelle |
| (0.022, 0.263) | FPR 11/500, Recall 20/76 | 0.5: tödlich ab 2 Verschütteten |
| (0.176, 0.829) | FPR 88/500, Recall 63/76 | 0.3: tödlich ab 1 Verschüttetem |
| (1, 1) | alles positiv vorhergesagt | tödlich ab 0 Verschütteten |

So hängen ROC-Kurve und Schwellenvergleich zusammen: Die Kurve zeigt **alle** Schwellen auf einmal, Aufgabe 6 nur zwei Punkte davon. `plt.plot([0, 1], [0, 1], 'k--')` zeichnet die Diagonale (zufälliges Ranking) als schwarze gestrichelte Linie.

**Interpretationen (Vorschlag):**

> **1.** The probability is 0.731 (e⁻¹ ≈ 0.368, p = 1 / 1.368), which is at least 0.5, so the predicted class is 1.
>
> **2.** A positive case (fatal = 1) is an accident with at least one death; 13.2% of the 2876 accidents since 2000/01 are fatal. stratify=y keeps this share in training and test. The number of fully buried people is only known after an accident, so this models outcomes of recorded accidents, not a pre-trip avalanche forecast.
>
> **3.** Yes. The slope is positive (2.26), so the predicted probability rises with the number of fully buried people: 0.04 for 0, 0.30 for 1, 0.81 for 2 and 0.98 for 3. Each extra person multiplies the odds by about 9.6. This is an association, not a causal effect.
>
> **4.** Precision = 50/72 = 0.694: of the predicted positives, 69% are real. Recall = 50/74 = 0.676: of the actual positives, 68% are found. Precision looks at the predicted positives, recall at the actual positives.
>
> **5.** Rows are actual, columns predicted classes. Accuracy is 0.884, only slightly above the always-negative baseline of 0.868, because 87% of accidents are non-fatal. Recall is only 0.263: the model finds about one in four fatal accidents. Accuracy hides these misses; recall shows them.
>
> **6.** Lowering the threshold from 0.5 to 0.3 changes the rule to «fatal from 1 buried person»: missed fatal accidents fall from 56 to 13 (recall 0.263 → 0.829), false alarms rise from 11 to 88. With costs 10 per miss and 1 per false alarm, the cost drops from 571 to 218. The threshold should be chosen on validation data, not on this test comparison.
>
> **7.** Yes, the ROC curve lies clearly above the diagonal; the test AUC is 0.841. For a random fatal and a random non-fatal accident, the model gives the fatal one the higher probability about 84% of the time. AUC summarises the ranking across all thresholds, not the share of correct labels.

#### Klassifikationsbaum: Gini und Blattwahrscheinlichkeit

Quelle: ML Basics 05, `classification_trees_ensembles_concept.ipynb`, Block 1–3; Übung Aufgaben 1–3. Datensatz: Titanic; Überleben aus Alter, Fahrpreis, Klasse und Geschlecht.

**Unterschied zum Regressionsbaum:** Blatt sagt keinen Mittelwert voraus, sondern **Klassenanteile** (Wahrscheinlichkeiten) und die Klasse mit dem grössten Anteil. Split-Kriterium ist **Gini** (oder Entropie) statt SSE.

```latex
\hat P(y=k \mid \text{leaf}) = \frac{\text{number in class } k}{\text{number in leaf}}
```

```latex
G = 1 - \sum_k p_k^2 \qquad \text{(2 Klassen: } G = 1 - p^2 - (1-p)^2) \qquad H = -\sum_k p_k \log(p_k)
```

```latex
\Delta G = G_{\text{parent}} - \left( \frac{n_L}{n} G_L + \frac{n_R}{n} G_R \right)
```

- **Gini = wie gemischt ein Knoten ist:** 0 = rein (nur eine Klasse), 0.5 = 50/50 (maximal gemischt bei 2 Klassen).
- Split mit der **grössten Gini-Abnahme** wählen (Kinder nach Grösse gewichtet), dann rekursiv weiter. Stopp, wenn Knoten rein ist oder `max_depth` / `min_samples_leaf` greift.

**Aufgabe 1 von Hand** (100 Passagiere, 40 überlebt):

```python
gini = 1 - p ** 2 - (1 - p) ** 2
```

| Knoten / Split | Rechnung | Ergebnis |
| --- | --- | --- |
| Parent 40/60 | 1 − 0.4² − 0.6² = 1 − 0.16 − 0.36 | G = **0.48** → nicht rein |
| «male?» links (60, 12 überlebt) | 1 − 0.2² − 0.8² | 0.32 |
| «male?» rechts (40, 28 überlebt) | 1 − 0.7² − 0.3² | 0.42 |
| «male?» gewichtet | 0.6 · 0.32 + 0.4 · 0.42 | 0.36 → Abnahme **0.12** |
| «first class?» | 0.25 · 0.48 + 0.75 · 0.444 ≈ 0.453 | Abnahme nur **0.027** |
| Blatt 145 / 125 | 145 / 270 | P(überlebt) = **0.537** ≥ 0.5 → «survived» |

→ «male?» trennt Überlebende viel besser und wird Root-Split.

**Aufgabe 2, Daten:**

```python
titanic = titanic.dropna(subset=['Age', 'Fare']).copy()
X['male'] = (titanic['Sex'] == 'male').astype(int)   # 1 = Mann, 0 = Frau
X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, stratify=y, random_state=42)
```

- 714 Passagiere nach Entfernen fehlender Alter/Fahrpreise: 571 Training, 143 Test; ca. 40.6 % überlebt.
- `stratify=y` hält den Überlebensanteil in beiden Teilen gleich (232 von 571, 58 von 143).
- **Repräsentativität:** Passagiere ohne Altersangabe fallen weg; sind sie systematisch anders (z. B. häufiger 3. Klasse), sind die Daten verzerrt.

**Aufgabe 3, Klassifikationsbaum lesen:**

```python
tree = DecisionTreeClassifier(max_depth=2, random_state=42)
plot_tree(tree, feature_names=list(X.columns),
          class_names=['Not survived', 'Survived'], filled=True, rounded=True)
tree.predict_proba(new_passengers)[:, 1]   # P(survived)
```

| Angabe im Knoten | Bedeutung |
| --- | --- |
| `male <= 0.5` | Frage: True (Frau) → links, False (Mann) → rechts |
| `gini` | Durchmischung im Knoten |
| `samples` | Anzahl Trainingspassagiere im Knoten |
| `value = [a, b]` | Anzahl nicht überlebt / überlebt |
| `class` | Mehrheitsklasse = Vorhersage |
| Farbe | Orange = eher Not survived, Blau = eher Survived; je kräftiger, desto reiner |

| Blatt | Weg | value \[nicht, überlebt\] | P(survived) | Klasse |
| --- | --- | --- | --- | --- |
| Frauen, 1./2. Klasse | male ≤ 0.5 → Pclass ≤ 2.5 | \[7, 122\] | 0.946 | Survived |
| Frauen, 3. Klasse | male ≤ 0.5 → Pclass > 2.5 | \[43, 34\] | 0.44 | Not survived |
| Männer, 1. Klasse | male > 0.5 → Pclass ≤ 1.5 | \[49, 34\] | 0.41 | Not survived |
| Männer, 2./3. Klasse | male > 0.5 → Pclass > 1.5 | \[240, 42\] | 0.149 | Not survived |

- Passagier 1 (Mann, 30, 3. Klasse) → 0.149 → nicht überlebt; Passagierin 2 (Frau, 30, 1. Klasse) → 0.946 → überlebt.
- Bei Tiefe 2 nutzt der Baum nur Geschlecht und Klasse; Alter und Fahrpreis nicht.
- Ein Label fasst eine Wahrscheinlichkeit zusammen: auch 0.946 ist keine Gewissheit (7 von 129 Frauen starben).

#### Klassifikation: Pruning, Forest, Boosting und GridSearchCV

Quelle: ML Basics 05, Concept Block 3–5; Übung Aufgaben 4–6.

**Aufgabe 4, Pruning:**

| alpha | Blätter | Training-Accuracy |
| --- | --- | --- |
| 0.0 | 136 | 0.988 |
| 0.01 | 5 | 0.800 |

- `pruned.score(X_train, y_train)` = Accuracy bei Klassifikatoren (bei Regressoren R²).
- 131 zusätzliche Blätter mit oft nur wenigen Passagieren → Baum hat Trainingsdaten fast auswendig gelernt (Noise). Hohe Training-Accuracy reicht nicht zur Auswahl; Komplexität mit CV wählen.

**Forest vs. Boosting bei Klassifikation:**

- **Random Forest:** viele Bäume unabhängig (Bootstrap + zufällige Inputs pro Split); sklearn **mittelt die Klassenwahrscheinlichkeiten**. Beispiel 0.8, 0.6, 0.3 → Mittel 0.567 → überlebt bei 0.5. Klassisch oft als Mehrheitsabstimmung beschrieben; Mitteln kann ein anderes Ergebnis geben als Abstimmen.
- **Gradient Boosting:** kleine Bäume nacheinander, arbeitet mit Log-Loss und Pseudo-Residuen (nicht einfach 0/1-Fehlern).

```python
cross_val_score(model, X_train, y_train, cv=5, scoring='roc_auc')
```

- CV AUC: Forest **0.871**, Boosting **0.861**. Differenz 0.010 = klein; anderer Split oder andere Settings könnten die Reihenfolge ändern. Keine Methode gewinnt immer.

**Aufgabe 6, GridSearchCV:**

```python
grid = GridSearchCV(
    RandomForestClassifier(n_estimators=100, random_state=42),
    {'max_features': ['sqrt', 1.0], 'min_samples_leaf': [1, 5, 20]},
    cv=5, scoring='roc_auc')
grid.fit(X_train, y_train)
grid.best_params_, grid.best_score_
p = grid.predict_proba(X_test)[:, 1]
confusion_matrix(y_test, p >= 0.5, labels=[0, 1])
```

- **Kombinationen:** 2 × 3 = **6**; je 5 Folds → 30 Forests, plus ein finaler Refit auf allen Trainingsdaten.
- `max_features='sqrt'` bei 4 Inputs = 2 Inputs pro Split; `1.0` = alle 4.
- Gewählt: `sqrt`, `min_samples_leaf=1` (= Default) → Best CV AUC 0.871, gleich wie Forest in Aufgabe 5.
- Final Test AUC **0.828**: tiefer als CV, aber eine einzelne Schätzung aus 143 Passagieren.
- **Warum eine Schwelle:** AUC nutzt Wahrscheinlichkeiten; eine Konfusionsmatrix braucht Labels → Schwelle 0.5.
- Matrix `[[71 14] [15 43]]` → TN 71, FP 14, FN 15, TP 43 · Accuracy (71 + 43) / 143 = 0.797 · Recall 43 / 58 = 0.741 · Precision 43 / 57 = 0.754.
- **Ablauf wie immer:** Suche nur auf Trainingsdaten (CV), Test erst danach und einmal.

**Interpretationen (Vorschlag):**

> **1.** The 40/60 node is not pure: Gini = 1 − 0.4² − 0.6² = 0.48 (pure would be 0). The «male?» split reduces Gini most (0.48 → 0.36, decrease 0.12), compared with only 0.027 for «first class?», so it separates survivors much better. The 145/125 leaf has P(survived) = 145/270 ≈ 0.537 ≥ 0.5, so it predicts «survived».
>
> **2.** male is 1 for men and 0 for women. stratify=y keeps the survival share (about 40.6%) equal in training and test data; without it, the test set could by chance contain noticeably more or fewer survivors. Removing passengers with missing age may make the data less representative.
>
> **3.** The root splits by sex. The 30-year-old man in 3rd class ends in the leaf of men in 2nd/3rd class (240 died, 42 survived): P(survived) = 0.149, predicted «not survived». The 30-year-old woman in 1st class ends in the leaf of women in 1st/2nd class (7 died, 122 survived): P(survived) = 0.946, predicted «survived». At depth 2 the tree uses only sex and class. A label summarises a probability: even 0.946 is not certainty.
>
> **4.** alpha = 0.01 creates far fewer leaves (5 instead of 136). The unpruned tree reaches 98.8% training accuracy by nearly memorising the training passengers; much of the extra 18.8 percentage points is fitted noise. Higher training accuracy is therefore not enough; complexity must be chosen with validation such as CV.
>
> **5.** The random forest builds trees independently on bootstrap samples with random inputs per split and averages their probabilities; boosting adds small trees sequentially, each correcting the remaining errors. CV AUC: forest 0.871, boosting 0.861. The difference is small; it does not show that one method is always better.
>
> **6.** The chosen settings are max\_features = 'sqrt' and min\_samples\_leaf = 1; 2 × 3 = 6 combinations were tried (30 CV fits). Best CV AUC 0.871, final test AUC 0.828 (single estimate from 143 passengers). AUC uses probabilities, but a confusion matrix needs labels, so a threshold (0.5) converts probabilities into classes: TN 71, FP 14, FN 15, TP 43; accuracy 0.797, recall 0.741, precision 0.754.

### Entscheidungsbäume

- **Regressionsbaum-Split**: SSE(links) + SSE(rechts) → min. Die Blattvorhersage ist der Mittelwert von y im Blatt. (F. 29–30)
- **Gini**: G = 1 − Σₖ p̂ₖ². Reiner Knoten = 0, Maximum bei 50:50 = 0,5. (F. 41)
- **Gini-Abnahme**: ΔG = G\_Eltern − (n\_L/n · G\_L + n\_R/n · G\_R). Der grösste ΔG ergibt den besten Split. (F. 42)
- **Blattwahrscheinlichkeit**: p̂(Klasse) = Anzahl der Klasse im Blatt / Anzahl total im Blatt. (F. 43)
- **Pruning**: R\_α(T) = R(T) + α · |T|. Je grösser α, desto kleiner der Baum; α wird per CV gewählt. (F. 31)
- **Baumgrösse**: höchstens 2^(d+1) − 1 Knoten bei Tiefe d. (F. 40)

### Ensembles

- **Varianz des Mittelwerts** = ρσ² + (1 − ρ)σ² / B. Der Anteil ρσ² bleibt immer bestehen. Beispiel: σ² = 1, ρ = 0,2, B = 100 → 0,208. (F. 33)
- **Bagging**: Bei Regression ŷ = (ŷ⁽¹⁾ + … + ŷ⁽ᴮ⁾) / B, bei Klassifikation Mehrheit oder Mittel der Wahrscheinlichkeiten. Rund 37 % der Daten sind pro Baum out-of-bag. (F. 34)
- **Random Forest, Faustregeln für m**: m ≈ √p bei Klassifikation, m ≈ p/3 bei Regression. (F. 35)
- **Gradient Boosting**: Fₘ(x) = Fₘ₋₁(x) + ν · hₘ(x). Bei quadratischem Verlust lernt hₘ die Residuen. (F. 36)

### Klassifikation

- **Logistische Regression**: p(x) = 1 / (1 + e^−(β₀ + β₁x)). Beispiel: β₀ = −5, β₁ = 1, x = 6 → p ≈ 0,73. (F. 39)
- **Schwelle**: ŷ = 1, falls p̂(x) ≥ τ. (F. 49)

### Konfusionsmatrix und Masse (F. 48)

Anordnung wie in scikit-learn: Zeilen = tatsächlich, Spalten = vorhergesagt.

|  | vorhergesagt negativ | vorhergesagt positiv |
| --- | --- | --- |
| **tatsächlich negativ** | TN | FP |
| **tatsächlich positiv** | FN | TP |

| Mass | Formel | Frage |
| --- | --- | --- |
| Accuracy | (TP + TN) / (TP + TN + FP + FN) | Wie viele Vorhersagen sind richtig? |
| Precision | TP / (TP + FP) | Wie viele der vorhergesagt Positiven sind echt positiv? |
| Recall (TPR) | TP / (TP + FN) | Wie viele echt Positive wurden gefunden? |
| FPR | FP / (FP + TN) | Wie viele echt Negative wurden fälschlich markiert? |
| F1 | 2 · Precision · Recall / (Precision + Recall) | Ausgleich von Precision und Recall |

- **ROC-Kurve**: (FPR, TPR) für jede Schwelle τ. **AUC** ist die Wahrscheinlichkeit, dass ein zufälliger positiver Fall höher eingestuft wird als ein zufälliger negativer (0,5 = Zufall, 1 = perfekt). (F. 50)
- **Achtung**: Bei unausgewogenen Klassen ist die Accuracy allein irreführend. (F. 48)

### Python-Umsetzung mit scikit-learn

Grundmuster für jedes Modell: Modell erzeugen → `fit` auf Trainingsdaten → `predict` / `predict_proba` auf Testdaten → mit `sklearn.metrics` bewerten. **X** = Merkmale (Tabelle, doppelte Klammern), **y** = Zielgrösse (eine Spalte). Alle Beispiele wurden getestet; Kontrollwerte stehen jeweils darunter.

#### Lineare Regression, R² und RMSE (F. 19–22)

```python
import numpy as np
import pandas as pd
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score, mean_squared_error

df = pd.DataFrame({
    "flaeche": [35, 48, 60, 72, 85, 95, 110, 130],
    "miete":   [1250, 1600, 1950, 2350, 2750, 3050, 3500, 4100]
})
X = df[["flaeche"]]   # Tabelle
y = df["miete"]       # eine Spalte

model = LinearRegression().fit(X, y)
print(model.intercept_, model.coef_)              # β0, β1
print(model.predict(pd.DataFrame({"flaeche": [95]})))

y_hat = model.predict(X)
print(r2_score(y, y_hat))                         # R²
print(np.sqrt(mean_squared_error(y, y_hat)))      # RMSE = Wurzel aus MSE
```

Kontrollwerte: β₀ ≈ 162, β₁ ≈ 30,3, Vorhersage 95 m² ≈ 3043 CHF, R² ≈ 0,9997, RMSE ≈ 16,6 (erfundene Übungsdaten).

#### p-Werte, Konfidenz- und Prognoseintervall mit statsmodels (F. 23, 25)

scikit-learn liefert diese Werte nicht. `add_constant` ist nötig, sonst fehlt β₀.

```python
import statsmodels.api as sm

X_sm = sm.add_constant(df[["flaeche"]])
ols = sm.OLS(df["miete"], X_sm).fit()
print(ols.summary())          # Koeffizienten, p-Werte, R²

neu = sm.add_constant(pd.DataFrame({"flaeche": [95]}), has_constant="add")
print(ols.get_prediction(neu).summary_frame(alpha=0.05))
# mean_ci_lower/upper = Konfidenzintervall (Durchschnitt)
# obs_ci_lower/upper  = Prognoseintervall (einzelner Fall)
```

Nicht getestet (statsmodels fehlte in der Testumgebung); Umsetzung im Kurs-Notebook `Linear_Regression` abgleichen.

#### Regressionsbaum: Split von Hand prüfen (F. 30)

```python
from sklearn.tree import DecisionTreeRegressor, export_text

X = pd.DataFrame({"x": [1, 2, 3, 4, 5]})
y = [10, 12, 14, 30, 34]

baum = DecisionTreeRegressor(max_depth=1).fit(X, y)   # nur ein Split
print(export_text(baum, feature_names=["x"]))
```

Kontrollwerte: Split bei x ≤ 3,5, Blattwerte 12 und 32, also identisch mit Folie 30.

#### Klassifikation: kompletter Ablauf (F. 39, 48–50, 57)

```python
from sklearn.datasets import load_breast_cancer
from sklearn.model_selection import train_test_split
from sklearn.pipeline import make_pipeline
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import (confusion_matrix, precision_score,
                             recall_score, f1_score, roc_auc_score)

X, y = load_breast_cancer(return_X_y=True)

# 1. Aufteilen: 80 % Training, 20 % Test, Klassenanteile gleich halten
X_tr, X_te, y_tr, y_te = train_test_split(
    X, y, test_size=0.2, stratify=y, random_state=42)

# 2. Skalieren + Modell in einer Pipeline, nur auf Trainingsdaten fitten
model = make_pipeline(StandardScaler(), LogisticRegression())
model.fit(X_tr, y_tr)

# 3. Wahrscheinlichkeit für Klasse 1 (zweite Spalte)
p = model.predict_proba(X_te)[:, 1]

# 4. Schwelle τ anwenden
y_pred = (p >= 0.5).astype(int)

# 5. Bewerten
print(confusion_matrix(y_te, y_pred))   # [[TN, FP], [FN, TP]]
print(precision_score(y_te, y_pred))
print(recall_score(y_te, y_pred))
print(f1_score(y_te, y_pred))
print(roc_auc_score(y_te, p))           # AUC braucht p, nicht y_pred!
```

Kontrollwerte: Matrix \[\[41, 1\], \[1, 71\]\], Precision = Recall = F1 ≈ 0,99, AUC ≈ 0,995. Mit `p >= 0.3` wird die Matrix zu \[\[40, 2\], \[0, 72\]\]: kein FN mehr, dafür ein FP mehr (Zielkonflikt F. 49).

#### Klassifikatoren per Kreuzvalidierung vergleichen (F. 15, 40–47)

```python
from sklearn.model_selection import cross_val_score
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
from sklearn.svm import SVC

modelle = {
    "Baum":          DecisionTreeClassifier(max_depth=3, random_state=42),
    "Random Forest": RandomForestClassifier(random_state=42),
    "Boosting":      GradientBoostingClassifier(random_state=42),
    "SVM":           make_pipeline(StandardScaler(), SVC(C=1, kernel="rbf")),
}

for name, m in modelle.items():
    scores = cross_val_score(m, X_tr, y_tr, cv=5, scoring="roc_auc")
    print(name, round(scores.mean(), 3))
```

Kontrollwerte (AUC): Baum 0,922 · Random Forest 0,988 · Boosting 0,988 · SVM 0,994. Skaliert wird nur SVM, weil es mit Abständen rechnet — Bäume und Ensembles brauchen keine Skalierung.

#### Hyperparameter suchen mit GridSearchCV (F. 57)

```python
from sklearn.model_selection import GridSearchCV

grid = GridSearchCV(
    RandomForestClassifier(random_state=42),
    {"max_features": ["sqrt", 0.5],
     "min_samples_leaf": [1, 5, 20]},
    cv=5, scoring="roc_auc")
grid.fit(X_tr, y_tr)

print(grid.best_params_)   # beste Kombination
print(grid.best_score_)    # deren CV-AUC
```

Kontrollwerte: 2 × 3 = 6 Kombinationen × 5 Folds = 30 Läufe; bestes Ergebnis `max_features="sqrt"`, `min_samples_leaf=5`, AUC ≈ 0,988. Danach ist `grid` das beste Modell (`grid.predict_proba(X_te)`).

#### k-Means mit Elbow-Werten und PCA (F. 53–56)

```python
from sklearn.datasets import load_iris
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA

X, _ = load_iris(return_X_y=True)        # y wird nicht gebraucht: unüberwacht
X_s = StandardScaler().fit_transform(X)  # zuerst skalieren (F. 54)

for k in range(1, 7):
    km = KMeans(n_clusters=k, n_init=10, random_state=42).fit(X_s)
    print(k, round(km.inertia_, 1))      # y-Wert im Elbow-Plot

pca = PCA(n_components=2).fit(X_s)
print(pca.explained_variance_ratio_)     # Anteil erklärte Varianz je Achse
```

Kontrollwerte: inertia 600 → 222 → 140 → 114 → 91 → 82 (Knick bei k = 2–3); PCA: PC1 ≈ 73 %, PC2 ≈ 23 %.

#### Stolperfallen im Code

- `predict_proba(X)[:, 1]` = Wahrscheinlichkeit für Klasse 1; AUC immer mit Wahrscheinlichkeiten, nicht mit 0/1-Vorhersagen berechnen.
- Scaler nur auf Trainingsdaten fitten; am sichersten mit `make_pipeline`.
- Testdaten erst ganz am Schluss verwenden; Modellwahl und Hyperparameter nur per CV auf den Trainingsdaten.
- `confusion_matrix` liefert `[[TN, FP], [FN, TP]]` (F. 48).
- RMSE: `np.sqrt(mean_squared_error(...))`.

## Konzept-Merksätze und typische Fehler

### Für Teil A (Konzeptfragen)

Antworten ohne Bezug zu den konkreten Daten werden nicht gewertet. Nenne immer Tabellen-, Spalten- oder Variablennamen des vorliegenden Datensatzes.

- **ETL** = Extract (lesen), Transform (bereinigen, umformen), Load (ins Zielsystem schreiben).
- **Constraints** (Primary Key, Foreign Key, NOT NULL) sind Zusagen der Datenbank. `df.to_sql()` überträgt nur Daten, keine Constraints — danach sind Duplikate, verwaiste Verweise und fehlende Werte technisch möglich.
- **Datenqualitätsdimensionen**: Uniqueness (Duplikate), Completeness (fehlende Werte), Consistency (widersprüchliche Schreibweisen, referenzielle Integrität), Accuracy, Validity, Timeliness.

### Für Teil B (Fehleranalyse)

Dieser Teil bringt pro Arbeitspaket am meisten Punkte. Gefragt ist jeweils: Fehler benennen, begründen, korrigieren.

Typische Fehlerquellen, auf die du beim Lesen von fremdem Code achten solltest:

#### AP01 — Relationale Daten

- `INNER JOIN` statt `LEFT JOIN`, wodurch Datensätze ohne Gegenstück unbemerkt wegfallen
- fehlende oder falsche `ON`-Bedingung, was zu einem Kreuzprodukt führt
- `COUNT(*)` statt `COUNT(spalte)` bei Aggregation über einen LEFT JOIN
- `WHERE` statt `HAVING` bei Bedingungen auf Gruppen
- Vergleich mit `= NULL` statt `IS NULL`
- `SUM` über eine leere Gruppe liefert NULL statt 0 — `COALESCE` fehlt
- Gruppierung nach dem Namen statt nach dem Primärschlüssel

#### AP02 — Datenbeschaffung, Aufbereitung, EDA

- `df.corr()` lässt nicht-numerische Spalten stillschweigend weg; eine falsch eingelesene `object`-Spalte fehlt dann unbemerkt
- Pearson verwendet, obwohl der Zusammenhang nicht linear oder die Variable ordinal ist
- aus einer Korrelation auf Kausalität geschlossen
- Mittelwert als Repräsentant einer stark schiefen Verteilung, wo der Median gehört
- `value_counts()` ohne `dropna=False`, wodurch fehlende Werte unsichtbar bleiben
- Kennzahlen ohne ergänzende Grafik interpretiert
- `df.std()` und `np.std()` verwechselt (`ddof=1` gegenüber `ddof=0`)

#### AP03 — Machine Learning

- *(wird beim ML-Block ergänzt)*

#### Vorgehen beim Lesen von fremdem Code

Genau das verlangt Teil B. Sechs Schritte, in dieser Reihenfolge:

1. **Kommentaren misstrauen.** Der Kommentar sagt, was gemeint war; der Code sagt, was passiert. Steht «top ten» über einem `sort_index()`, ist der Kommentar die Absicht und der Code der Fehler.
2. **Methodenkette von links nach rechts lesen** und jeden Schritt einzeln ausgeben lassen.
3. **Datentypen prüfen**: `type(obj)`, `obj.shape`, `df.dtypes`.
4. **Zwischenstände ansehen**, statt nur das Endergebnis zu beurteilen.
5. **Achsen- und Beschriftungslogik prüfen**: Was steht auf x, was auf y, und passen Label und Titel dazu? Vertauschte Achsenbeschriftungen sind ein häufiger, leicht übersehener Fehler.
6. **Randfälle durchdenken**: fehlende Werte, leere Gruppen, eine Kategorie mit nur einer Beobachtung, Division durch 0.

In der Antwort immer beides liefern: **was** falsch ist und **warum** das zum beobachteten Ergebnis führt. Die Bewertung verlangt die Begründung ausdrücklich.
