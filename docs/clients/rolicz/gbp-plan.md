# Rolicz – wykończenia wnętrz · Plan Google Business Profile (GBP)

Cel: top 3 w „Local Pack” Google Maps na frazy typu *wykończenia wnętrz [miasto]*, *remont mieszkania [miasto]*, *glazurnik / gładzie / malowanie [miasto]*.

Google rankuje lokalnie według 3 czynników: **trafność** (kategorie, usługi, treść), **odległość** (nie mamy wpływu – firma usługowa ⇒ obszar obsługi), **renoma** (opinie, zdjęcia, aktywność, linki/cytowania). Plan uderza w 1 i 3.

---

## 0. Dostęp i narzędzia

| Co | Narzędzie | Status |
|---|---|---|
| Publikacja postów, edycja profilu, godziny, raporty | **Markifact → Google Business Profile** (`business_profile_*`) | ❌ brak połączenia – podłączyć na markifact.com/app/connections kontem, które jest właścicielem/menedżerem wizytówki |
| Odczyt konkurencji, opinii, pozycji na mapie | Composio → Google Maps | ✅ (dzienny limit API chwilowo wyczerpany) |
| Magazyn zdjęć | Composio → Google Drive | ✅ |
| Strona www / GSC | Composio → Google Search Console | ✅ (jeśli strona istnieje) |
| Krótkie wideo „przed/po” | OpenMontage (ten repo) | ✅ |

Composio nie ma natywnego zapisu do GBP (tylko odczyt Map) – dlatego publikujemy przez Markifact.

---

## 1. Fundament profilu (tydzień 1, jednorazowo)

1. **Nazwa** = nazwa używana w realnym świecie (szyld, auto, Facebook, wizytówki) – u nas **„Zygmunt Rolicz”**, marka od 2007 r. Nazwa z rejestru/księgowości (Imperium Group) nie musi być na GBP. Bez dopychania miast i usług → ryzyko zawieszenia.
2. **Kategoria główna**: *Wykonawca robót wykończeniowych* / *Firma remontowa* (sprawdzimy `business_profile_search_categories` + co mają liderzy w okolicy). **Dodatkowe** (do 9): Glazurnik, Malarz, Tynkarz, Firma remontowo-budowlana, Montaż płyt g-k, Układanie podłóg itd. – tylko to, co faktycznie robicie.
3. **Firma usługowa**: ukryć adres, ustawić **obszar obsługi** (miasto + ościenne gminy, max ~2 h dojazdu, do 20 obszarów).
4. **Usługi**: każda usługa osobno, z opisem 300–750 znaków i (opcjonalnie) ceną „od”. Opisy zawierają naturalnie frazy + miasta.
5. **Opis firmy** (750 znaków): kim jesteście, od kiedy, co robicie, gdzie, czym się wyróżniacie (terminowość, gwarancja, sprzątanie po pracy).
6. **NAP spójny wszędzie**: ta sama nazwa, telefon, www na GBP, stronie, Facebooku, Oferteo, Fixly, Panorama Firm, pkt.pl, Zumi, Cylex. Spójność = sygnał zaufania.
7. **Strona www**: link UTM (`?utm_source=gbp&utm_medium=organic`) → mierzymy ruch. Na stronie: podstrona na każdą usługę + miasto, mapa, opinie.
8. Godziny, telefon, WhatsApp/wiadomości, atrybuty (np. „bezpłatna wycena”, „faktura VAT”).

## 2. Zdjęcia – skąd brać

**Tylko prawdziwe zdjęcia z realizacji.** Google karze za stocki i AI udające realizacje (polityka treści + nieuczciwe wobec klienta). AI wolno użyć tylko do grafik ofertowych (np. tło z tekstem „Wolne terminy w listopadzie”).

Proces (zero wysiłku dla ekipy):

1. Folder Google Drive: `Rolicz/Realizacje/RRRR-MM_miasto_typ-pracy/` (np. `2026-10_Kielce_lazienka/`).
2. Ekipa wrzuca z telefonu **przed – w trakcie – po** (5–15 zdjęć na zlecenie). Telefon poziomo, światło dzienne, posprzątane, bez twarzy klientów i numerów mieszkań.
3. Claude co tydzień przegląda folder, wybiera najlepsze, opisuje, publikuje.

Na start (jednorazowo): logo, zdjęcie w tle, zespół przy pracy, auto firmowe z logo, 20–30 zdjęć z archiwum realizacji.

Bonus: z sekwencji przed/po robimy w OpenMontage 15–30 s wideo pionowe → GBP (wideo), Facebook, Instagram, TikTok.

