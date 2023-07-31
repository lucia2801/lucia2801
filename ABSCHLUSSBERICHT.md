<h1>Individueller Abschlussbericht</h1>

Sucht man nach einer Veranstaltung, wird man auf Internetseiten wie zum Beispiel tourismus-bw.de, heidelberg.de und meinestadt.de fündig. Allerdings bieten diese Seiten weder eine Kommentarfunktion, noch lässt sich die Suche nach vielen Schlagwörtern eingrenzen.
Im Rahmen des zweiten Semesters habe ich mir deshalb gemeinsam mit Herrn Scheffelmeier und Herrn Hospotzky überlegt, einen online zugänglichen Veranstaltungskalender auf kommulaler beziehungsweise regionaler Ebene zu erstellen. Ziel dieses Veranstaltungskalenders war das Veröffentlichen von Veranstaltungen auf Gemeinde beziehungsweise Vereinsebene sowie das Editieren folgender Informationen:

<img width="414" alt="Bildschirmfoto 2023-07-31 um 10 16 51" src="https://github.com/lucia2801/lucia2801/assets/131368798/a693dcc0-37d2-43d5-9ce0-bb4ab44becb1"><br>

Darüber hinaus soll es eine Bewertungsfunktion und nach registrierter Anmeldung eine Kommentarfunktion geben, um vergangene Veranstaltungen kommentieren und bewerten zu können.

<h2>Meine Verantwortung im Team / Tasks, die ich übernommen habe</h2>

Unser Projekt haben wir in FrontEnd, BackEnd, die Vorbereitung der Serverinstanz und die Testphase untergliedert. Als Verantworlichen im Bereich FrontEnd bestimmten wir Herrn Hospotzki, aufgrund seines bereits vorhandenen technischen Vorwissens durfte Herr Scheffelmeier das BackEnd, beziehungsweise die Verbindung von FrontEnd und BackEnd übernehmen. Die Vorbereitung der Serverinstanz sowie die Testphase vielen in meinen Aufgabenbereich. 

Im Bereich der Projektplanung haben wir zu dritt ein Gantt-Diagramm erstellt und darin die für die Durchführung des Projekts nötigen Aufgaben und Ereignisse festgeshalten. Meine Aufgabe war es, dieses Diagramm zu verfeinern und mir zu überlegen, bis wann wir diese Aktivitäten abgeschlossen haben möchten. Im Nachfolgenden sieht man den ersten Entwurf unseres Gant-Diagramms vom April. Wie man dem Diagramm entnehmen kann, war unser Ziel, das Projekt bis zum 01.07.2023 abzuschließen. ...

<img width="456" alt="Bildschirmfoto 2023-07-31 um 11 17 18" src="https://github.com/lucia2801/lucia2801/assets/131368798/037d5ed0-1a2f-48a1-a499-9bea10842182"><br>

Zur Besprechung des Fortschritts unses Projektes haben wir ursprünglich geplant, uns regelmäßig montags und mittwochs zu treffen. Aus zeitlichen Gründen konnten wir diese Termine jedoch nicht immer einhalten. Im Bereich des Organisatorischen habe ich also des Öfteren die Terminabsprachen geleitet. 

Unsere Sorge war, dass jede beliebige Person unsere Veranstaltungen kommentieren kann. Wir haben uns überlegt, deshalb die Kommentar- und Bewertungsfunktion nur nach erfolgter Registrierung zu ermöglichen. Nachdem Herr Scheffelmeier ein Pop-Up-Fenster erstellt hat, habe ich mittels HTML-Forms und CSS den Code für eine Registrierungs- und Anmeldemaske für den User geschrieben. Damit die Gemeinden und Vereine neue Veranstaltungen eintragen können, habe ich zusätzlich eine Eingabemaske erstellt, um von den Vereinen Informationen über Veranstaltungsort, Veranstaltungszeit usw. anzufragen. Mit .showmodal() und .close() Funktionen gelang mir die Verknüpfung der jeweiligen Pop-Up-Fenster untereinander.
Im Folgenden sieht man zur Veranschaulichung den Code für die Registrierungsmaske, in dem ich die oben genannten Funktionen eingebaut habe, um im Falle einer bereits erfolgten Registrierung zum Anmeldefenster zu gelangen.

<img width="996" alt="Bildschirmfoto 2023-07-31 um 14 18 12" src="https://github.com/lucia2801/lucia2801/assets/131368798/701c2240-082f-479e-9655-ee55d07d65e6"><br>


Eine Voraussetzung für unseren Veranstaltungskalender war, dass nur Gemeinden und Vereine neue Veranstaltungen posten können. Um dies zu gewährleisten, habe ich eine Verifizierungsmaske für Vereine erstellt. Abgefragt weren hier der Vereinsname, ein Ansprechpartner, die E-MAil-Adresse und die Vereinsregisternummer (VR-Nummer) des Vereins. Ziel war es, mit Betätigen des Bestätigungsbuttons diese Informationen automatisch per Mail an Hernn Scheffelmeier, Herrn Hospotzki und mich zu schicken, damit wir anschließend überprüfen können, ob diese Vereinsregisternummer im Vereinsregister vorhanden ist und es sich um einen offiziell eingetragenen Verein handelt. Mit folgendem Code ist es mir gelungen, eine E-Mail zu erstellen, in dem die oben abgefragten Informationen aufgelistet dargestellt werden. Allerdins bewirkte dieser Code nur die Öffnung des E-Mail-Programms und der erstellten E-Mail und nicht wie gewünscht die automatische Versendung dieser Mail. Da dieser Vorgang nicht besonders nutzerfreundlich wäre, recherchierte ich im Internet und fand heraus, dass die Programmiersprache PHP dieses Problem beheben könnte, weshalb ich mich grob in die Thematil eingearbeitet habe. Nach Absprache mit dem Team haben wir uns jedoch darauf geeinigt, die Verifizierung auf andere Art und Weise zu gestalten. Aufgrund Zeitmangels konnten wir diese jedoch nicht mehr zuende stellen.

<img width="1309" alt="Bildschirmfoto 2023-07-31 um 15 47 12" src="https://github.com/lucia2801/lucia2801/assets/131368798/36654982-dfde-4346-bcc9-aec49fd3533b">

<h2>Zusammenarbeit im Team</h2>
