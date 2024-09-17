

# Elektronisches Laborbuch (ELN)

    ## Lerziele

    Die Teilnehmenden können . . .

- eigenständig eine komplexe Datendokumentation in einem ELN erstellen.

- Inhalte und Bedeutung einer Datendokumentation in einem ELN vermitteln.

- Dritte bzgl. ihrer Datendokumentationen in einem ELN beratend unterstützen.

- Vorlagen für Datendokumentationen in einem ELN entwickeln.


## Was sind Elektronische Laborbücher? 

> ___Elektronische Laborbücher (ELB)___ (oder Electronic Lab Notebooks (ELN)) dienen der Dokumentation der Konzeptionierung, Durchführung und Auswertung von wissenschaftlichen Experimenten, Beobachtungen oder Versuchen und den in diesem Zusammenhang erstellten Forschungsdaten.

{{1}}
******

Sie sind die digitalen Versionen von Laborbüchern im Papierformat, die bisher überwiegend in natur- und lebenswissenschaftlichen Disziplinen einen wesentlichen Teil des wissenschaftlichen Arbeitsprozesses darstellten.

Mit zunehmender Digitalisierung, v. a. bei der Erhebung von Daten, erfahren die ELN auch eine steigende Wahrnehmung und Nutzung. Insbesondere die Deutsche Forschungsgemeinschaft (DFG) sieht in der Umsetzung des Kodex __„Leitlinien zur Sicherung guter wissenschaftlicher Praxis“__ die Führung eines Laborjournals für die Qualitätssicherung vor$^1$. Die elektronische Dokumentation soll darüber hinaus __Nachvollziehbarkeit von entstandenen Forschungsdaten__ mit den jeweiligen Methoden-, Auswertungsund Analyseschritten erhöhen.

**********


{{2}}
********

* Gebräuchliche Synonyme für ENL: elektronisches Labornotizbuch, elektronisches Laborjournal, elektronisches Feldbuch, electronic laboratory notebook

* Neben den ELNs existieren auch Labor-Informations- und Management-System (LIMS), mit denen alle (Proben- und Geräte-)Daten und die Dokumentation der Arbeitsabläufe in Laboren in einem EDV-System automatisiert verwaltet werden können.

*************
## Softwarelösungen und Funktionalitäten

{{0-1}}
****
> Mittlerweile gibt es eine Reihe von ELN-Softwareangeboten – von kommerziellen Anbietern bis hin zu Open-Source-Lösungen. Einen ersten Überblick findet man auf der Webweite der ZBMed zu ELN$^2$. Beispielhaft zu nennen sind:

- Chemotion$^3$ (Open Source – nützlich für die chemische Fachcommunity)
- eLabFTW$^4$ (Open Source – generisch nutzbar und anpassbar)
- openBIS$^5$ (Open Source – generisches LIMS)
- TUM Workbench$^6$ (Open Source – generisches LIMS)
- Rspace ELN$^7$ (kommerziell – generisch nutzbar)
- Labfolder$^8$ (kommerziell – generisch nutzbar)
- eLabJournal$^9$ (kommerziell – generisch nutzbar)
- LabArchives$^1$$^0$  (kommerziell – generisch nutzbar)
******

{{1-2}}
******
> In der Regel haben unterschiedliche Disziplinen sehr verschiedene Anforderungen an Funktionalitäten, die eine ELN-Software mit sich bringen sollte, sodass es keine „one-fits-all-Lösung“ geben kann. Funktionalitäten, die eine ELN-Software mindestens aufweisen sollte, sind folgende:

- Versionierung aller vorgenommen Änderungen
- Einfache strukturierte Texteingabe (z. B. Markdown oder Hypertext Markup Language (HTML)-Editor)
- Anzeige und Einbettung von Grafiken (z. B. png)
- Möglichkeiten von Dateiupload und -speicherung
- Granulare Lese-/Schreibrechtevergabe der Benutzer*innen
- Erweiterte Suchfunktionen (z. B. nach Nutzer*in, Tags, Volltextsuche)
- Archivierungsfunktion mit Zeitstempel
- Exportfunktion insbesondere aller Dokumentationen (z. B. pdf) und Dateien (z. B. als zip-Archiv)
******

