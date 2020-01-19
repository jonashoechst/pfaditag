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
      mailto:hessen@vcp.de?subject=Pfadi%20Tag%202020&body=Hallo Liebes Landesbüro,%0A
      %0A
      ich möchte eine Aktion meines Stammes zum Pfadi Tag 2020 anmelden. Dazu sind hier die wesentlichen Informationen für unsere Aktion.%0A
      %0A
      Name: %0A
      Stamm: %0A
      Aktion: %0A
      Datum und Dauer: %0A
      Beschreibung für die Website: %0A
      %0A
      Gut Pfad, %0A

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
  block: iframe-1
  id: map
  media_alignment: Right
  headline: <strong>Aktionen zum Mitmachen</strong><span
    class="light"> am Pfadi Tag 2020</span>
  content: Übersicht der Aktionen am Pfadi Tag in deiner Nähe!
  iframe: |
      <iframe width="100%" height="600px" frameborder="0" allowfullscreen src="https://umap.openstreetmap.fr/de/map/pfaditag-2020_406434?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&allowEdit=false&moreControl=false&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=false&onLoadPanel=undefined&captionBar=false"></iframe>

- template: detail-content
  block: media-4
  id: posters
  images:
    - image: assets/pfaditag-poster1.jpg
      caption: "Poster 1: Essen"
      link: downloads/pfaditag-poster1.jpg
    - image: assets/pfaditag-poster2.jpg
      caption: "Poster 2: Gute Nacht"
      link: downloads/pfaditag-poster2.jpg
    - image: assets/pfaditag-poster3.jpg
      caption: "Poster 3: Gruppenleiter"
      link: downloads/pfaditag-poster3.jpg
    - image: assets/pfaditag-poster4.jpg
      caption: "Poster 4: Singerunde"
      link: downloads/pfaditag-poster4.jpg

- block: mailto
  id: signup
  content: Melde deinen Stamm zum Pfadi Tag 2020 an...
  teaser: "Hallo Liebes Landesbüro, ..."
  cta_text: "Anmelden"
  url: |
      mailto:hessen@vcp.de?subject=Pfadi%20Tag%202020&body=Hallo Liebes Landesbüro,%0A
      %0A
      ich möchte eine Aktion meines Stammes zum Pfadi Tag 2020 anmelden. Dazu sind hier die wesentlichen Informationen für unsere Aktion.%0A
      %0A
      Name: %0A
      Stamm: %0A
      Aktion: %0A
      Datum und Dauer: %0A
      Beschreibung für die Website: %0A
      %0A
      Gut Pfad, %0A

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
