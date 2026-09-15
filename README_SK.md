# Nasadenie stránky TEACHERS na GitHub Pages

Tento priečinok je pripravený na nasadenie na `https://teachers.sk`.

## Čo nahrať

Do koreňa verejného GitHub repozitára nahrajte **celý obsah** tohto priečinka vrátane skrytého súboru `.nojekyll` a súboru `CNAME`.

## Nastavenie v GitHub

V repozitári otvorte **Settings → Pages**, zvoľte nasadenie z vetvy, do ktorej boli súbory nahraté, a vyberte priečinok `/ (root)`. GitHub musí pri vlastnej doméne zobrazovať `teachers.sk` a má byť zapnuté **Enforce HTTPS**.

## DNS

V DNS správe domény nastavte apex doménu `teachers.sk` podľa aktuálnych pokynov GitHub Pages. Ak používate `www.teachers.sk`, nastavte ho ako CNAME na používateľský GitHub Pages hostname a presmerujte ho na hlavnú verziu `https://teachers.sk/`.

## URL adresy

- Domovská stránka: `https://teachers.sk/`
- Výstupy 1. ročníka: `https://teachers.sk/prvy-rocnik/`

Súbor `prvy-rocnik.html` zostal len ako kompatibilná alternatíva so značkou `noindex`; Google indexuje čistú URL s lomkou.

## Po publikovaní

1. Skontrolujte, že fungujú obe URL vyššie cez HTTPS.
2. Pridajte vlastníctvo `https://teachers.sk/` do Google Search Console.
3. V Search Console odošlite `https://teachers.sk/sitemap.xml`.
4. Odoslanie jednotlivých URL na indexovanie je vhodné až po stabilnom nasadení; nerequestujte indexovanie Framer subdomény.
