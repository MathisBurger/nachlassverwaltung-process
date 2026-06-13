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


### Question Session 02

- [ ] nachlassanlage.bpmn: Muss ich den Subprozess in Vorsorge Dokumente gedöns beschriften?
- [ ] Vllt Ergäzend daran: Muss wirklich jeder Subprozess eine Bezeichnung haben oder reicht es in manchen Fällen den weg zu lassen, wenn klar ist was passiert?
- [ ] Wo muss ich überall Datenobjekte und Data Stores nutzen und wo nicht?
- [ ] Müssen Default Flows auch beschriftet werden?
- [x] Angehörigen Anlage: Kann man die End Events so machen?


