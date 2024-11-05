Github actions
- Github actionsin avulla voidaan automatisoida jekyl sivustoa tekemällä sinne työjonoja jotka aktivoitaessa suorittaa tiettyjä työtehtäviä. Esimerkkinä tästä. Automatisoitu koodin testaaminen, push:ataan työjonoa kun koodi on päivitetty ja se sitten tarkistaa koodin ja varmistaa ettei muutokset riko koodin toimintaa. Toinen esimerkki tästä on ajastetut muutokset, voin esimerkiksi asettaa että työjono varmuuuskopio koodin kerran viikossa sunnuntaina klo 20:00.
  
CI/CD putkisto (Continuous Integration / Continuous Deployment)
- Yhdistämällä jekyl sivustoon Github actions marketplacesta erilaisia työkaluja kuten AWS CodeBuild run build  ja docker. Yhdistelemällä näitä saadaan kokonaisuus joka eliminoi manuaalista työta ja antaa kehittäjälle enemmän aikaa keskittyä luovaan työhön ja jatkokehittämiseen eikä niin ongelmien ratkomiseen.