## 3. Posty – co i jak często

**Rytm: 2 posty / tydzień** (wt + pt), **5–10 nowych zdjęć / tydzień**. Regularność > ilość.

Rotacja typów (cykl 4-tygodniowy):

| Tydz. | Wtorek | Piątek |
|---|---|---|
| 1 | Realizacja: łazienka (przed/po) | Porada: „Jak przygotować mieszkanie do remontu” |
| 2 | Realizacja: gładzie + malowanie | Oferta/terminy: „Wolne terminy od …, bezpłatna wycena” |
| 3 | Realizacja: podłogi / zabudowa g-k | Za kulisami: ekipa, materiały, sprzęt |
| 4 | Realizacja: całe mieszkanie | Opinia klienta (cytat + zdjęcie) |

Szablon posta „Realizacja” (150–300 słów, max 1500 znaków):

```
[Typ pracy] w [dzielnica/miasto] – [efekt w 1 zdaniu]
Zakres: … (3–5 punktów)
Czas realizacji: X dni. Materiały: …
Co było wyzwaniem i jak to rozwiązaliśmy.
Planujesz [typ pracy] w [miasto] i okolicach? Bezpłatna wycena.
CTA: Zadzwoń
```

Zasady: naturalne frazy lokalne (miasto/dzielnica), konkretne liczby, zawsze CTA (Zadzwoń / Więcej), 1 zdjęcie główne z realizacji, zero numeru telefonu w treści (Google odrzuca).

## 4. Opinie – największa dźwignia

- **Cel: 4–8 nowych opinii / miesiąc**, równomiernie (nagłe skoki wyglądają podejrzanie).
- Prośba **w dniu odbioru prac**: SMS/WhatsApp z krótkim linkiem do opinii + QR na wizytówce papierowej i fakturze.
- Podpowiedź dla klienta: „Napisz, co robiliśmy i w jakim mieście” → słowa kluczowe w opiniach pomagają w rankingu.
- **Odpowiedź na każdą opinię w 24–48 h** (Claude przygotowuje, Wy akceptujecie). Negatywne: spokojnie, rzeczowo, propozycja kontaktu.
- Nie wolno: kupować opinii, dawać rabatu za opinię, pisać z kont rodziny.

## 5. Poza wizytówką (renoma)

- Cytowania w katalogach (lista w pkt 1.6) – 1 raz, potem utrzymanie.
- Linki lokalne: hurtownie budowlane, sklepy z płytkami, deweloperzy, lokalne portale (artykuł „jak wybrać ekipę”).
- Facebook + Instagram z tymi samymi treściami (recykling postów).

## 6. Pomiar (co miesiąc)

`business_profile_get_report`: wyświetlenia w Mapach/Wyszukiwarce, połączenia, kliknięcia www, prośby o trasę. Dodatkowo ręczny „grid check” pozycji na 3–5 fraz w kilku punktach miasta. Raport 1-stronicowy + wnioski na kolejny miesiąc.

## 7. Automatyzacja z Claude

1. **Poniedziałek** (zadanie zaplanowane): Claude czyta nowe zdjęcia z Drive, pisze 2 posty na tydzień + odpowiedzi na nowe opinie → wysyła do akceptacji (mail/czat).
2. Po akceptacji: publikacja/zaplanowanie przez Markifact (`business_profile_publish_post` z datą).
3. **1. dzień miesiąca**: raport wyników.

## 8. Harmonogram startu

| Kiedy | Co |
|---|---|
| Dzień 1–2 | Podłączenie GBP w Markifact, audyt profilu i 3–5 konkurentów z top 3 |
| Tydzień 1 | Fundament (pkt 1), 20–30 zdjęć, folder Drive, link do opinii + QR |
| Tydzień 2 | Pierwsze posty, prośby o opinie do ostatnich 10–20 klientów |
| Tydzień 3–4 | Katalogi/NAP, start automatyzacji |
| Miesiąc 2–3 | Rytm + pierwsze wyniki; realnie top 3 w 2–4 mies. (zależy od konkurencji) |

---

## Potrzebne od Was

1. Miasto bazowe + obszar dojazdu.
2. Pełna lista usług (i czego NIE robicie).
3. Czy wizytówka już istnieje i jest zweryfikowana? Które konto Google jest właścicielem?
4. Telefon, www (jeśli jest), dokładna nazwa z CEIDG.
5. Archiwalne zdjęcia realizacji (dowolnie – wrzucimy na Drive).
6. Kto akceptuje posty i odpowiedzi na opinie.
