---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-29
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: <i class='fas fa-book'></i>&nbsp;Aurkezpena
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: antxieta-arkeologi-taldea
  - block: collection
    id: posts
    content:
      title: '[<i class=''fas fa-edit''></i>&nbsp;Bloga](post)'
      subtitle:
      # Filter on criteria
      filters:
        folders:
          - post
        tag: ''
        category: ''
        publication_type: ''
        author: ''
        publication_type: ""
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
    id: projects
    content:
      title: '[<i class=''fas fa-code''></i>&nbsp;Proiektuak](project)'
      subtitle: ''
      filters:
        folders:
          - project

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
  - block: tag_cloud
    id: tags
    content:
      title: "[<i class='fas fa-tags'></i>&nbsp;Etiketak](tags)"
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
  - block: experience
    id: history
    content:
      title: '<i class=''fas fa-landmark''></i>&nbsp;Historia'
      subtitle: ''
      text: |2- 
        <div class="d-flex justify-content-center">
        <a href="uploads/ANTXIETA-50%20urte%20Liburua-Konprimiuta.pdf" target="_blank">
        {{< figure src="historia/featured.jpg" caption="[ANTXIETA arkeologi taldea: 50 urte lanean gozatuz](uploads/ANTXIETA-50%20urte%20Liburua-Konprimiuta.pdf) liburua." lightbox="false" >}}
        </a>
        </div>
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: '2006'
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
      - title: Dena egiteko dagoenean EKAIN aurkitzen dute
        company: Antxieta Arkeologi Taldea
        company_url: ''
        company_logo: ''
        location: ''
        date_start: '1965-01-01'
        date_end: '1975-01-01'
        description: |2-
          ![Dena egiteko dagoenean EKAIN aurkitzen dute](uploads/history/1.jpg)
          ![Dena egiteko dagoenean EKAIN aurkitzen dute](uploads/history/2.jpg)
          ![Dena egiteko dagoenean EKAIN aurkitzen dute](uploads/history/3.jpg)

          Antxieta Arkeologi Taldearen istorioa Andoni
          Albizuri eta Rafael Rezabalekin hasten da 1965. urtean

          Gogo biziak, orokorrean euskal kulturan
          duen ezaguerak eta zehazki gizakiak gure
          haranean eduki duen eboluzioak bultzatzen
          du Andoni Albizuri gure arbasoen arrasto
          eta aztarnak bilatzera, horretarako, Rafael
          Rezabal sartzen du taldean lehenengo eta
          ondoren, beste lagun batzuk aldizka.

          Larunbata edo igandean mendira ateratzen
          dira aztarnak aurkitu nahiean. Astean
          zehar, lana egiteaz gain, beraien denbora
          librea astebukaeran zehar aurkitu dituzten
          aztarnak sailkatzen eta garbitzen pasatzen
          dute, planoetan aztarnen aurkikuntzak non
          izan diren kokatuz eta Aranzadi Zientzia
          Elkartera entregatuko duten estudiorako
          dokumentazioa prestatuz.

          Ez dute laguntza ekonomikorik jasotzen,
          gastu guztiak beraien poltsikotik ordaintzen
          dituzte. Beraien lana azterlariak izatea da,
          amateur moduan. Beraien laginetan 30 x 40
          cm gehienera aztertzera iristen dira. Zerbait
          aurkitu orduko, gelditu eta Aranzadi Elkarteari
          jakinarazten diote.

          Jose Miguel Barandiaranek, modu berezian,
          beraien lana goraipatu eta adore ematen die.
          Egun batean, Andoni eta Rafaelek zientzialari
          komunitatea eta Eukal Herria zur eta lur uzten
          dituzte berebiziko aurkikuntza batekin. 1969.
          urteko uztailaren 1ean Ekain aurkitzen dute.

      - title: Gazte gogotsuen sarrera, aurkikuntza kopurua handitzen da
        company: Antxieta Arkeologi Taldea
        company_url: ''
        company_logo: ''
        location: ''
        date_start: '1976-01-01'
        date_end: '1985-01-01'
        description: |2-
          ![Gazte gogotsuen sarrera, aurkikuntza kopurua handitzen da](uploads/history/4.jpg)
          ![Gazte gogotsuen sarrera, aurkikuntza kopurua handitzen da](uploads/history/5.jpg)
          ![Gazte gogotsuen sarrera, aurkikuntza kopurua handitzen da](uploads/history/6.jpg)
          
          Andoni eta Rafaelek beraien aurkikuntzekin
          jarraitzen dute, ez antzinako aztarnenak
          bakarrik, baizik eta gazte gogotsuenak, hamar
          urte lehenago hasi zuten lanarekin jarraituko
          dutenak.

          1975 urtean lehen gazte taldea gehitzea
          lortu zuten. 1978an aurpegi berriekin taldea
          handitzen da. 1982an hirugarren gazte talde
          bat iristen da.

          Andoni eta Rafael gazteekin lanean aritzen
          dira, lehenengo Errailan eta ondoren
          Altzolaraz haranean. Koben lilura energiaz eta
          ilusioz beteriko gazte horiei transmititzeaz
          arduratzen dira. Batzuk geratu egingo
          dira, beste batzuk joan eta bakan batzuek
          noizbehinka kolaboratuko dute.

          Laginen neurriak handitu egiten dira, 30x40 cm
          izatetik 100x100 cm izatera. Jesus Altuna eta
          Koro Mariezkurrenak aurkikuntzak kudeatzen
          dituzte eta baita lan taldea ere.

          1980tik 1985era, gazte hauek Jesus Altunak
          industutako Amaldako Koban lagundu eta
          ikasten dute.

          Aldi berean, beraien lana eta dedikazioak dagokion
          errekonozimendua jasotzen hasten da:
          1982ko maiatzaren 15ean, Aranzadi Zientzia
          Elkarteak Antxieta taldeari Gipuzkoako beste
          kobetan historiaurreko laginak aurkitzea baimentzen
          dio; 1983ko urtarrilaren 10ean, Azpeitiko
          Udalak Antxieta Arkeologi Taldeari Guardia
          Zibilen Kuartela izandako etxean lokal bat
          uztea erabakitzen du aho batez; 1984ko maiatzaren
          8an, Gipuzkoako Foru Aldundiak 70.000
          pezetako diru laguntza ematen dio taldeari.

          Hamarkada honetako gauzarik aipagarriena
          taldea bermatu egiten dela da, espiritu berritua
          duen oinarriarekin finkatu eta aukikuntzak
          nabarmenak dira…

          1983an Andoni Albizuri hiltzen da, taldearen
          arima eta motorra.

      - title: Taldearen eta proiektuaren bermatzea
        company: Antxieta Arkeologi Taldea
        company_url: ''
        company_logo: ''
        location: ''
        date_start: '1986-01-01'
        date_end: '1995-01-01'
        description: |2-
          ![Taldearen eta proiektuaren bermatzea](uploads/history/7.jpg)
          ![Taldearen eta proiektuaren bermatzea](uploads/history/8.jpg)
          ![Taldearen eta proiektuaren bermatzea](uploads/history/9.jpg)
          
          Antxieta Arkeologi Taldeak 20 urteko historia
          du jada eta bere hirugarren hamarkada
          sendotasunez hasten du, ezagutza handiago
          batekin eta bide onetik doazen uste
          osoarekin.

          Oso gazte hasi zirenek esperientzia hartu
          dute, beraien ilusioa mantenduz eta talde
          tinko bat osatuz.

          Hasierako dinamikarekin jarraitzen dute,
          Andoni eta Rafaelengandik jasotakoa hain
          zuzen ere: astean zehar lana egin igande
          goizetan mendira atera eta aztarna eta arrasto
          berriak aurkitzeko. Astearte gauetan, bilera.
          Asteburuko aztarnak garbitu eta dokumentatu,
          plano berriak egin, dokumentazioa garbira
          pasa eta aurkituriko materialak Aranzadira
          eramateko prestatu.

          1983tik bileretarako azpiegitura daukate:
          Guardia Zibilen kuartela zen etxean Azpeitiako
          Udalak lagaturiko lokal bat.

          Denborarekin, beraien lanen errekonozimendua
          handitzen doa:

          Antxieta Arkeologi Taldeak eginiko aurkikuntzak
          Gizpukoako Arkeologia Kartan agertzen
          dira, Aranzadi Zientzia Elkarteak eginiko eta
          publikaturiko lanean.

          Eusko Jaurlaritzako Ondare Historiko-Artistikoko
          Zuzendaritzak Antxieta taldeari Lastur-Debako
          kobetan laginak egitera baimentzen du.

          Jesus Altuna eta Koro Mariezkurrenak, Aranzadi
          Elkarteko kideek taldearen aurkikuntzak
          kudeatzen jarraitzen dute.

      - title: Irikaitzek aztarnen aurkikuntzen eboluzioa irudikatzen du
        company: Antxieta Arkeologi Taldea
        company_url: ''
        company_logo: ''
        location: ''
        date_start: '1996-01-01'
        date_end: '2005-01-01'
        description: |2-
          ![Irikaitzek aztarnen aurkikuntzen eboluzioa irudikatzen du](uploads/history/10.jpg)
          ![Irikaitzek aztarnen aurkikuntzen eboluzioa irudikatzen du](uploads/history/11.jpg)
          ![Irikaitzek aztarnen aurkikuntzen eboluzioa irudikatzen du](uploads/history/12.jpg)

          Jasotako esperientziak fruitu berriak ematen
          ditu. Taldearen aurkikuntzak aire librean
          zundaketak egitera zuzentzen ditu, kobetan
          aurkituriko aztarna fosilak baino zaharragoak
          diren arrastoak aurkituz, Irikaitzen, Zestoan
          aurkiturikoak frogatzen duen bezala, gizakiak
          aire librean bizi litezkeela.

          Egia esateko, Irakaitzek aurrera pauso bat
          irudikatzen du aurkikuntzak kobetan bakarrik
          egin daitezkeela finkatzen duen ideia
          baztertzen baitu.

          Finantzaketari dagokionez ere eboluzio bat
          dago. Azpeitiako Udalak eta Gipuzkoako Foru
          Aldundiak Antxieta Arkeologi Taldeko gastuak
          babesten dituzte. Bi erakundeek, gainera,
          gogo onez parte-hartzen dute taldearekin.
          Antxietak eginiko lanak esker ona jasotzen ari
          dela nabarmena da.

          Zorroztasun, zehaztasun eta kalitate handiagoarekin
          lana egiten da. Kantitatea
          bigarren maila batera pasatzen da. Taldea bere
          heldutasunean dago, badakite zer nahi duten
          eta bateratua eta trinkoa mantentzen da.
          Jesus Altuna eta Koro Mariezkurrenak taldea
          zientifikoki kudeatzen jarraitzen dute.

      - title: Aztarnategien ugaritasuna, begiratzen jakin behar da
        company: Antxieta Arkeologi Taldea
        company_url: ''
        company_logo: ''
        location: ''
        date_start: '2006-01-01'
        date_end: '2015-01-01'
        description: |2-
          ![Aztarnategien ugaritasuna, begiratzen jakin behar da](uploads/history/13.jpg)
          ![Aztarnategien ugaritasuna, begiratzen jakin behar da](uploads/history/14.jpg)
          ![Aztarnategien ugaritasuna, begiratzen jakin behar da](uploads/history/15.jpg)

          Denborak arrazoia eman eta kendu egiten du.
          Kasu honetan, taldekideen alde dago, gure
          geografian arrasto arkeologiko ugari daudela
          mantentzen baitute, baina aurkitzen jakin
          behar da. Horretan dago giltza. Esperientzia,
          ezagutza eta urteen joanean garaturiko
          intuizioa dira bidea zehazten dutenak.

          Azken hamarkada honetan, urte askoren
          ondoren, taldekide berriak gehitu dira.

          Lehenengo berrogeita hamar urteak betetzeko
          ateetan, Antxieta Arkeologi Taldea hiru
          aldiz izan da albiste 2014 eta 2015ean zehar.
          Hiru aurkikuntza albiste izan dira daukaten
          garrantziagatik. Aurretik ezagutzen ziren hiru
          barrunbetan, arkeologikoki balio handia duten
          aztarnak aurkitu dituzte, zehazki Ezkuztan
          (Azpeitia), Danbolinzulon eta Erlaitzen (Zestoa).

          Gaur egun, Antxieta Arkeologi Taldea Maria
          Jose Iriarte eta Alvaro Arrizabalagak zuzentzen
          dute, Aranzadi Zientzia Elkarteko kideak.
    design:
      columns: '1'
  - block: markdown
    id: findings
    content:
      title: '<i class=''fas fa-search-location''></i>&nbsp;Aurkikuntzak'
      subtitle: ''
      text: |-
        {{< gallery album="aurkikuntzak" >}}
    design:
      columns: '1'
  - block: people
    id: people
    content:
      title: '<i class=''fas fa-users''></i>&nbsp;Taldea'
      subtitle:
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
      - Partaideak
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: contact
    id: contact
    content:
      title: <i class='fas fa-envelope'></i>&nbsp;Kontaktua
      subtitle:
      text: |2-
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

        Astearteetan, gaueko 21:30etatik aurrera,
        Soreasu 1. Kulturgunean dagoen gure lokalean
        biltzen gara.

        Oso erraza da. Jar zaitez gurekin kontaktuan
        ikasteko eta aldi berean ondo pasatzeko gogoa,
        ilusioa eta gure taldekide izan nahi baduzu,
        anima zaitez zerbait berria eta gizartearentzat
        interesgarria dena egitera, gizartea bera baita
        egingo dituzun aurkikuntzen onuragarri.

      # Automatically link email and phone or display as text?
      autolink: true
      
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true

      # Contact (edit or remove options as required)

      email: antxieta.arkeologi.taldea@outlook.com
      phone: 608 08 70 24
      address:
        street: Antxieta Arkeologia Taldea bulegoa<br> Soreasu 1. Kulturgunea
        city: Azpeitia
        region: Gipuzkoa
        postcode: '20730'
        country: Espainia
        country_code: ES
      coordinates:
        latitude: '43.1867'
        longitude: '-2.2639'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Asteartea 21:00-23:00 bulegoan'
      # appointment_url: 'https://calendly.com'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/Antxieta_Taldea'
        - icon: instagram
          icon_pack: fab
          name: Instagram
          link: 'https://www.instagram.com/antxieta_arkeologi_taldea'
        - icon: youtube
          icon_pack: fab
          name: YouTube
          link: 'https://www.youtube.com/channel/UCWUlFhZBxXqodnvo7FVSkuw'
        - icon: newspaper
          icon_pack: fas
          name: Uztarria
          link: 'https://uztarria.eus/komunitatea/antxietaarkeologia'
        - icon: newspaper
          icon_pack: fas
          name: Danbolin
          link: 'https://danbolin.eus/category/antxieta-arkeologia-taldea'
  
    design:
      columns: '1'

---