{{2-3}}
***
> Zusätzlich können weitere Funktionen sinnvoll sein, wie z. B.

- Klares intuitives Layout des User Interface (UI)
- Einbindungen von Office-Anwendungen (z. B. Tabellenkalkulation)
- Formeleditor insbesondere für komplexe mathematische und chemische Gleichungen
- Kalenderfunktion z. B. zur Buchung/Verwaltung von Gerätenutzung
- Bereitstellung einer standardisierten Application Programming Interface (API) z. B. RESTAPI
- Zweisprachigkeit (dt./en.) für wissenschaftliches und wissenschaftsunterstützendes Personal
- Integration von JupyterHub für weitere automatisierte Auswertungsschritte
- Möglichkeit, Teile des ELN öffentlich zu machen und zu teilen

******


{{3-4}}
*****
Je nach Fachdisziplin können erweiterte Funktionalitäten, wie z. B. die Einbindung eines Editors für chemische Strukturen von Bedeutung sein. Weitere Workflows zur automatischen Einbindung und Eintragung von Mess- und Labordaten sind zudem empfehlenswert. 

Welche Software sich daher am besten eignet, hängt immer von den benötigten Funktionalitäten ab und den Möglichkeiten, die Software entsprechend anzupassen. Eine Übersicht verschiedener ELNs und deren Funktionalitäten findet sich im ELN-Finder der TU Darmstadt$^1$$^1$ .

> Machen sie sich an dieser Stelle Gedanken zu folgenden Fragestellungen:
    - Welche Funktionen benötigt ein ELN?
- Welchen Anforderungen sollte es genügen? (Wunschliste für Anforderungen an ein ELN erarbeiten)
******

## Betrieb und rechtliche Anforderungen 

 {{0-1}}
****
In der von der ZB MED - Informationszentrum Lebenswissenschaften (ZB MED) erstellten Handreichung$^1$$^2$  werden praktische Hinweise gegeben, die bei der Entscheidung und Einführung eines ELNs helfen können. Bei der Einführung von ELNs, die als Open-Source-Software vorliegen, wird in der Regel eine technische Installation der Software „vor Ort“ (on-premise) benötigt.

> Sowohl für die Installation als auch den Betrieb der Open-Source-Software müssen personelle Ressourcen eingeplant werden. 

Die meisten kommerziellen Produkte bieten Komplettlösungen (Bereitstellen der Infrastruktur, Support, Updates) oft als Cloud-Service (Software as a Service (SaaS)) weniger als On-Premise-Varianten an. 

> Bei allen Varianten sollte auf Datensicherheit (Verschlüsselung) und Datenschutzvorgaben geachtet werden.

In Institutionen mit Personal- bzw. Betriebsrat ist dieser bei der Einführung mitbestimmungspflichtig und anfänglich zu informieren und zu involvieren.
*****

{{1-2}}
******
> Bei der Einführung eines ELNs sollte auch immer eine Exit-Strategie im Vorfeld mitbedacht werden.

Das bedeutet, dass die enthaltenen Daten mitsamt den dazugehörigen Informationen und Strukturen, aber auch Verlinkungen und Dateien in ein __menschen- sowie ein maschinenlesbares Format__ exportiert werden können. Dies kann z. B. in Form einer Datenbank realisiert werden. Die Daten sollten dabei so exportiert werden, dass sie ohne Verlust von Informationen in ein anders System migriert werden können. Momentan (Stand 2023) gibt es kein einheitliches Austauschformat zwischen den verschiedenen ELNs, doch gibt es eine Initiative einiger Anbieter$^1$$^3$ dieses für die Zukunft zu erarbeiten. Daher sind die Daten und Datenformate momentan größtenteils (noch) nicht miteinander kompatibel.

