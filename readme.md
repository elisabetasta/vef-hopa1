# Vefforritun 1, 2022, hópverkefni 1

[Kynning í fyrirlestri](https://youtu.be/AMb-bmaRlU0).

Verkefnið felst í því að smíða vef eftir forskrift.

Gefin er [hönnun í Figma](https://www.figma.com/file/oG7glHy9F872ywateHdVLV/Vefforritun-1%2C-2022%2C-h%C3%B3pverkefni-1). Hægt er að kveikja á grind með View > Layout grids.

Allt efni, litir, stærði o.s.fr skal taka úr Figma skjali.

Ekki þarf að útfæra neina virkni fyrir takka eða form.

Hönnunin **er ekki fullkomin** og er ósamræmi í bilum, stærðum o.þ.h. Leyfilegt er að normalísera en hægt er að spyrja spurninga um hönnun á rásinni `#vef1-2022-h1`.

Gefin er desktop og mobile hönnun. Passa þarf upp á að vefur sé skalanlegur á milli.

Allir tenglar á uppskrift skulu fara á uppskriftarsíðu, allir tenglar á yfirlit/skoða uppskriftir skal fara á yfirlitssíðu.

Vefur skal vera prófaður og virka í nýjustu útgáfum af Firefox og Chrome.

## Hópavinna

Verkefnið skal unnið í hóp með 3-4 einstaklingum. Hafið samband við kennara ef ekki er mögulegt að vinna í hóp. Hægt er að leita að félögum á slack á rásinni `#vef1-2022-h1-vantar-hop`.

Notast skal við Git og GitHub. Engar zip skrár með kóða ættu að ganga á milli í hópavinnu, heldur á að „committa“ allan kóða og vinna gegnum Git.

Sjást ætti á _commit history_ að allir meðlimir hóps hafi tekið þátt í verkefni.

Útbúa ætti a.m.k. fimm Pull Request (PR) þar sem búið er að fara yfir af öðrum meðlim í hóp.

## Lýsing á verkefni

`README.md` skrá skal vera í rót verkefnis og innihalda:

* Upplýsingar um hvernig keyra skuli verkefnið
  * `npm run dev` eða `npm start`
  * `npm run lint` skal vera til staðar og keyra stylelint á Sass
* Létt lýsing á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS/Sass er skipulagt og fleira sem á við
* Upplýsingar um alla sem unnu verkefni, nöfn, HÍ notendanöfn og GitHub notendanöfn

## Tæki og tól

Verkefnið skal innihalda `package.json` og `package-lock.json` sem innihalda öll notuð tól.

Þegar verkefnið er sótt verður `npm install` keyrt á undan öllum öðrum skipunum.

Setja skal upp Sass og stylelint með `stylelint-config-sass-guidelines` og `stylelint-config-standard` fyrir verkefnið.

Til að passa upp á samræmi eru skrárnar `.gitignore`, `.gitattributes` og `.editorconfig` gefnar.

## Mat

* 10% - Git og GitHub PR eftir forskrift
* 10% - `README` eftir forskrift, tæki og tól uppsett
* 10% – Snyrtilegt, gilt (skv. stylelint) CSS/Sass, gilt og aðgengilegt HTML
* 15% – Almennt útlit
* 15% – Forsíða
* 15% – Yfirlitssíða
* 15% – Uppskriftasíða, bæði með mynd og vídeó í haus
* 10% – Almennur skalanleiki

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 26. október 2022.

## Skil

Einn aðili úr hóp skal skila fyrir hönd allra og skila skal í Canvas í seinasta lagi 30. október.

Skil skulu innihalda:

* nöfn allra í hóp ásamt notendanafni
* slóð á verkefni keyrandi á Netlify
* slóð á **private** GitHub repo fyrir verkefni. Dæmatímakennurum skal hafa verið boðið í repo. Notendanöfn þeirra eru:
  * `MarzukIngi`
  * `Stimmikex`
  * `brynjar13`
  * `ofurtumi`
  * `BjarniHaskoli`
  * `Stulli888`

## Einkunn

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

## Hönnun

Upprunaleg hönnun eftir [Meghan Regior](https://twitter.com/meghanregior) fyrir verkefni í vefforritun 2016. Flutt í Figma og uppfært af Óla.

> Útgáfa 0.2 (bæta við um git og PR)
