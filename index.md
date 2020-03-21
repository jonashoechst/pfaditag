---
layout: blocks
title: ...und Kekse haben wir auch!
date: 2020-01-12T22:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "assets/logo-pfaditag.png"
  navigation:
  # - link: "#"
  #   link_text: Home
  - link: "#detail"
    link_text: "Details"
  - link: "#map"
    link_text: "Vor Ort"
  - link: "#posters"
    link_text: "Materialien"
  # - link: "#contact"
  #   link_text: "Kontakt"

  cta:
    button_text: "Stamm Anmelden"
    url: |
      mailto:hessen@vcp.de?subject=Pfadi%20Tag%202020&body=Hallo,%0A
      %0A
      ich möchte eine Aktion meines Stammes zum Pfadi Tag 2020 anmelden. Dazu sind hier die wesentlichen Informationen für unsere Aktion.%0A
      %0A
      Stamm: %0A
      Ansprechpartner*innen: %0A
      Telefon: %0A
      Email: %0A
      Adresse: %0A
      Ziel unserer Aktion (bitte ankreuzen):%0A
          [ ] Kinder für unsere Gruppen%0A
          [ ] neue Mitarbeitende%0A
          [ ] Spenden für unseren Stamm%0A
          [ ] Anerkennung im Ort%0A
          [ ] Sonstiges: %0A
      %0A
      Dauer unserer Aktion:%0A
          [ ] Freitag abend%0A
          [ ] Samstag früh%0A
          [ ] Samstag mittag%0A
          [ ] Samstag abend%0A
          [ ] Sonntag früh%0A
          [ ] Sonntag mittag%0A
      %0A
      Wir können gebrauchen:%0A
          [ ] Zeltmaterial%0A
          [ ] Geräte zum Kochen%0A
          [ ] Gast von der LaFü%0A
          [ ] Geräte für Aktionen (Siebdruck, Buttonmaschine, Bälle, ...)%0A
          [ ] Hessen-Keks-Backmischung für __ Kekse%0A
          [ ] Sonstiges: %0A
      %0A
      Gut Pfad, %0A
          %0A

- template: hero-banner-w-image
  block: hero-2
  id: opener
  headline: Pfadi Tag <br><strong>... und Kekse haben wir auch!</strong>
  content: "28. - 30. August 2020"
  cta:
    enabled: false
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: 'See on GitHub '
  image:
    image: "assets/keks.png"
    alt_text: Product Shot
  background_image: "assets/hero-2-bg.png"

- template: detail-content
  block: text-1
  id: detail
  headline: Pfadi was? 
  content: |
    <p>Vielleicht hast Du ja schon was davon gehört, vielleicht hiermit zum ersten Mal. Ganz egal, hier die wichtigsten Infos zum Pfaditag.</p>
    <p><b>Was ist?</b> Der Pfaditag ist eine neue Aktion im VCP Hessen, die wir gerne mal ausprobieren möchten.</p> 
    <p><b>Was genau?</b> Am Pfaditag macht Ihr Werbung für Euren Stamm und das, was Ihr genau erreichen wollt: eine neue Gruppe, neue Mitarbeitende, Geld, Liebe und Anerkennung – was auch immer.</p> 
    <p><b>Wer macht?</b> Euer Stamm macht die Aktion vor Ort, so wie Ihr es braucht. Das Land unterstützt Euch mit einer Werbekampagne, Material und wenn Ihr wollt auch Besuch von der Landesführungsrunde.</p> 
    <p><b>Wir sollen das ganze Wochenende...</b> könnt Ihr, muss aber nicht sein. Ob Eure Aktion jetzt 2 oder 72 Stunden geht bleibt ganz Euch überlassen. Schaut, was Ihr bewältigen könnt.</p> 
    <p><b>Und was macht das Land?</b> Wir haben Plakate für Euch gestaltet, die Ihr nutzen könnt. Da ist Platz für Eure eigenen Infos. Wir haben Werbeschnickschnack und wir haben eine Backmischung für Kekse, die Ihr bestellen könnt. Dazu gibt es eine Homepage, auf der Ihr Ideen für die Durchführung bekommt. Wenn Ihr Lust habt, könnt Ihr auch jemand von der Lafü einladen, zum Helfen, hübsch sein, Reden halten, was auch immer. Je nachdem wie viele Stämme mitmachen, werben wir auch mehr und überregionaler?</p> 
    <p><b>Aber wieso denn?</b> Jeder Stamm macht immer wieder Werbung für sich und organisiert dafür kleine Veranstaltungen. Genau das wollen wir unterstützen und ein bisschen bekannter machen, so dass vielleicht auch Leute vom Nachbarort kommen oder Menschen, die keinen Gemeindebrief lesen.</p> 
    <p><b>Und jetzt?</b> Bitte gebt uns bis zur Landesversammlung am 13. März 2020 Rückmeldung, ob Euer Stamm da mitmachen möchte. Der allerletzte Anmeldeschluss ist der 24. April 2020. </p> 

