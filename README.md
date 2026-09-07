# Auto škola Faring BG - sajt

Statičan sajt, jedna HTML strana po stranici. Svaki fajl je samostalan (stil, skriptovi i logo su ušiveni u njega), pa se tekst menja direktno u tom fajlu.

| Fajl | Stranica |
| --- | --- |
| `index.html` | Početna |
| `o-nama.html` | O nama |
| `galerija.html` | Galerija |
| `cenovnik.html` | Cenovnik |
| `vodic.html` | Vodič |
| `kontakt.html` | Kontakt |

Meni, hamburger meni i futer na svakoj strani vode na ostale fajlove običnim linkovima.

## Hostovanje na GitHub Pages

1. Napravi repozitorijum (npr. `faring-bg`).
2. Prebaci sav sadržaj ove fascikle u root repozitorijuma.
3. **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)` → **Save**.
4. Sajt je za minut-dva na `https://<korisnik>.github.io/<repo>/`.

Za sopstveni domen: **Settings → Pages → Custom domain**, a kod registrara CNAME na `<korisnik>.github.io`.

## Izmena teksta

Otvori fajl te stranice u bilo kom uređivaču teksta i promeni tekst između tagova. Ako menjaš nešto što stoji na svim stranama (telefon, adresa, meni, futer), izmeni to u svakom fajlu.

## Fotografije

Mesta za fotografije stoje kao sivi placeholderi sa opisom šta tu ide. Kad pošalješ slike, ubacujemo ih kao `<img>` u fasciklu `images/`.
