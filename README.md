### Sukamasis žvaigždėlapis (planisfera) ir Lietuvių kalba *** Planisphere generator with the option of Lithuanian language 


### Pasigaminkite kartoninį sukamojo žvaigždėlapio (planisferos) modelį / Make your own cardboard model planisphere

Čia pateikiami Python skriptai, kuriuos galima naudoti norint pasigaminti kartoninį sukamojo žvaigždėlapio arba planisferos modelį ir Lietuvių kalba (+ kelios kitos kalbos), skirtą Lietuvos geografinėms platumoms. 

This repository contains Python scripts that can be used to produce a cardboard cut-and-glue kit to make your own model planisphere in Lithuanianan language (as well as other languages).

### Įvadas

Planisfera - tai paprastas sukamasis žvaigždėlapis, kuriame matomos žvaigždės, matomos naktiniame danguje bet kuriuo konkrečiu metu. Sukant diską rodoma, kaip žvaigždės juda dangumi naktį ir kaip skirtingu metų laiku matomi skirtingi žvaigždynai.

### Kaip naudoti

Norėdami sukurti visų platumų planisferos modelius penkių laipsnių intervalais, paleiskite skriptą `main_planisphere.sh`. Planisferos dalys (.svg, .png, .pdf) sugeneruojamos "Output" direktorijoje. Planisferos sugeneruojamos įvairioms skripte nurodytoms platumoms (kas 5 laipsniai) ir visomis skripte nurodytomis kalbomis. Puikiai veikia su Raspberry pi minikompiuteriu.

### Apribojimai

Planisferos netinka, kai jos naudojamos arti ekvatoriaus. Šioje saugykloje esantys skriptai neleidžia kurti planisferų platumoms tarp 15 laipsnių šiaurės platumos ir 15 laipsnių pietų platumos, nes dangaus ašigalis yra per arti horizonto.

### Autorinės teisės

Ši kodą sukūrė Dominic Ford <https://dcford.org.uk>. Jis platinamas pagal „Gnu General Public License V3“.

