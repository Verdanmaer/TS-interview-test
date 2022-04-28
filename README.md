# TS-interview-test

## Teoretická část
Otevřete si stránku https://formats.r2b2.cz/view/vhs04lwnemmy4q4 a pomocí devtools zodpovězte následující otázky. Není nutné stahovat a upravovat celý kód.


1. U elementu header.c-header upravte jednu hodnotu již existující CSS vlastnosti tak, aby byla hlavička vidět i při odscrollování.
   - **position: fixed;**

2. Hlavní nadpis - h1 - má v inline stylu nastavenou barvu písma na černou. Proč se i přesto zobrazuje růžově?
   - **Protože má v CSS nastavenou barvu na růžovou s !important, což přepíše všechny předchozí pravidla.**


3. Z jakého důvodu se nezobrazuje obrázek .hero-media > .img > img ?
   - Místo *https://prima-ott...* má být *https://nova-ott...*


4. Jak byste bez použití inline stylů obarvil/a na modro pozadí odstavce začínajícího větou “Typickou reakcí většiny divokých zvířat by byl útěk.”?
   - **.c-rte p:nth-last-child(4) { background: blue }**


5. Logo v hlavičce by mělo proklikávat na stránku https://tn.nova.cz/. Proč se tak reálně neděje?
   - U *'a'* tagu má být **href** místo **src**.
