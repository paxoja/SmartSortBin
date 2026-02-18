# SmartSort Bin – webstránka projektu

Webstránka k projektu **SmartSort Bin** (tím SORT – Smart Optimized Recycling Team) v rámci predmetu MSI. Statická stránka pripravená na publikovanie na GitHub Pages.

## Štruktúra

- **index.html** – domovská stránka (názov projektu, slogan, úvod)
- **o-projekte.html** – anotácia projektu (popis, cieľ, spätná väzba, spoločenský prínos)
- **tim.html** – zoznam členov tímu SORT
- **zadania.html** – archív týždenných výstupov (prezentácie, QA dokumenty)
- **css/style.css** – vlastné štýly (zelené akcenty, responzívny layout)
- **assets/** – anotácia, obrázky; pre každý týždeň vlastný priečinok:
  - **assets/tyzden2/** – výstupy Týždňa 2 (prezentacia.pdf, anotacia.pdf, qa.pdf)
  - **assets/tyzden3/** – výstupy Týždňa 3 (zhrnutie, prezentácia, QA)
  - **assets/tyzden4/** … – ďalšie týždne podľa potreby

## Údržba

### Pridanie nového týždňa v sekcii Zadania

1. Vytvorte priečinok v `assets/`, napr. `assets/tyzden4/`.
2. Vložte do neho súbory (prezentácia, anotácia, QA dokument) – odporúčané názvy sú v súbore `README.txt` v priečinku daného týždňa.
3. Otvorte `zadania.html`, skopírujte jeden blok karty (od `<section class="card mb-4">` po `</section>`) a upravte nadpis a odkazy na nové súbory v `assets/tyzden4/`.

### Aktualizácia tímu

V súbore `tim.html` upravte karty členov: meno, e-mail, prípadne rolu. Pre viac členov skopírujte jednu kartu (celý `<div class="col-md-6 col-lg-4">` … `</div>`) a upravte údaje.

## GitHub Pages

1. Nahrajte obsah tohto priečinka do repozitára (napr. do vetvy `main`).
2. V repozitári: **Settings → Pages**.
3. V časti **Source** zvoľte branch (napr. `main`) a priečinok:
   - Ak sú súbory v **root** repozitára, zvoľte **/ (root)**.
   - Ak je web v podpriečinku (napr. `web/`), buď zvoľte tento priečinok ako root pre Pages, alebo presuňte obsah webu do rootu repozitára.
4. Uložte. Stránka bude dostupná na adrese `https://<vase-pouzivatelske-meno>.github.io/<nazov-repozitara>/`.

## Technológie

- HTML5, CSS3
- Bootstrap 5 (CDN)
- Žiadny backend – vhodné pre GitHub Pages

## Povinné výstupy MSI na stránke

- Webstránka projektu (táto stránka)
- Prezentácia používateľských požiadaviek (odkaz v sekcii Zadania)
- QA dokument (odkaz v sekcii Zadania)
- Ďalšie zadania v priebehu semestra (pridávané v sekcii Zadania)
