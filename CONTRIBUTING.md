# CONTRIBUTING.md - Anleitung zum Beitragen
Beiträge sind explizit erwünscht, der Sinn dieser Repository ist das gemeinsame Erstellen eines zentralen hubs für Inhalte.
Allerdings sollten einige Punkte vor dem Einreichen eines Pull Requests geprüft werden:


### Guide:
- fork erstellen 
- Änderungen vornehmen
- Checkliste prüfen
- Pull request einreichen


#### wichtige Hinweise / Tipps:
- bitte shreiben Sie sinnvolle commit messages (z.B. "adding content of last computer science lecture (graphs, heaps)" statt "added content")
- bitte wählen Sie einen sinnvollen Pull request Titel und beschreiben Sie in der ersten Nachricht, WAS Sie geändert haben und WARUM (Beispiel am Ende der Datei zu finden)


### PR-Checklist:

<details>
<summary> 1. In welche Kategorie fällt mein Beitrag ? </summary>

Beim Beitragen muss zwischen mehreren Kategorieren unterschieden werden:
1. repo-maintenance     - Pull requests, die Dateien, die in falschen Ordnern liegen bewegen oder andere administratorische Aufgaben erfüllen
2. content-addition     - Pull requests, die neuen Inhalt hinzufügen (dies beinhaltet neue Dateien oder das Fortschreiben existierender Dateien)
3. content-edit         - Pull requests die Fehler in Inhalten korrigieren

Diese Aufteilung findet sich auch in der Aufteilung der Labels wieder.
Falls Sie sich bei ihrem Pull request nicht ganz sicher, in welche Kategorie er passt, nutzen Sie bitte das 'not-categorized' - Label oder fügen Sie einen entsprechenden Hinweis im Titel ein. 

</details>




<details>
<summary> 1. Passt der Beitrag zu den im Studium gelernten Inhalten ? </summary>

Der Inhalt sollte zu dem, was in den Vorlesungen vermittelt wird, passen.
Weiterführende Inhalte sind zwar oft spannend und interessant, gehören jedoch nicht zu den zu lernenden Inhalten und sollten deshalb vermieden werden.

</details>

<details>
<summary> 2. Enthält der Beitrag copyright-geschützte Inhalte? </summary>

Es ist wichtig, dass nur Inhalte hinzugefügt werden, die entweder selbst erstellt wurden oder von dem Inhaber des Copyrights explizit für diese Art der Verwendung freigegeben wurde.
Dies bedeutet, dass das Hinzufügen von Vorlsungsfolien (sei es direkt oder indirekt in Karteikarten etc.) nur mit expliziter Zustimmung des jeweiligen Professors erfolgen darf.
Bei der Verwendung geschützter Inhalte muss zudem ein Eintrag in [sources.md](sources.md) erfolgen.

</details>



<details>
<summary> 3. Passt meine Datei in die aktuelle Dateistruktur ? </summary>

Um die Lerninhalte sinnvoll zu strukturieren gibt es eine festgelegte Dateistruktur.
Diese Datenstruktur sollte gewahrt werden. Die aktuelle Struktur kann [hier](file_structure.txt) angeschaut werden

</details>


<details>
<summary> 4. Erfülle ich die Datenschutzregeln ? </summary>

Wichtig für den Datenschutz in diesem Kontext ist:
- das Weglassen von Namen und Daten zu Dozenten
- Weglassen von Links zu offizillen oder inoffiziellen Studienseiten (z.B. Links zu Moodle etc.)

Selbstverständlich gilt auch für diese repository die DSGVO

</details>





### Beispiel Pull request:
```markdown
Hinzufügen von Karteikarten theoretische Informatik
```

```markdown
Ich habe Karteikarten für theoretische Informatik mit den folgenden Inhalten erstellt:
- Bäume
- Heaps
- Stacks
- Queues

Ich habe die guidelines gelesen und habe verwendete Quellen sowohl im Dokument als ich in sources.md angegeben und die Legalität des uploads geprüft.
Meine Änderungen enthalten Screenshots aus den Folien, dies ist mit dem Dozenten abgeklärt.


```



Vielen Dank für deinen Beitrag !