# Fragen

### Question Session 01

- [x] Ist bei der Nachlassverwaltung der Ansatz mit den Subprozessen richtig? Können wir annehmen, dass ein Update Event nicht reinkommt, wenn ein Schritt noch nicht final abgeschlossen ist?
- [x] Antwort: Nein muss nicht bedacht werden in unserem Fall
- [ ] Kann man die Rückgängig mach Ereignisse der Transaktion hier gleich nennen? Oder ist das gegen die Best-Practises?
- [ ] Kann man die Kompensierenden Aufgaben für unsere Transaktion auch in die Call Activities rein machen?
- [ ] Antwort: Keine Call-Activity, sondern eingebetteter Prozess
- [x] Ist es in Ordnung, die Kalender Abfrage so zu mocken wie sie aktuell ist und dann einfach nur die Terminvorschläge zu generieren?
- [x] Antwort: Sendeaufgabe und Empfangsaufgabe anstatt Service-Task -> Einfach über print dann "Abfrage gestartet" und in der Empfangsaufgabe das Hardcodierte senden
- [ ] Nachlassverwaltungsprozess: Kann man auf eine Nachricht von der Beerdigungsplanung warten, damit man quasi noch das Testament in dem Part aktualisieren kann? Macht das Sinn oder ist das unsauber?
- [ ] Antwort: Haben die Frage nicht verstanden -> Müssen das nochmal klären
- Antwort: Ereignisteilprozess mit dem man jederzeit alles Anlegen kann....

- Anrwort; Keine Transaktion notwengi, einfach bestattung canceln und dann alle Daten löschen


### Question Session 02

- [ ] nachlassanlage.bpmn: Muss ich den Subprozess in Vorsorge Dokumente gedöns beschriften?
- [ ] Vllt Ergäzend daran: Muss wirklich jeder Subprozess eine Bezeichnung haben oder reicht es in manchen Fällen den weg zu lassen, wenn klar ist was passiert?
- ANtwort: ALle subprozesse. Deren Startereignisse nicht, aber Endereignisse schon
- [ ] Wo muss ich überall Datenobjekte und Data Stores nutzen und wo nicht?
- Antwort: Bei den Mehrfachinstanzmarkierungen muss das dran sein, ansonsten eben nicht
- [ ] Müssen Default Flows auch beschriftet werden?
- Antwort: Default Flows eliminieren und einfach richtig beschriften
- [x] Angehörigen Anlage: Kann man die End Events so machen?
- [x] Was genau aus dem 3. Semester ist relevant?
- [ ] Wie viele Business Rule Tasks sind notwenig? 4? Oder sind in den Anforderungen 4 Entscheidungen gemeint?
- [ ] Bei dem Eingebetteten Prozess, dann entsprechend selbst Logik, die Prüft, was storniert werden muss, oder?:wq


### Question Session 03

- [ ] Kann man den Prozess zum aktualisieren und Erstellen des Testaments so nennen, wie wir es haben???
