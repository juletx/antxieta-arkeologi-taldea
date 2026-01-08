---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-29
type: landing

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: biografia
    content:
      username: antxieta-arkeologi-taldea
      greeting: ""
      show_status: true
      show_scroll_indicator: false
      typewriter:
        enable: true
        prefix: "Ikerketa arkeologikoak egiten ditugu:"
        strings:
          - "Kobazuloetan"
          - "Aire librean"
          - "Miaketak"
          - "Zundaketak"
          - "Indusketak"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: Bloga
          url: "#bloga"
          icon: arrow-down
        - text: Proiektuak
          url: "#proiektuak"
          icon: briefcase
        - text: Historia
          url: "#historia"
          icon: book-open
        - text: Taldea
          url: "#people"
          icon: user-group
    design:
      style: centered
      avatar_shape: circle
      animations: true
      spacing:
        padding: ["6rem", "0", "4rem", "0"]
  - block: collection
    id: bloga
    content:
      title: '[Bloga](blog)'
      subtitle:
      # Filter on criteria
      filters:
        folders:
          - blog
        tag: ''
        category: ''
        publication_type: ''
        author: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a view for the listings:
      #   1 = List
      #   2 = Compact
      #   3 = Card
      #   4 = Citation (publication only)
      view: card
      columns: '2'
  - block: portfolio
    id: proiektuak
    content:
      title: '[Proiektuak](projects)'
      subtitle: ''
      count: 100
      filters:
        folders:
          - projects

      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0

      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
      - name: Denak
        tag: '*'
      - name: Izarraitz
        tag: Izarraitz
      - name: Zundaketak
        tag: Zundaketak
      - name: Indusketak
        tag: Indusketak
      - name: Miaketak
        tag: Miaketak
      - name: Dibulgazioa
        tag: Dibulgazioa

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

      # Toggle between the various page layout types.
      #   1 = List
      #   2 = Compact
      #   3 = Card
      #   5 = Showcase
      view: masonry

      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: knowledge-tags
    id: etiketak
    content:
      title: "Etiketak"
      subtitle: ''
      # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 20
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0
      columns: '2'
  - block: resume-experience
    id: historia
    content:
      date_format: '2006'
      username: antxieta-arkeologi-taldea
    design:
      columns: '1'
  - block: team-showcase
    id: taldea
    content:
      title: 'Taldea'
      subtitle:
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: contact-info
    id: kontaktua
    content:
      title: Kontaktua
      subtitle: |2-
        Antxieta Arkeologi Taldeko ateak parez
        pare irekiak daude elkartea ezagutu nahi
        duzuen pertsona guztientzat. Nor garen eta
        arrasto fosilak eta aurrehistoriako aztarnen
        aurkikuntzan zertarako eta zergatik ibiltzen
        garen interesa duzuenontzat.

        Gu ezagutzera etortzen bazarete, zuen kabuz
        ikusi ahal izango duzue arkaeologiaz gain,
        gure lana, familia eta lagunak ditugula eta
        hau egitera bultzatzen gaituena ilusioa eta
        denbora libreaz disfrutatzeko beharrak direla,
        beti ere taldean, gustukoen duguna eginez,
        hau da, aire librean zulatu, edo kobetan
        aztarnak, lanabesak, hezurrak edo gure
        aurrekoen arrastoak bilatzera sartuz.

        Horrez gain, Antxieta Arkeologi Taldeko kide
        izateko arkeologoa izatea beharrezkoa ez dela
        konturatuko zarete, ezta horrelako gaitasunik
        frogatzen duen antzeko titulurik edukitzea
        ere. Altua edo baxua, gizena edo argala, gaztea
        edo heldua… denok zarete ongi etorriak.

        Ez dago badintzarik Antxieta Arkeologi
        Taldeko kide izateko. Gure jardueran jakinmina
        edukitzea da soilik beharrezkoa, eta igande
        goiz batean egin ohi ditugun irteeretako batera
        etortzea. Horrekin nahikoa da, zaletasuna
        jakinminaren hurrengo pausoa baita.

        Gure deia Azpeitiko gaztediari dago batez ere
        zuzendua, zuen denbora librea zerbaitekin
        betetzeko beharra sentizen duzuen neskamutilei,
        beste gazte batzuekin beste modu
        batera erlazionatzeko eta astean zehar
        motibaturik sentitzeko beharra duzuenoi.

        Antxieta Arkeologi Taldeak beste garai bateko
        aztarnak aurkitu eta gure inguruko hainbat
        txoko ezagutzeko aukera emango dizue
        modu dibertigarri eta entretenigarri batean.
        Aurkikuntza berri bakoitza energiaz beteriko
        bultzada pozgarri bat baita.

        Gure irteerak, lehen aipatu bezala, igande
        goizetan egiten ditugu. Zortzirak aldera
        ateratzen gara eta bazkalordurako bueltatzen.
        Beti ere zerbait hartu eta barre batzuk egin
        ondoren.

        Oso erraza da. Jar zaitez gurekin kontaktuan
        ikasteko eta aldi berean ondo pasatzeko gogoa,
        ilusioa eta gure taldekide izan nahi baduzu,
        anima zaitez zerbait berria eta gizartearentzat
        interesgarria dena egitera, gizartea bera baita
        egingo dituzun aurkikuntzen onuragarri.
      visit_title: "Bisitatu gaitzazu"
      address:
        lines:
          - 'Antxieta Arkeologia Taldea bulegoa'
          - 'Soreasu 1. Kulturgunea'
          - 'Azpeitia, Gipuzkoa 20730'
      office_hours:
        - 'Irteerak igandero 8:00 bulegoan'
      email: antxieta.arkeologi.taldea@outlook.com
      phone: 608 08 70 24
      map_url: 'https://maps.app.goo.gl/z2tStbvY3j6ToM1a7'
      map_embed: '<iframe title="Google Maps" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d846.3442503776424!2d-2.264491888955202!3d43.18668274407603!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd51cd9f19a4bdbf%3A0x8873426fd1ec43c!2sAntxieta%20Arkeologi%20Taldea!5e0!3m2!1seu!2ses!4v1625736311593!5m2!1seu!2ses" width="100%" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0" loading="lazy"></iframe>'
      connect_title: "Jarri kontaktuan"
      social:
        - icon: 'brands/x'
          url: 'https://twitter.com/Antxieta_Taldea'
        - icon: 'brands/instagram'
          url: 'https://www.instagram.com/antxieta_arkeologi_taldea'
        - icon: 'brands/youtube'
          url: 'https://www.youtube.com/@antxietaarkeologitaldea7158'
          name: YouTube
          link: 'https://www.youtube.com/channel/UCWUlFhZBxXqodnvo7FVSkuw'
        - icon: newspaper
          name: Uztarria
          link: 'https://uztarria.eus/komunitatea/antxietaarkeologia'
        - icon: newspaper
          name: Danbolin
          link: 'https://danbolin.eus/category/antxieta-arkeologia-taldea'
      show_form: true
      form_action: '/.netlify/functions/form'
    design:
      columns: '1'

---
