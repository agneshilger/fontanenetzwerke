# fontanenetzwerke

In diesem Repository teile ich die von mir manuell in CATMA annotierten Daten zur Erzeugung von Figurennetzwerken für Theodor Fontanes Roman 'Der Stechlin' sowie den Notebook, mit dem sich aus diesen Daten Netzwerke erzeugen lassen. Das zugehörige Projekt beschreibe ich in einem Blogpost der demnächst veröffentlicht und hier verlinkt wird.

Bei der Annotation der Daten wurden folgende Richtlinien* befolgt:

## Annotation von Sprechakten
Für den ersten Netzwerktyp wurden für alle Sprechakte des Romans der gesprochene Text annotiert und der/die Sprecher:in, sowie die Figur(en), an die sich der Sprechakt richtet, als Properties vergeben.
Nicht als Sprechakt erfasst wurden Sätze, die Leute im Allgemeinen sagen, typische Redeweisen einer Figur, die losgelöst vom Gesprächskontext wiedergegeben werden und Briefe.

### Property Sprecher:in 
Wird der Sprecher oder die Sprecherin im Text nicht durch den Erzähler benannt, wurde versucht, die entsprechende Information aus dem Kontext zu erschließen. Meistens werden die Bezeichnungen im Text weggelassen, wenn sich zwei Figuren in einem Gespräch befinden und allein durch die Markierung unterschiedlicher Sprechakte durch Anführungszeichen klar ist, wer spricht. Auch wenn mehr als zwei Figuren am Gespräch beteiligt sind und der/die Sprecher:in nicht benannt wird, kann es sein, dass er/sie sich dennoch zuordnen lässt, etwa wenn die Figur eine besonders charakteristische Sprechweise hat. 
Nicht zugeordnete Sprechakte, deren Sprecher:in sich nicht plausibel aus dem Kontext erschließen lässt, wurden nicht erfasst. Da diese Fälle äußert selten sind, ist das nicht weiter schlimm.

### Property Gegenüber
In der Property 'Gegenüber' werden grundsätzlich alle Figuren erfasst, die der Sprecher oder die Sprecherin adressiert, nicht alle anwesenden Figuren. Dabei kann es sein, dass eine bestimmte Figur als Gegenüber angesprochen wird oder mehrere bestimmte Personen werden direkt angesprochen. Es kommt beispielsweise häufig vor, dass ein Sprechakt sich zunächst an die vorherige Sprecherin richtet, am Ende aber eine andere adressiert. Ein Sonderfall solcher Sprechakte sind diejenigen, bei denen die Gesprächssituation tatsächlich wechselt und sich die Äußerung jeweils nur an die nun Adressierten richtet, ein Beispiel: Wenn Dubslav von Stechlin im zweiten Kapitel Rex und Czako bittet, um sieben Uhr zum Abendessen zu erscheinen, wendet er sich anschließend an Engelke und bittet ihn, die Herren auf ihre Zimmer zu führen. Dieser Fall, obwohl die Äußerung innerhalb einer Einheit von Anführungszeichen erfolgt, wird als zwei Sprechakte erfasst.  Schließlich kommt es noch vor, dass alle, oder zumindest fast alle Anwesenden adressiert werden, etwa bei Wendungen wie „meine Herren“. Dann werden alle anwesenden Figuren (bzw. hier männlichen Figuren) als Gegenüber erfasst.
Natürlich gibt es auch Sprechakte, deren Gegenüber nicht explizit adressiert wird. Antwortet eine Figur auf den Sprechakt einer anderen, wird der Sprecher oder die Sprecherin des vorherigen Sprechaktes als Gegenüber annotiert. Bei Gesprächen in größeren Runden wird im ersten Sprechakt häufig noch niemand adressiert, als Gegenüber werden dann alle anwesenden und grundsätzlich an der Gesprächssituation beteiligten Figuren erfasst. Stellt eine Figur andere Figuren(gruppen) einander vor, so werden alle an der Vorstellungsrunde Beteiligten als Gegenüber annotiert. Ähnliches gilt für Reden und Toasts, hier werden alle anwesenden und an der Gesprächssituation unmittelbar beteiligten Figuren als Gegenüber erfasst. Eine Ausnahme bilden lediglich Reden in sehr großen Runden, bei denen nur ein kleiner Teil der Anwesenden namentlich genannt wird und bei denen die Gesprächssituation unpersönlich ist. Solche Reden sind allerdings äußerst selten.

### Sonderfälle
Gibt eine Figur in Gedanken oder Worten Sprechakte anderer Figuren wörtlich oder indirekt wieder, wird das entsprechend als eigener Sprechakt gefasst. Diese Annotationspraxis ist vor allem dadurch gerechtfertigt, dass im 'Stechlin' gelegentlich ausgesparte Gespräche zu einem späteren Zeitpunkt durch eine der beteiligten Figuren wiedergegeben werden. Beispielsweise wird das wichtige Gespräch zwischen Lorenzen und Woldemar im fünften Kapitel nicht wiedergegeben, dafür aber später von Woldemar im 15. Kapitel nacherzählt.

## Annotation von Referenzen auf abwesende Figuren
Für den zweiten Netzwerktyp wurde erfasst, wenn eine Figur über eine andere Figur, die derzeit nicht unmittelbar anwesend oder an der Gesprächssituation beteiligt ist, spricht. 
Referenzen der Figuren auf sich selbst wurden nicht erfasst. Ebenso wurden Referenzen auf nicht näher (v.a. mit Namen) beschriebene Figuren der Vergangenheit nicht erfasst. Mit der Property Polarität wurde zudem versucht, die Einstellung des Sprechers/der Sprecherin gegenüber der referierten Figur zu erfassen. Hier lassen sich schwer allgemeine Richtlinien treffen, die Frage nach der Polarität wurde im Einzelfall nach dem Kontext bewertet, wenn die Polarität unklar war wurde sie als „neutral/irrelevant“ getaggt. Nicht erfasst wurden mit diesen Annotationsrichtlinien Referenzen in Briefen.



* Da die Annotationen nicht noch einmal korrekturgelesen wurden, kann ich nicht garantieren, dass im einen oder anderen Einzelfall Fehler enthalten sein mögen.
