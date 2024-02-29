# Data-Visualisation-Kredit
## 1. [KR01] Einlesen CSV Files
Als Data Scientist möchte ich die Daten der CSV-Files in ein DataFrame einlesen, um sie effizient analysieren und visualisieren zu können.
- [x] Done
## 2. [KR02] Zusammenfassung der DataFrames
Als Data Scientist möchte ich die eingelesenen DataFrames zusammenfassen, um sie einfacher analysieren und visualisieren zu können.
- [x] Done
## 3. [KR03] Identifikation von Daten Problemen
Als Data Scientist möchte ich einen ersten Überblick über die Daten haben, um im Review mit dem Business klären zu können, dass der Datensatz korrekt ist. Anzahl Spalten, Anzahl Reihen, erste identifizierte Probleme etc.
- [x] Done
## 4. [KR04] Visualisierung der Zielklasse
Als Data Scientist möchte ich die Zielklasse visuell erfassen und darstellen, um ein klares Verständnis von der Gewichtung der Klassen zu haben. Info: Bitte eine Python Methode erstellen, welche die Grafik plotted.
- [x] Done
## 5. [KR05] Anzahl Duplikate
Als Business möchte ich wissen, wie viele Duplikate es in meinem bereitgestellten Datensatz gibt.
- [x] Done
## 6. [KR06] Kredite in der urbanen Gegend
Als Business möchte ich wissen, wie viele Personen in der urbanen Gegend (Core Central Region = CCR) bereits mindestens einen Kredit hatten. Zusätzlich möchte ich wissen, wie viele Frauen einen Kredit bereits im urbanen Umfeld erhalten haben. Info: Bitte zwei Python Methoden erstellen, welche die gesuchten Werte zurückgeben.
- [x] Done
## 7. [KR07] Durchschnittseinkommen
Als Business möchte ich wissen, was das Durchschnittseinkommen von Selbstständigen und Angestellten Personen ist. Info: Bitte eine Python Methode erstellen, welche basierend auf dem gesuchten Beschäftigungsstatus (Selbständig, Angestellt) den gesuchten Wert zurück gibt.
- [x] Done
## 8. [KR08] Bildungsstatus höchstes Einkommen
Als Business möchte ich wissen, welchen Bildungsstatus die Person mit dem höchste Einkommen hat und wie hoch das Einkommen ist. Bitte nur auf Personen beziehen, die einen Kredit erhalten haben. Info: Bitte eine Python Methode erstellen, welche den Bildungsstatus und das Einkommen zurück gibt.
- [x] Done
## 9. [KR09] Identifikation von Ausreißern beim Einkommen
Als Business möchte ich wissen, ob in dem Datensatz numerische Ausreißer existieren. Bitte wählen Sie eine geeignete Visualisierungsmethode aus, um das Einkommen der Beantragenden zu analysieren. Info: Sofern Ausreißer in der Spalte existieren, erarbeiten Sie Vorschläge, wie mit diesen umzugehen ist.
- [x] Done
## 10. [KR10] Gegenüberstellung Gehalt Antragsteller und Co.-Antragsteller
Als Business möchte ich eine Gegenüberstellung der numerischen Verteilung des Gehalts des Antragstellers und des Co.-Antragstellers in einer visualisierten Form aufbereitet bekommen. Bitte bewerten Sie zusätzlich die generierte Abbildung. Müssen eventuell numerische Ausreißer behandelt werden?
- [x] Done
## 11. [KR11] Verteilung der Kredithöhe zum Bildungsabschluss
Als Business interessiert mich, ob die Kredithöhe (Loan_Amount) vom Bildungsabschluss des Antragsstellers abhängt. Bitte geben Sie ebenfalls eine Einschätzung zur Interpretation der Visualisierung ab.
- [x] Done
## 12. [KR12] Kreditstatus basierend auf Kredithöhe
Als Business möchte ich grafisch ermitteln, ob ein Zusammenhang zwischen dem Kreditstatus (loan_status) und der Kredithöhe besteht. Erstellen Sie bitte eine Grafik, die Sie anschließend interpretieren.
- [x] Done
## 13. [KR13] Visualisierung der Zielvariable in Abhängigkeit zum Lohn der beiden Antragsteller
Als Business möchte ich verstehen, ob ein direkter Zusammenhang zwischen der Zielvariable (loan_status) und dem Einkommen der beiden Antragsteller besteht. Tipp: Wählen Sie ein Scatter Plot mit dem Einfluss einer dritten Variable und interpretieren Sie die Ergebnisse. Müssen die jeweiligen Spalten womöglich bereinigt werden?
- [x] Done
## 14. [KR14] Höhe des Kredits basierend auf Ehestatus
Als Business möchte ich grafisch ermitteln, ob ein Zusammenhang zwischen der Kredithöhe und dem Ehestatus besteht. Erstellen Sie bitte eine Grafik, die Sie anschließend interpretieren. Tipp: Überprüfen Sie zusätzlich, ob der Ehestatus ausschließlich aus zwei Werten (wahr, falsch) besteht.
- [x] Done
## 15. [KR15] Standardisierung Gender
Als Data Scientist möchte ich den Datensatz auf unterschiedliche Schreibweisen bei String-Variablen untersuchen. Hierfür analysiere ich das Attribut Geschlecht und standardisiere, wenn nötig, die Abweichungen. Sind für das Attribut Geschlecht möglicherweise noch weitere Bereinigungsmaßnahmen notwendig?
- [x] Done
## 16. [KR16] Umgang mit irrelevanten Spalten
Als Data Scientist möchte ich den Datensatz auf irrelevante Spalten analysieren. Hierfür verschaffe ich mir zunächst einen Überblick über die einzelnen Spalten und deren Werte und bewerte anschließend deren Notwendigkeit. Abschließend bereite ich eine mögliche Lösung der irrelevanten Spalten vor.
- [x] Done
## 17. [KR17] Verteilung des Einkommens
Als Data Scientist möchte ich einen Plot erstellen, der exakt wie aus einer zurückliegenden Data Visualization Vorlesung des Studium ausschaut. Der Plot befindet sich angehängt zu diesem Ticket. Bitte implementiere mit Matplotlib den aufgeführten Plot, der die Maße (6,4) aufweist.
- [x] Done
## 18. [KR18] Verteilung des Einkommens aller Co.-Antragsteller mit weiblichen Antragsteller
Als Business möchte ich einen kombinierten Plot erstellt bekommen. Der kombinierte Plot soll aus einem Histogram und darunter abgebildet, dem korrespondierenden Box Plot bestehen. Konkret möchte ich die Verteilung des Einkommens der Co.-Antragsteller verstehen, bei welchen der Antragssteller weiblich ist.
- [ ] Done
## 19. [KR19] Verteilung des Bezirks bei Kreditablehnung und Akademikern
Als Business möchte ich wissen, wie die Verteilung des Bezirks (= Property_District) bei Akademikern (Education = Graduate) ausschaut, die keinen Kredit erhalten haben (Loan_Status = 0). Bitte wählen Sie eine geeignete Visualisierungsmethode, um die einzelnen Bezirke miteinander zu vergleichen.
- [x] Done
## 20. [KR20] Erstellung zweier komibinierter Bar Plots
Als Business möchte ich wissen, wie die Verteilung der Zielvariable (= Loan_Status) und der Selbständigkeit von Antragstellenden (= Self_Employed) ausschaut. Bitte wählen Sie einen kombinierten Bar Plot, bestehend aus einem vertikalen Bar Plot und einem horizontalen Bar Plot.
- [x] Done
## 21. [KR21] Verteilung von Selbständigkeit je Property District
Als Business möchte ich wissen, wie die Verteilung der Selbständigkeit (= Self_Employed) je Property District verteilt ist. Bitte erstellen Sie einen gruppierten Bar Plot.
- [x] Done
## 22. [KR22] Erstellung einer Korrelationsmatrix
Als Business möchte ich eine Korrelationsmatrix erstellt bekommen, um mögliche Beziehungen zwischen Attributen zu identifizieren. Wichtig: Bitte nur numerische Werte verwenden und keine kategorischen Werte umwandeln.
- [x] Done
## 23. [KR23] Verteilung des Einkommens aller verheirateter Antragsteller
Als Business möchte ich einen kombinierten Plot erstellt bekommen. Der kombinierte Plot soll aus einem Histogram und darunter abgebildet, dem korrespondierenden Box Plot bestehen. Konkret möchte ich die Verteilung der verheirateten Antragsteller verstehen.
- [x] Done
## 24. [KR24] Fehlerbehebung Box Plot
Als Data Scientist möchte ich einen auftretenden Fehler im nachfolgenden Code Snippet
lösen. Es scheint, als wird nicht ein Boxplot korrekt dargestellt, das das Gehalt des
Hauptantragstellers und des Co.-Antragstellers gegenüberstellt:

fig, ax = plt.subplots(figsize=(5,6))
ax.set_title("Distribution of Application Income and Co-Application Income")
ax.set_xlabel("Income")
ax.set_ylabel("Amount [in US$]")
ax.boxplot([df["Applicant_Income"], df["CoApplicant_Income"]])
ax.set_xticklabels(['Applicant_Income', 'CoApplicant_Income'])
plt.show()

Wo liegt der Fehler und wie kann dieser behoben werden?
- [ ] Done
