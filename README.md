## Projektaufgabe: Vorhersage von Verbrechen in San Francisco

Ihre Projektaufgabe, die Sie in Gruppen von zwei bis vier Studierenden bearbeiten sollen, ist die Vorhersage von Verbrechen in San Francisco. 
Die Daten dazu finden Sie auf Kaggle: [SF Crime](https://www.kaggle.com/c/sf-crime).


>    Die Daten sind zu groß für dieses GitHub Projekt, daher müssen sie eigenständig im data Ordner abgelegt werden:
>
>    data  
>    |-- train.csv  
>    |-- test.csv  


Sie sollen die Kategorie eines Verbrechens in San Francisco vorhersagen.   

Um den Umfang der Daten etwas zu verkleinern, beschränken Sie sich bitte auf folgende Kategorien: *Larceny/Theft*, *Assault*, *Drug/Narcotic*, *Vehicle Theft* und *Burglary*.

## Anforderungen

Für die Aufgabe gelten grundsätzlich folgende Anforderungen, die allerdings nach Absprache mit Herrn Prof. Dr. Spott und mir auf Ihre Problemstellung angepasst werden können.
Je nach Daten und Problemstellung soll es entweder um *Regression*, *Klassifikation* oder *Clustering* gehen (pro Projekt nur **eines** der drei). 

### Schritte des Projektes

1. **Deskriptive Analyse der Daten:**
    - Beschreiben Sie die Daten, Datentypen, Wertebereiche.
    - Überprüfen Sie fehlende Daten, falsche Werte und Korrelationen zwischen Merkmalen.
    - Benutzen Sie Visualisierungen, wenn es sinnvoll erscheint.
    - Was können wir aus dieser deskriptiven Analyse über das Problem lernen?

2. **Definition geeigneter Merkmale (Features):**
    - Leiten Sie aus den bestehenden Merkmalen neue ab.
    - Überlegen Sie sich zusätzliche Merkmale, z.B. mit externen Informationen.

3. **Anwendung von Verfahren für Klassifikation/Regression/Clustering:**
    - Jede*r von Ihnen soll ein Verfahren anwenden.

4. **Im Fall von Regression/Klassifikation:**
    - Benutzen Sie Kreuzvalidierung, um
        - die Hyperparameter zu optimieren.
        - die Qualität der Modelle zu evaluieren (wählen Sie sinnvolle Maße für die Qualität).

5. **Im Fall von Clustering:**
    - Optimieren Sie die Hyperparameter und evaluieren Sie die Qualität der Clusteringmodelle.

6. **Vergleich der Ergebnisse der verschiedenen Verfahren**

### Dokumentation

- Bitte benutzen Sie Formate wie Jupyter Notebooks.
- Mischen Sie textuelle Beschreibungen, Code und Visualisierungen.
- Die Dokumentation kann auf Deutsch oder Englisch verfasst werden, aber bitte entscheiden Sie sich für eine Sprache.

### Quellen und Hilfsmittel

- Sie dürfen Arbeiten anderer benutzen (z.B. bei Kaggle), allerdings nicht die Ihrer Kommilitonen.
- Geben Sie bitte immer die Quellen an.
- Als Hilfsmittel können Sie Aurélien Gérons Machine Learning Project Checklist verwenden: [Machine Learning Project Checklist](https://github.com/ageron/handson-ml/blob/master/ml-project-checklist.md).
