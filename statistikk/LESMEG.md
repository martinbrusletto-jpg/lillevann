# Salgsstatistikk – Lillevannsveien 13 B

Enebolig, 277 m², 4 soverom, Holmenkollen-området. Prisantydning **33 500 000 kr** (~121 000 kr/m²).

Annonsen ligger på to plattformer med **ulik startdato**, så tallene må normaliseres for tid:

- **hjem.no** – publisert ca. **18.06** (1 døgn før Finn)
- **Finn** – publisert **19.06 kl. 17:00**

## Slik bruker du `salgsstatistikk.csv`

Legg inn **én rad per plattform per dag**. Fyll inn tallene du ser i hvert dashbord. La felt stå tomt der plattformen ikke rapporterer det (f.eks. har Finn ikke «Visninger», og hjem.no ikke «Varsler sendt»).

Kolonner:

| Kolonne | Hva det er |
|---|---|
| Dato | Datoen avlesningen ble gjort |
| Plattform | Finn eller hjem.no |
| Døgn live | Antall døgn siden *den* plattformen ble publisert |
| Visninger | Impressions (kun hjem.no) |
| Klikk | Klikk på annonsen |
| Unike | Unike besøkende |
| Gjengangere 2-5 | Personer som har sett annonsen 2–5 ganger (kun Finn) |
| Sett 6+ | Personer som har sett annonsen 6+ ganger (kun Finn) |
| Favoritter | Antall som har favorittmarkert |
| Salgsoppgave bestilt | Antall som har bestilt salgsoppgaven |
| Visningsinteresse | Antall som har meldt interesse for visning |
| Varsler sendt | Push fra lagrede søk (kun Finn) |

## Nøkkeltall å regne ut og følge

Disse forholdstallene sier mer enn rådataene, fordi de korrigerer for tid og volum:

1. **Unike per døgn** = Unike ÷ Døgn live
   Måler rekkevidde rettferdig på tvers av ulik startdato.
   *Status:* Finn ~1 740/døgn, hjem.no ~180/døgn → Finn ca. 10× rekkevidden.

2. **Klikk per bruker** = Klikk ÷ Unike
   Lavt (~1) = bred, grunn nysgjerrighet. Høyt (4–5) = liten, men engasjert gruppe.
   *Status:* Finn 1,1 · hjem.no 4,6.

3. **Favorittrate** = Favoritter ÷ Unike
   3–5 % er normalt/sunt. *Status:* Finn ~3,7 %.

4. **Returandel** (Finn) = (Gjengangere 2-5 + Sett 6+) ÷ Unike
   De varme kjøperne. Forvent at denne — og spesielt «Sett 6+» — vokser dag 2–7.

5. **Salgsoppgave bestilt** ← det viktigste tidlige kjøpssignalet
   Man laster ikke ned prospektet uten å vurdere på alvor. Følg dette tett på begge plattformer.

## Hva vi ser etter de neste dagene

- Produserer **Finn** salgsoppgave-bestillinger i takt med de 7 hjem.no allerede har? Med 10× rekkevidden bør hoveddelen av budgiverne komme derfra.
- Vokser **«Sett 6+»** og returandelen på Finn? Det er kjennetegnet på reelle interessenter.
- Konverterer **favoritter → visningspåmelding**? Kommer typisk dag 2–4.
- Faller Finn-trafikken bratt etter push-bølgen (3 849 varsler)? Vurder en oppdatering/«bump» rundt visningshelgen.

> Null visningsinteresse så tidlig er **forventet** i dette prissegmentet – kjøpsreisen tar uker, ikke timer.