- template: content-feature
  block: leaflet-1
  id: events
  media_alignment: Right
  headline: <strong>Aktionen zum Mitmachen</strong><span
    class="light"> am Pfadi Tag 2020</span>
  content: Übersicht der Aktionen am Pfadi Tag in deiner Nähe!
  tilesUrl: https://api.mapbox.com/styles/v1/mapbox/light-v10/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoiaG9lY2hzdCIsImEiOiJjazVueDhyMWkwenpuM2RydzltNjhraDAzIn0.HntghYG9IBZvVd0bUJEY9Q
  attribution: Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>
  markers:
    - text: <b>Landesbüro VCP Hessen, Bad Nauheim</b><br> <a href='https://hessen.vcp.de/'>https://hessen.vcp.de/</a>
      lat: 50.36552
      lon: 8.73049
    # Kurhessen
    - text: <b>Stamm Graf Folke Bernadotte, Fulda</b><br> <a href='http://vcp-fd.de'>http://vcp-fd.de</a>
      lat: 50.5554376
      lon: 9.6807718
    - text: <b>Stamm Kirchhain</b><br> <a href='https://vcp-kirchhain.de'>https://vcp-kirchhain.de</a>
      lat: 50.8204667
      lon: 8.9193417
    - text: <b>Stamm Martin Luther, Lumdatal</b><br> <a href='https://vcp-lumdatal.de'>https://vcp-lumdatal.de</a>
      lat: 50.6743844
      lon: 8.8621879
    - text: <b>Stamm Gottfried von Ebersberg, Hettenhausen</b><br> <a href='https://www.vcp-hettenhausen.de'>https://www.vcp-hettenhausen.de</a>
      lat: 50.4518321
      lon: 9.8146037
    # - text: <b>Stamm Mückenstürmer, Bad Hersfeld</b><br> <a href='https://vcp-hef.de'>https://vcp-hef.de</a>
    #   lat: 50.8450519
    #   lon: 9.7016599
    # Wetterau
    - text: <b>Stamm Friedberg</b>
      lat:  50.3323554
      lon: 8.7519085
    - text: <b>Stamm Kojoten, Nieder Mörlen</b>
      lat:  50.3620209
      lon: 8.7539428
    # Rhein-Main
    - text: <b>Stamm Schinderhannes, Taunusstein</b><br> <a href='http://www.vcp-taunusstein.de/'>http://www.vcp-taunusstein.de/</a>
      lat: 50.1371867
      lon: 8.1385843
    - text: <b>Stamm Ottheinrich von der Pfalz, Ingelheim</b><br> <a href='https://www.vcp-ingelheim.de/'>https://www.vcp-ingelheim.de/</a>
      lat: 49.9649018
      lon: 8.0619247
    - text: <b>Stamm Franken, Wiesbaden Erbenheim</b><br> Unsere Aktion findet bereits am 21.08.2020 statt.
      lat: 50.0583014
      lon: 8.3030815
    - text: <b>Stamm Ansgar, Dauborn</b><br> <a href='http://vcp-dauborn.de/'>http://vcp-dauborn.de/</a>
      lat: 50.3277451
      lon: 8.1744336
    # Main-Kinzig
    - text: <b>Stamm Eschersheim, Frankfurt</b><br> <a href='https://www.efrg.de/gemeindeleben/kinder-und-jugendliche/integrative-pfadfindergruppen/'>https://www.efrg.de/gemeindeleben/kinder-und-jugendliche/integrative-pfadfindergruppen//</a>
      lat: 50.1452377
      lon: 8.6674053
    # Starkenburg