*****

{{2-3}}
******
Neben der reinen Dokumentation für die wissenschaftliche Arbeit bieten einige ELNs eine Versionierung von ELN-Eintragungen an, wodurch die Versionshistorie mittels Audit Trail im Nachgang nachvollziehbar wird. Unter Umständen kann es für abgeschlossene Projekte notwendig sein, diese vor Veränderungen zugriffsgeschützt zu archivieren. Auch hier bieten sich Zeitstempel und digitale Signaturen für die Beweissicherung an$^1$$^2$.

> Nicht zuletzt hängt der Erfolg des ELN maßgeblich von der Nutzung ab. 

Diese ist dabei stark abhängig von der angebotenen Unterstützung vor Ort z. B. in Form von Einführungskursen, der Bereitstellung von Schulungsunterlagen und Ansprechpersonen/Administrator*innen*. Auch zur Sichtbarkeit und Veränderungen von Einträgen durch verschiedene Personengruppen (Administrator*innen*/Nutzer*innen*/Projektmitglieder/Gäste) sollte sich im Vorfeld Gedanken gemacht und eruiert werden, ob das ELN ein granuläres Rechtemanagement umsetzen kann.
******


## Praktischer Umgang mit Elektronischen Laborbüchern 

{{0-1}}
*********
Wie bei der Wahl eines ELNs, so sollte auch beim praktischen Umgang mit einem ELN im Vorfeld eine Bedarfsanalyse erfolgen. Vor allem sollte das Layout ansprechend und intuitiv zu bedienen sein, um die Akzeptanz für die Nutzung zu erhöhen und Fehleingabe zu vermeiden. Insbesondere der Grundsatz __„weniger ist mehr“__ sollte bei der einführenden Bereitstellung der Dienste beachtet werden, um die Benutzer*innen zu führen und nicht zu überfordern. Daher empfiehlt sich, regelmäßige Schulungen von Beginn an im Umgang mit dem UI und der Dateneingabe ins ELN durchzuführen. Um die Akzeptanz weiter zu erhöhen, sollte für Rückfragen eine benannte Ansprechperson in der Einrichtung zur Verfügung stehen, damit diese bei spezifischen Anfragen zielgenau Unterstützung leisten kann. 
**********

{{1-2}}
************
> Für die Übertragung des wissenschaftlichen Forschungsprozesses in das ELN empfiehlt sich eine vorgehende „Projektanalyse“, die die Fragestellung beantworten sollte:

- Welche Daten werden erhoben?
- Wer erhebt die Daten?
- Wer überträgt die Daten?

********

{{2-3}}
*****
> Da nicht alle Daten und Metadaten eines Experiments in das ELN übertragen werden (können), sollte nach der Leitlinie verfahren werden, dass die Dokumentation in einem ELN min destens so vollständig sein sollte wie in einem klassischen (papiergebunden) Laborbuch.

Dazu gehört – auch zur Unterstützung – die Erarbeitung und Bereitstellung von __vorgefertigten Eingabemasken__ (Templates) sowie von __Standard Operating Procedure__ (SOP), um eine möglichst einfach Integration in den wissenschaftlichen Arbeitsprozess zu gewährleisten. Mithilfe eines SOP wird das standardisierte Vorgehen bei wissenschaftlichen Experimenten beschrieben, indem verständlich und nachvollziehbar alle Arbeitsschritte dargelegt, abgearbeitet und dokumentiert werden.
*******

 {{3-4}}
