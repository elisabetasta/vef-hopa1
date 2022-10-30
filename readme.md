## Höfundar verkefnis

* Elísa Björg Tryggvadóttir [ebt15@hi.is](mailto:ebt15@hi.is)
  * github: [`elisabjorg-13`](https://github.com/elisabjorg-13)
* Elísabet Ásta Ólafsdóttir [eao13@hi.is](mailto:eao13@hi.is)
  * github: [`elisabetasta`](https://github.com/elisabetasta)
* Friðrik Snær Björnsson [fsb3@hi.is](mailto:fsb3@hi.is)
  * github: [`fridrik-snaer`](https://github.com/fridrik-snaer)
* Ívan Már Þrastarson [imt1@hi.is](mailto:imt1@hi.is)
  * github: [`ivanmtra`](https://github.com/ivanmtra)

## Scriptur og keyrsla á verkefni

Eftirfarandi skriptur eru til staðar í verkefni: 

* `npm run install` - sækir öll þau npm tól sem notuð eru í verkefninu
* `npm run browser-sync` - keyrir browser-sync sem fylgist með breytingum á index.html og styles.css
* `npm run sass` - þýðir úr sass yfir í css innihald skráarinnar `styles.scss` og skrifar í skránna `styles.css`
* `npm run dev` - keyrir skripturnar `sass` og `browser-sync` samhliða og opnar í vafra
* `npm run lint` - keyrir stylelint á allar `.scss` skrár
  * Notar reglurnar `stylelint-config-sass-guidelines` og `stylelint-config-standard`

  ## Uppsetning verkefnis
  * components mappa þar sem einstakir íhlutir verkefnis eru (.html, .css og .scss skrár).
  * images mappa sem inniheldur myndir vefsíðanna
  * sites mappa sem inniheldur síður verkefnisins fyrir utan forsíðu
  * í rót er forsíða, package.json og package-lock.json skrár sem og style.css sem hefur allar css reglur. Einnig styles.scss sem býr til styles.css reglurnar út frá .scss skrám í components möppu