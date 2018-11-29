---
title: "Stadier i programvaruprojekt"
geometry: margin=1.5cm
fontfamily: merriweather
fontfamilyoptions: sfdefault
fontsize: 10pt
output:pdf_document:
---

Det finns ungefär 7 stadier i programvaruprojekt, vissa koncept kan flyta mellan nivåer, men i allmänhet ser det ut så här:


|Stadie				|Innehåll						|Resultat
|:------------------------------|:------------------------------------------------------|:----------------------
|0. Kravanalys/Förstudie	|Analys av krav från intressenter			|Kravspecifikation
|				|							|Lösningsförslag
|Görs före själva projektet	|Förberedelse av, och diskussion om lösningsförslag	|Lönsamhetsanalys
|börjat				|							|Budget
|				|Analys av projektets genomförbarhet			|WBS (Work Breakdown Structure)
|Uppgift:			|Finns det tillräckligt med:				|Milstolpeplan (t.ex. GANTT-schema)
|Analysera ifall projektet	|pengar, kunskap, tid, resursser			|	
|går/lönar sig att genomföra	|							|	
|				|Lönsamhetsanalys, är projektet värt att genomföra?	|
|Bestäm tydliga mål		|Kommer projektet leda till mera värde (pengar)		|
|för projektet			|							|
|-------------------------------|-------------------------------------------------------|-------------------------
|1. Planering			|Detaljerad planering av programvaran			|Funktionell design
|				|Hur ska programvaran bete sig? (funktionell design)	|Teknisk design
|Uppgift:			|Hur ska programvaran implementeras? (teknisk design)	|WBS
|Tänk igenom programvarans	|							|Milstolpeplan (t.ex. GANTT-schema)
|innehåll och beteende		|Säkerställ tillgången till resursser (teknisk personal)|
|				|under projektets gång					|
|Definiera milstolpar och deras |							|
|datum, fastställ tidtabell	|Använder sig av lösningsförslag, kravspecifikation,	|
|				|WBS från förra steget					|
|-------------------------------|-------------------------------------------------------|-------------------------
|2. Implementering		|Följ upp projektet med hjälp av projektmöten, 		|Burndown-graf (visar hur projektet framskrider)
|				|reagera ifall projektet inte hinner till 		|Programvaran
|Uppgift:			|milstolparnar eller går över budget 			|Dokumentation
|Utför planen, följ upp		|							|
|projektet			|Dela ut uppgifter inom teamet				|
|				|							|
|				|Programmera, testa, dokumentera			|
|				|							|
|-------------------------------|-------------------------------------------------------|--------------------------
|3. Testning			|Kan bestä av:						|Testresultat
|				|- förbestämda tekniska tester 				|
|Uppgift:			|	- stresstest över nätverk			|
|Verifiera att programvaran	|	- performanstest				|
|fungerar som den skall		|- användartestning 					|
|				|	- vanligen VIKTIGAST!				|
|				|- säkerhetstestning 					|
|				|	- penetration testing				|
|				|	- blue team vs red team				|
|				|							|
|-------------------------------|-------------------------------------------------------|-------------------------
|4. Ibruktagning		|Installera programvaran på servrar, eller 		|Användbar tjänst
|				|distribuera den till användare				|Bruksanvisningar
|Uppgift:			|							|	
|Installera programvaran 	|Utbilda användarna, utibilda stödpersonalen 		|
|i sin omgivning så att 	|(om annan än utvecklingspersonalen)			|
|användare kan använda den	|							|
|-------------------------------|-------------------------------------------------------|---------------------------
|5. Underhåll			|Se till att tjänsten hålls uppe, dvs lös problem 	|
|				|med nätverkstjänst, servrar som brinner, användare	|
|Efter projektet tagit slut	|som skriker, och brottslingar eller statsmakter som 	|
|				|försöker bryta sig in på ditt nätverk.			|
|Uppgift:			|							|
|Uppehåll tjänstens brukbarhet	|Svara på/lös stödförfrågningar från användare		|
|				|Förbättra säkerheten av programvaran vid behov, t.ex om|
|				|nya hot publiceras "Täpp till luckor"			|
|-------------------------------|-------------------------------------------------------|--------------------------
|6. Urbruktagning		|Trappa ner tjänstenivån långsamt, kan även ske 	|Meddelande om att stödet tar slut
|				|naturligt (Ingen vill använda ditt program mera)	|
|Uppgift:			|							|
|Se till att tjänsten tas ur	|Se till att alternativ för att lösa samma problem	|
|bruk utan att störa någon	|som tjänsten löste finns till förfogande		|
|annan verksamhet		|							|
|				|Ta ner alla instansser av servern (ifall det finns)	|
|				|							|
|				|Skicka ut meddelanden om att tjänsten inte längre stöds|
