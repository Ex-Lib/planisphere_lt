#### Planisphere generator with the option of Lithuanian language

This repository contains Python scripts that can be used to produce a cardboard cut-and-glue kit to make your own model planisphere in Lithuanianan language (as well as other languages).

### Sukamasis žvaigždėlapis (planisfera) lietuvių kalba V.1

#### Pasigaminkite kartoninį sukamojo žvaigždėlapio (planisferos) modelį V.1

Čia pateikiami Python skriptai, kuriuos galima naudoti norint pasigaminti kartoninį sukamojo žvaigždėlapio arba planisferos modelį ir lietuvių kalba (+ kelios kitos kalbos), skirtą bet kokiai pasaulio vietai. Lietuvos geografinės platumos: Šiaurėje – 56°27'N (į šiaurės vakarus nuo Aspariškių kaimo, Biržų raj.); Pietuose – 53°54'N (į pietryčius nuo Kabelių ir į pietus nuo Musteikos kaimų, Varėnos raj.). Platumos skirtumas iki 5° nėra reikšmingas planisferos veikimui.

#### Įvadas

Planisfera - tai paprastas sukamasis žvaigždėlapis, kuriame matomos žvaigždės, matomos naktiniame danguje bet kuriuo konkrečiu metu. Sukant diską rodoma, kaip žvaigždės juda dangumi naktį ir kaip skirtingu metų laiku matomi skirtingi žvaigždynai.Planisfera yra puikus dangaus orientyras, ieškant žvaigždynų, ūkų, galaktikų ir planetų. 

Kam reikalinga kartoninė, save rankomis suklijuota planisfera, kai telefone yra daygybė žvaigždėlapio programėlių? Jeigu jums kyla toks klausimas - šis Github kampelis yra ne jums, negaiškite čia savo brangaus laiko.

#### Kaip naudoti

Norėdami sukurti visų platumų planisferos modelius penkių laipsnių intervalais, paleiskite skriptą `main_planisphere.sh`. Planisferos dalys (.svg, .png, .pdf) sugeneruojamos "Output" direktorijoje. Planisferos sugeneruojamos įvairioms skripte nurodytoms platumoms (kas 5 laipsniai) ir visomis skripte nurodytomis kalbomis. Geriausia naudoti kažkurią linux OS su instaliuotu pytonu ir latex. Puikiai veikia su Raspberry pi minikompiuteriu ir Bookworm OS. Suteikite skriptui reikiamus linux saugumo leidimus (chmod 777 main_planisphere.sh)

#### Apribojimai

Planisferos netinka, kai jos naudojamos arti ekvatoriaus. Šioje saugykloje esantys skriptai neleidžia kurti planisferų platumoms tarp 15 laipsnių šiaurės platumos ir 15 laipsnių pietų platumos, nes dangaus ašigalis yra per arti horizonto.

#### Autorinės teisės

Ši kodą sukūrė Dominic Ford <https://dcford.org.uk>. Jis platinamas pagal „Gnu General Public License V3“.

