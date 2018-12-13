---
---
Kmom05 webbplatsers laddningstider
==================================

Uppgiften går ut på att se hur en sidas uppbyggnad med bla. bilder kan påverka laddningstiderna.

Urval
-----------------------

Jag valde BTH.se, Miun.se och KTH.se. BTH hade jag med från förra rapporten, sedan följde jag
Emils förslag att ställa 3 lika sidor mot varandra. Därav blev valet 3 olika högskolor.

Metod
-----------------------

Metoden enligt spec. jag använde devtools för at mata laddningstid, storlek och hur många resurser som laddas.

Resultat
-----------------------
[Rådata](https://docs.google.com/spreadsheets/d/1AIJJp7po22BMVLFd7seUCB1flgDoMhsAvgEEVcmlBNo/edit?usp=sharing)

[FIGURE src=image/bth.jpg?w=300 caption="BTH"]
[PageSpeed](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fwww.bth.se%2F)

Eventuellt använda format med högre komprimering av bilder.
Sidan har mycket bilder och video. Möjligtvis skala ner vid mobil version.

[FIGURE src=image/miun.jpg?w=300 caption="MIUN"]
[PageSpeed](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fwww.miun.se)

Eventuellt använda format med högre komprimering av bilder.
Sidan har mycket bilder. Möjligtvis skala ner vid mobil version.

[FIGURE src=image/kth.jpg?w=300 caption="KTH"]
[PageSpeed](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fwww.kth.se%2F&tab=desktop)

Ta bort resurser som blockerar renderingen. Infoga JS/CSS kod direkt i sidan. Sidans prestanda är bra. Men designen känns rörig. Designen i BTH och MIUN känns lugnare.

Analys
-----------------------

Det vanligaste som påverkade laddningstiderna var antalet bilder som laddades. PageSpeed förslog hårdare komprimering med nyare format.

KTH var överlägset snabbast enligt mätdatat, men ingen skillnad gick att se visuellt. BTH var långsammast enligt datat och hade den tyngsta sidan. Vinnare blir BTH för att trots mera bilder så syns ingen skillnad.

Upp till 1,5-2s anser jag vara en snabb sida. Samtliga sidor klarar mina referenser vad gäller hastighet.

Övrigt
-----------------------

Denna rapport är skapad av Roy Johansson.