*******
Um eine kontinuierliche und eineindeutige Zuordnung von ‚analogen‘ Datensätzen (z. B. Materialproben) in das ELN zu gewährleisten, sollte im Vorfeld eine __Leitlinie über die systematische Probenbenennung__ erstellt werden. Hier bieten viele ELNs die Erzeugung von QR-Codes an, welche an die jeweiligen physischen Proben befestigt werden und damit durch einen direkten Scan der ELN-Eintrag aufgerufen werden kann. Direkt vorliegende rein ‚digitale‘ Daten (z. B. Messwertreihen) von (Labor-)Geräten können mittels Programmierung der API automatisch verarbeitet und in das ELN übertragen werden. Hierbei ist zu beachten, dass die meisten ELNs eine __Speicherbegrenzung für Dateianhänge__ besitzen und nicht fälschlicherweise von den Nutzer*innen als Daten(bank)archiv oder -backup missbraucht werden sollten. Wie bei dem klassischen papiergebundenen Laborbuch erfordert das digitale Pendant dieselbe Disziplin bei der Dokumentation und der kontinuierlichen Pflege der enthaltenen Daten, damit auch das ELN einen Mehrwert für die eigene wissenschaftliche Arbeit darstellt.
*********

# Übungen

## 5W1H

Machen Sie sich Gedanken zu den folgenden Fragen:

- __What__ – Was ist ein ELN und was sollte es beinhalten?
- __Who__ – Wer sollte einen ELN-Eintrag schreiben?
- __Where__ – Wo legt man einen ELN-Eintrag ab?
- __When__ – Wann startet man mit einem ELN-Eintrag?
- __How__ – Wie sollte ein ELN-Eintrag aufgebaut sein?
- __Why__ – Welche Vorteile ergibt eine Dokumentation in einem ELN?

## Erstellung eines ELN

Bitte erstellen Sie entweder eigenständig oder in Gruppenarbeit ein Template auf Grundlage eines Kuchenrezepts für die übergeordneten Kategorien eines SOP in einem elektronischen Laborjournal. Wenn möglich tauschen Sie sich anschließend mit anderen aus und vergleichen Sie die Kategorien. Danach erstellein Sie bitte, unter Verwendung des Kuchenrezepts für 'Tarte au Citron', einen vollständigen SOP (einschließlich Versuchsaufbau, Daten, Einheiten, Geräte usw.) in dem elektronischen Laborjournal. Zum Abschluss des Auftrags bitten wir Sie, Ihre Erfahrungen untereinander auszutauschen.

Alternativ vergleichen sie Ihre mit der bereitgestellten Musterlösung.

### Kuchenrezept

__Kuchenrezept „Tarte au citron“__

Für den Teig 100g weiche Butter und 75g Zucker schaumig schlagen. Eine Prise Salz und ein Ei unterheben und mit 200g Mehl und 20 g Mandelmehl einen Teig kneten. Diesen für 1 Stunde zugedeckt kalt stellen. Den Teig in eine gefettete Tarteform auslegen und leicht durchlöchern damit dieser keine Blase bildet. Den Boden für 15-20 min bei 180°C keksig-trocken backen und dann in der Form auskühlen lassen (a).

Für die Zitronencreme von 3 unbehandelte Zitronen die Schale abreiben und den Saft auspressen. Den Abrieb mit ca. 115ml Zitronensaft und 120 g Zucker aufkochen. Bei mittlerer Hitze 100g Butter, 3 Eier und 2 Eigelb hinzufügen und unter ständigen Rühren solange erwärmen bis die Masse verdickt (b). 

Die Zitronencreme auf den Tarteboden geben (c).

 
Für das Baiser/Meringue die 2 Eiweiß mit einer Prise Salz und 120 g Zucker zu einen Schaum aufschlagen. Die Zitronentarte mit dem Eischnee verzieren. Die gesamte Tarte sehr kurz im Ofen backen, bis die Meringue leicht bräunlich wird. Die Tarte abkühlen lassen, aus der Form nehmen und genießen (d).

![alt](Kuchenrezept_01 "")


### Musterlösung Template

__Date:__ 2023-04-24

__Created by__: Manu Musterperson

----

___Ziel des Experiments: Kuchenzept für ...___

Zutatenliste:

Benötigte/verwendete Geräte:

Zubereitungsschritte:

Analyse des Ergebnisses (Aussehen/Geschmack):

