---
layout: blocks
title: ...und Kekse haben wir auch!
date: 2020-01-12T22:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "assets/logo-pfaditag.png"
  navigation:
  - link: "#"
    link_text: Home
  - link: "#detail"
    link_text: "Details"
  - link: "#map"
    link_text: "Vor Ort"
  - link: "#contact"
    link_text: "Kontakt"

  cta:
    button_text: "Stammesaktion Anmelden"
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
    image: "assets/Keks.png"
    alt_text: Product Shot
  background_image: "assets/hero-2-bg.png"

- template: detail-content
  block: text-1
  id: detail
  headline: Pfadi was? 
  content: <p>uBuild is an open-source Jekyll based theme that doubles as a builder
    tool inside the Forestry content manager. It's easy to get started!</p><ol><li><p>Fork
    the <a href="https://github.com/forestryio/ubuild-jekyll">repo</a> and import
    the site into <a href="https://forestry.io/">Forestry</a> (or use <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks#even-quicker-start">our
    magic button</a>).</p></li><li><p>Click on 'Add New' in Forestry and select the
    Page-Builder template.</p></li><li><p>Add and customize the available Blocks and
    preview them as you go along.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">our
    article</a> and create your own Blocks.</p></li></ol>

- template: content-feature
  block: iframe-1
  id: map
  media_alignment: Right
  headline: <strong>Aktionen zum Mitmachen</strong><span
    class="light"> am Pfadi Tag 2020</span>
  content: Übersicht der Aktionen am Pfadi Tag in deiner Nähe!
  iframe: |
      <iframe width="100%" height="600px" frameborder="0" allowfullscreen src="https://umap.openstreetmap.fr/de/map/pfaditag-2020_406434?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&allowEdit=false&moreControl=false&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=false&onLoadPanel=undefined&captionBar=false"></iframe>

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
      <img src="assets/social/018-youtube.svg" height="30pt" alt="YouTube" /></a> 
    <a href="https://www.facebook.com/VCPHessen/" target="_blank">
      <img src="assets/social/013-facebook.svg" height="30pt" alt="Facebook" /></a> 
    <a href="https://www.instagram.com/vcp.hessen/" target="_blank">
      <img src="assets/social/014-instagram.svg" height="30pt" alt="Instagram" /></a> 
    <a href="https://hessen.vcp.de" target="_blank">
      <img src="assets/social/012-network.svg" height="30pt" alt="Website" /></a>  
    <a href="mailto:hessen@vcp.de?subject=Pfadi%20Tag" target="_blank">
      <img src="assets/social/043-email.svg" height="30pt" alt="E-Mail" /></a> 
  col_4: <a href="https://hessen.vcp.de" target="_blank"><img src="assets/logo-vcp.png" width="100%" /></a>
  col_3: |
    <div class="block-header-2">
      <li class="nav-item">
        <a href="https://hessen.vcp.de/impressum" target="_blank">Impressum & Datenschutz</a>
      </li>
    </div>

---
