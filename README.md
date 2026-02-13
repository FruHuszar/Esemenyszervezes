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
...

## Dokumentáció

### Használt technológiák
- draw.io: Weblap grafikai megtervezése
- html, css: Weboldal technikai megvalósítása
- Adobe illustrator: Színek egységesítése a képek és weblap között
- github: A projekt során verziókezelő rendszer (Git) került alkalmazásra a változások nyomon követésére, és a csoportmonka könnyítésére.

### Tanult technológiák és hibakezelés
- A % oldalszélességbe beletartozik a scrollbar is. Ezért amikor az egyik aloldalon olyan hosszú a szöveg, hogy megjelenik a böngésző scrollbarja, akkor a többi aloldalhoz képest változhat az oldal szélessége. 
Ennek megoldása, hogy a scrollbarnak MINDIG fenntartunk helyet, akkor is ha nincs az oldalon.
```html
html {
  scrollbar-gutter: stable;
}
```
### Megjegyzések
...