### Musterlösung SOP

 #### Kuchenrezept - Tarte au citron

__Date:__ 2023-04-24

__Tags:__ Tarte Cake Dessert

__Created by:__ Manu Musterperson 

---

 #### Ziel des Experiments: Kuchenzept für "Tarte au citron"

__~~Zutatenliste:~~__

 | Komponente | Menge | Zutat |
| ---- |:----------- | :------------|:---------|
|   Teig  |    200g     | Mehl     |
|     |    100g   |   weiche Butter   |
|     |     1 Stück  |    Ei  |
|     |   20g    | gemahlene Mandeln     |
|     |      75g |    Zucker  |
|     |      1 Prise |    Salz  |
|   Creme  | 3 Stück      |    Zitronen (unbehandelt)  |
|     |     3 Stück  |   Eier   |
|     |    2 Stück   |   Eigelb   |
|     |    100g   |   weiche Butter   |
|     |     120g  |   Zucker   |
| Baiserbelag (Meringue):  |     2 Stück  |   Eisweiß   |
|     |   1 Prise       |   Salz   |
|     |   120g    | Zucker     |


__~~Benötigte/verwendete Geräte:~~__

- Tarteform (Durchmesser 28cm)
- Schneebesen / Mixer
- Knethaken
- Rührbesen
- Topf
- Schüssel
- Backofen 180°C
- Spritzbeutel
- Kühlschrank
- Messbecher
- Reibe
- Saftpresse
- Teigschaber
- Küchenuhr


__~~Zubereitungsschritte:~~__

__Teig:__

1. Zucker und weiche Butter zu cremig schlagen.
2. Salz und Ei hinzufügen und verrühren
3. Mehl und gemahlene Mandeln unterheben und zu einen Teig verkneten
4. Teig ca. 1h im Kühlschrank ruhen lassen
5. Teig auf Tarteform verteilen, einstechen und 20 min im Backofen bei 180°C ausbacken
6. Teig in der Tarteform auskühlen lassen

__Creme:__

1. Schale der Zitronen abreiben
2. Zitronen auspressen und Saft auffangen
3. ca. 115ml Zitronensaft mit Zitronenabrieb 3min erhitzen
4. Topf vom Herd nehmen
5. Butter, Zucker, Eier und Eigelb unter ständigen rühren hinzugeben
6. Creme bei mittlere Hitze für 10-15min erwärmen bis diese verdickt
7. Creme auf der Tarte verteilen

__Meringue:__

1. Eiweiß, Salz und Zucker schaumig aufschlagen
2. Tarte mit dem Schaum mit Hilfe eines Spritzbeutel verzieren
3. Tarte kurz backen bis die Meringue leicht bräunlich wird

__~~Analyse des Ergebnisses (Aussehen/Geschmack):~~__

- sehr fruchtig
- starkes Zitronenaroma

__~~Steps~~__

- Teig herstellen
- Teig ausbacken
- Creme herstellen
- Creme verteilen
- Meringue herstellen
- Tarte ausbacken
- Tarte auskühlen
- Tarte frisch genießen

__~~Attached file~~__

Tarte-au-Citron.png

![alt](Fertige-Tarte "")

# Abkürzungsverzeichnis

- API Application Programming Interface
- DFG Deutsche Forschungsgemeinschaft
- ELB Elektronische Laborbücher
- ELN Electronic Lab Notebooks
- HTML Hypertext Markup Language
- LIMS Labor-Informations- und Management-System
- SaaS Software as a Service
- SOP Standard Operating Procedure
- TN Teilnehmende
- UI User Interface
- ZB MED ZB MED - Informationszentrum Lebenswissenschaften

# Literaturverzeichnis

[1] Deutsche Forschungsgemeinschaft. Leitlinien zur Sicherung guter wissenschaftlicher Praxis. 2022. DOI: 10.5281/zenodo.6472827.