- template: detail-content
  block: media-4
  id: posters
  caption: Poster von <a href="https://www.tobidahmen.de">Tobi Dahmen</a> &copy; VCP Hessen
  images:
    - image: assets/pfaditag-poster1.jpg
      caption: "Poster 1: Essen"
      link: assets/pfaditag-poster1.jpg
    - image: assets/pfaditag-poster2.jpg
      caption: "Poster 2: Gute Nacht"
      link: assets/pfaditag-poster2.jpg
    - image: assets/pfaditag-poster3.jpg
      caption: "Poster 3: Gruppenleiter"
      link: assets/pfaditag-poster3.jpg
    - image: assets/pfaditag-poster4.jpg
      caption: "Poster 4: Singerunde"
      link: assets/pfaditag-poster4.jpg

- block: mailto
  id: signup
  content: Melde deinen Stamm zum Pfadi Tag 2020 an...
  teaser: "Hallo, ich möchte eine Aktion..."
  cta_text: "Anmelden"
  url: |
      mailto:hessen@vcp.de?subject=Pfadi%20Tag%202020&body=Hallo,%0A
      %0A
      ich möchte eine Aktion meines Stammes zum Pfadi Tag 2020 anmelden. Dazu sind hier die wesentlichen Informationen für unsere Aktion.%0A
      %0A
      Stamm: %0A
      Ansprechpartner*innen: %0A
      Telefon: %0A
      Email: %0A
      Adresse: %0A
      Ziel unserer Aktion (bitte ankreuzen):%0A
          [ ] Kinder für unsere Gruppen%0A
          [ ] neue Mitarbeitende%0A
          [ ] Spenden für unseren Stamm%0A
          [ ] Anerkennung im Ort%0A
          [ ] Sonstiges: %0A
      %0A
      Dauer unserer Aktion:%0A
          [ ] Freitag abend%0A
          [ ] Samstag früh%0A
          [ ] Samstag mittag%0A
          [ ] Samstag abend%0A
          [ ] Sonntag früh%0A
          [ ] Sonntag mittag%0A
      %0A
      Wir können gebrauchen:%0A
          [ ] Zeltmaterial%0A
          [ ] Geräte zum Kochen%0A
          [ ] Gast von der LaFü%0A
          [ ] Geräte für Aktionen (Siebdruck, Buttonmaschine, Bälle, ...)%0A
          [ ] Hessen-Keks-Backmischung für __ Kekse%0A
          [ ] Sonstiges: %0A
      %0A
      Gut Pfad, %0A
          %0A

- template: footer
  block: footer-2
  id: contact
  image: "assets/logo-pfaditag.png"
  col_2: | 
    <a href="https://www.youtube.com/channel/UCcffpRuB1hnpn7uiJ6GnDGA" target="_blank">
      <img src="assets/social/018-youtube.svg" height="20pt" alt="YouTube" /></a> 
    <a href="https://www.facebook.com/VCPHessen/" target="_blank">
      <img src="assets/social/013-facebook.svg" height="20pt" alt="Facebook" /></a> 
    <a href="https://www.instagram.com/vcp.hessen/" target="_blank">
      <img src="assets/social/014-instagram.svg" height="20pt" alt="Instagram" /></a> 
    <a href="https://hessen.vcp.de" target="_blank">
      <img src="assets/social/012-network.svg" height="20pt" alt="Website" /></a>  
    <a href="mailto:hessen@vcp.de?subject=Pfadi%20Tag" target="_blank">
      <img src="assets/social/043-email.svg" height="20pt" alt="E-Mail" /></a> 
  col_4: <a href="https://hessen.vcp.de" target="_blank"><img src="assets/logo-vcp.png" width="100%" /></a>
  col_3: |
    <a href="https://hessen.vcp.de/impressum" target="_blank" style="text-decoration: none;">Impressum & Datenschutz</a> 

---
