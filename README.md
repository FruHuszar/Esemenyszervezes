# Eseményszervezés

## Projekt leírása
Flexbox órai gyakorló feladat, eseményszervező weblap megvalósításban, működő űrlap aloldallal.

## Csapattagok
- Horváth Levente Roland 
- Huszár Fruzsina Anna
- Harnos Vanda Alina

## Munkafelosztás áttekintése
A projekt három fő szerepkörre bontva került megvalósításra.

### Tervezés
- Inspirációk gyűjtése: Közös
- Wireframe tervezés: Vanda
- Readme-be írt dokumentáció: Közös

### Megvalósítás
- index.html: Levi
- form.html: Vanda
- event.html: Fru

- style.css: Közös
- layout.css: Közös
- nav.css: Fru
- form.css: Vanda
- event.css: Levi

### Tesztelés
Tesztelésre vár

## Dokumentáció

### Használt technológiák
- draw.io: Weblap grafikai megtervezése
- html, css: Weboldal technikai megvalósítása
- Adobe illustrator: Színek egységesítése a képek és weblap között
- github: A projekt során verziókezelő rendszer (Git) került alkalmazásra a változások nyomon követésére, és a csoportmonka könnyítésére.

### Tanult technológiák és hibakezelés
1. A % oldalszélességbe beletartozik a scrollbar is. Ezért amikor az egyik aloldalon olyan hosszú a szöveg, hogy megjelenik a böngésző scrollbarja, akkor a többi aloldalhoz képest változhat az oldal szélessége. 
Ennek megoldása, hogy a scrollbarnak MINDIG fenntartunk helyet, akkor is ha nincs az oldalon.
```html
html {
  scrollbar-gutter: stable;
}
```
2. CSS Specificity és !important használata
A globális elrendezés (layout.css) fix képernyős Flexbox struktúrát és specifikus pozicionálásokat alkalmaz. Bizonyos esetekben – például az Esemény aloldal görgethetősége (event.css) és a mobilnézet átrendezése (layout.css media query) – a stílusok ütköztek. A kívánt megjelenés kényszerítéséhez és a korábbi szabályok felülírásához !important kulcsszót használtunk. Ennek megoldása
```
html, body {
  display: block !important;
  overflow-y: auto !important;
}

/* layout.css - mobil elrendezés javítása */
@media (max-width: 1000px) {
  article {
    padding: 30px 15px !important;
  }
  .icons {
    position: static !important;
    transform: none !important;
  }
}
```
### Megjegyzések
Továbbfejlesztésre vár