[2] ZB MED (Hrsg.) Forschungsdaten dokumentieren: Elektronische Laborbücher. Web Page. Zugriff am 2023-09-27. URL: https://www.publisso.de/forschungsdatenmanagement/fd-dokumentieren.

[3] Chemotion ELN. Web Page. Zugriff am 2023-09-14. URL: https://chemotion.net.

[4] eLabFTW ELN. Web Page. Zugriff am 2023-09-14. URL: https://www.elabftw.net.

[5] openBIS ELN. Web Page. Zugriff am 2023-09-14. URL: https://openbis.ch.

[6] TUM Workbench. Web Page. Zugriff am 2023-09-27. URL: https://www.ub.tum.de/workbench.

[7] ResearchSpace eLab Notebook. Web Page. Zugriff am 2023-09-14. URL: https://www.researchspace.com.

[8] LabFolder ELN. Web Page. Zugriff am 2023-09-14. URL: https://www.labfolder.com.

[9] eLabJournal. More than an ELN. Web Page. Zugriff am 2023-09-27. URL: https://www.elabnext.com/products/elabjournal/.

[10] LabArchives. All Your Research in One Place. Web Page. Zugriff am 2023-09-27. URL: https://www.labarchives.com/.

[11] ZB MED - ULB Darmstadt (Hrsg.) ELN Finder. Web Page. Zugriff am 2023-09-27. URL: https://eln-finder.ulb.tu-darmstadt.de/home.

[12] ZB MED (Hrsg.) “Elektronische Laborbücher im Kontext von Forschungsdatenmanagement und guter wissenschaftlicher Praxis - ein Wegweiser für die Lebenswissenschaften”. In: (2020). DOI: 10.4126/FRL01-006422868.

[13] The ELN Consortium. Web Page. Zugriff am 2023-09-27. URL: https://github.com/TheELNConsortium.


## Weiterführende Ressourcen

- Beatrix Adam u. a. “Raus aus dem Kladdenchaos: Elektronische Laborbücher als zentrale Dienstleistung – Erfahrungen und Empfehlungen”. In: (2023). DOI: 10.17192/BFDM.2023.5.8553

- AG zu Elektronischen Laborbüchern. Web Page. Zugriff am 2023-09-27. URL: https://wiki.hhu.de/display/ELB/ELB.nrw+Startseite

- Exact instructions challenge - How do you make a Peanut Butter Jelly Sandwich. Video. Zugriff am 2023-09-27. URL: https://www.youtube.com/watch?v=Ct-lOOUqmyY

- Fabian Fink u. a. Chemotion ELN Erklärvideos. Version 1.0.2022. DOI: 10.5281/zenodo.6356844

- Fraunhofer IPA (Hrsg). Noch eine unverbindliche Liste elektronischer Laborbücher. Web Page. Zugriff am 2023-09-27. URL: https://websites.fraunhofer.de/lost-in-life-sciences/?p=52

- OER.DigiChem.NRW - eLabFTW. Web Page. Zugriff am 2023-09-27.2022. URL: https://mediathek.hhu.de/playlist/1212

- TimmSchoening.SOP Image curation and publication. 2021. DOI:10.5281/zenodo.5704846

- Timm Schoening. SOP Using Elements to manage marine image data. 2021. DOI: 10.5281/zenodo.5705219

- Henning Timm, Sarah Ann Danker und Felix M. Schmidt. Slides for eLabFTW hands-on workshop. Web Page. 2022. URL: https://duepublico2.uni-due.de/receive/duepublico_mods_00076162

- Björn Trebels. Elektronische Laborbücher - eine Einführung am Beispiel eLabFTW. 2022. DOI: 10.5281/zenodo.6956569

- ZB MED (Hrsg.) Electronic Lab Notebook ELN: Labfolder & eLabFTW. Videotutorials. Zugriff am 2023-09-27. 2022. URL: https://www.youtube.com/playlist?list=PLJYlS0FDTMq17tvYMeuI2Ct5XtykRFy0K

