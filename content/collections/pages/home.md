---
id: home
blueprint: pages
title: Home
template: home
author: bbddf358-6361-47b9-ac37-52545ec3039f
meta_title: 'Your Page/Site Name'
meta_description: 'Your Page Meta Description'
meta_keywords: 'Tag 1, Tag 2'
og_title: 'OG Title'
og_description: 'OG Description'
og_image: logo.png
other_meta_tags:
  -
    id: lgnmvvg3
    meta_tag_name: http-equiv
    meta_tag_value: Author
    meta_tag_value_name: content
    meta_tag_value_name_value: 'John Doe'
updated_by: bbddf358-6361-47b9-ac37-52545ec3039f
updated_at: 1681940005
block_types:
  -
    id: lgnnkuye
    title_1: "Hello, i'm"
    title_2: Manup
    title_3: Rav
    image: photo-1438761681033-6461ffad8d80.jpg
    svg_data: |-
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                      <path fill="#ffffff" fill-opacity="1" d="M0,128L60,149.3C120,171,240,213,360,192C480,171,600,85,720,85.3C840,85,960,171,1080,197.3C1200,224,1320,192,1380,176L1440,160L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path>
                    </svg>
    edit_template: true
    template: |-
      <!-- section hero -->
              <div id="sectionhero" class="sectionblock">
                  <div class="container">
                      <div class="row">
                          <div class="col-lg-6 pr-0 mr-0 pl-lg-0 pr-lg-5 mr-lg-0 mt-3 mt-lg-0 align-items-center justify-content-center align-items-lg-left justify-content-lg-left text-center text-lg-left d-flex order-1 order-lg-0 ">
                              <div class="infohero ">
                                  <p class="infohero__p">{{title_1}}</p>
                                  <h1 class="infohero__title">{{title_2}}
                                      <span>{{title_3}}</span>
                                  </h1>
                                  <span id="typed-text">{{fields_work_with}}</span>
                                  <span class="cursor blink">&nbsp;</span>
                              </div>
                          </div>
                          <div class="col-lg-6 text-center order-0 order-lg-1 mb-5 mb-lg-0">
                              <div class="heroimg">
                                  <img src="{{image}}" alt="poto" class="img-fluid heroimg__poto" />
                              </div>
                          </div>
                      </div>
                  </div>
                  {{svg_data}}        
                  </div>
              <!-- end section hero -->
    type: home_hero
    enabled: true
    fields_work_with: 'UI/UX Design,Web Developer,Product Design,Digital Marketing,Logo Design, Web Design'
  -
    id: lgno7xy1
    name: 'Manup Rav'
    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur dolores quaerat perferendis expedita rem, neque consequuntur cum ullam magnam nulla nesciunt velit! Velit amet dolores iure dicta. Velit, placeat cum?'
    box_1:
      -
        id: lgno80qy
        title: 'FULL NAME'
        field_value: 'Manup Rav'
      -
        id: lgno82a9
        title: EMAIL
        field_value: manup.rav@gmail.com
      -
        id: lgno8bam
        title: Phone
        field_value: '+918907289865'
    box_2:
      -
        id: lgno8k1m
        title: Location
        field_value: Trivandrum
    cv_url: 'http://www.revolve314.com'
    numbers:
      -
        id: lgno8pqm
        title: 'Projects completed'
        field_value: '200'
      -
        id: lgno8rto
        title: 'Happy Clients'
        field_value: '500'
      -
        id: lgno94uz
        title: 'Winning Awards'
        field_value: '100'
      -
        id: lgno9jqa
        title: 'On Projects'
        field_value: '10'
    edit_template: true
    template: |-
      <!-- about section -->
              <div id="aboutsection" class="sectionblock">
                  <div class="container">
                      <div class="row">
                          <div class="col-lg-4 text-center text-lg-left">
                              <div class="abouthero">
                                  <h3>{{name}}</h3>
                              </div>
                          </div>
                          <div class="col-lg-8 pl-lg-5 text-center text-lg-left">
                              <div class="infoabout">
                                  <p class="infoabout__title">
                                      {{description}}
                                  </p>
                                  <div class="row  text-center text-lg-left">
                                      <div class="col-lg-6">
                                          <ul class="infoabout__list">
                                              
                                              {{box_1}}
                                              
                                              <li>
                                                  <div class="infoabout__wrap">
                                                      <span class="mt-4 mb-2 d-block infoabout__title">{{title}}</span>
                                                      <p>
                                                          {{field_value}}
                                                      </p>
                                                  </div>
                                              </li>
                                              {{/box_1}}
                                          </ul>
                                      </div>
                                      <div class="col-lg-6">
                                          <ul class="infoabout__list">
                                              {{box_2}}
                                              
                                              <li>
                                                  <div class="infoabout__wrap">
                                                      <span class="mt-4 mb-2 d-block infoabout__title">{{title}}</span>
                                                      <p>
                                                          {{field_value}}
                                                      </p>
                                                  </div>
                                              </li>
                                              {{/box_2}}
                                          </ul>
                                      </div>
                                      <a href="{{cv_url}}" target="_blank" class="btn linkbtn aboutlink mt-4">
                                          Download Cv
                                      </a>
                                  </div>
                              </div>
                          </div>
                          <div class="col-lg-12 mt-5 mb-4 pt-5">
                              <div class="row">
                                  
                                  {{numbers}}
                                  <div class="col-lg-3">
                                      <div class="counterwrap">
                                          <p class="counterwrap__counternum"><span class="counterwrap__counter" data-Speed="5000">{{field_value}}</span><span class="icon">+</span></p>
                                          <p>{{title}}
                                          </p>
                                      </div>
                                  </div>
                                  {{/numbers}}
                                  
                              </div>
                          </div>
                      </div>
                  </div>

              </div>
              <!-- end about -->
    type: about_me
    enabled: true
  -
    id: lgnp19rp
    services:
      -
        id: lgnp1dat
        icon: 'fa-solid fa-bullhorn'
        title: 'Digital Marketing'
        description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maxime ex asperiorest.'
      -
        id: lgnp1fyf
        icon: fa-cubes
        title: 'Web Design'
        description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maxime ex asperiorest.'
      -
        id: lgnp1kdu
        icon: fa-bullhorn
        title: 'Digital Marketing'
        description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maxime ex asperiorest.'
      -
        id: lgnp1oc0
        icon: 'fa-solid fa-bullhorn'
        title: 'Logo Design'
        description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maxime ex asperiorest.'
      -
        id: lgnp1r45
        icon: 'fa-solid fa-bullhorn'
        title: SEO
        description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maxime ex asperiorest.'
    edit_template: true
    template: |-
      <!-- service section -->
              <div id="servicesection" class="sectionblock">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                      <path fill="#ffffff" fill-opacity="1" d="M0,96L60,117.3C120,139,240,181,360,186.7C480,192,600,160,720,138.7C840,117,960,107,1080,117.3C1200,128,1320,160,1380,176L1440,192L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z"></path>
                    </svg>
                  <div class="container">
                      <div class="row">
                          <div class="col-lg-12">
                              <div id="sliderservice" class="sliderservice__contentinner keen-slider">
      	                        {{services}}
                                  <div class="wrapservice keen-slider__slide text-center text-lg-left">
                                      <i class="fa-solid {{icon}}"></i>
                                      <h3 class="mt-3 wrapservice__title">{{title}}</h3>
                                      <p>{{description}}</p>
                                  </div>
                                  {{/services}}
                                  </div>

                          </div>
                      </div>
                  </div>
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#ffffff" fill-opacity="1" d="M0,96L60,117.3C120,139,240,181,360,197.3C480,213,600,203,720,186.7C840,171,960,149,1080,160C1200,171,1320,213,1380,234.7L1440,256L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path></svg>
              </div>
              <!-- end service section -->
    type: services
    enabled: true
  -
    id: lgnpo75m
    filters: |-
      <ul id="filterwrap" class="warpfilter__filter justify-content-left text-center text-lg-left">
                                      <li data-group="all" class="active">All</li>
                                      <li data-group="web">Web Design</li>
                                      <li data-group="branding">Branding</li>
      <li data-group="logo">Logo</li>
                                  </ul>
    items:
      -
        id: lgnpo9mn
        category: web
        image: stock-photo-detailed-lever-on-old-lathe-645704086.jpg
      -
        id: lgnppg3f
        category: branding
        image: stock-photo-simple-detail-of-a-handlebar-belonging-to-an-old-motorcycle-in-a-state-of-corrosion-1144557941.jpg
      -
        id: lgnpppa1
        category: logo
        image: logo-05.jpg
      -
        id: lgnpq10k
        category: logo
        image: logo-07.jpg
    edit_template: true
    template: |-
      <!-- portfolio section -->
              <div id="portfoliosection" class="sectionblock">
                  <div class="container">
                      <div class="row">
                          <div class="col-lg-12 text-center">
                              <!-- filter portfolio -->
                              <div class="warpfilter text-left">
                                  {{filters}}
                              </div>
                              <!-- end filter portfolio -->
                              <div id="porfoliowarp" class="grid-gutter-md grid-col-3">
                                  <!--  PORFOLIO ITEM -->
                                  {{items}}
                                  <div class="porfoliowarp__item" data-groups='["{{category}}"]'>
                                      <a class="porfoliowarp__portolink glightbox" data-glightbox="type: image" href="{{image}}">
                                          <i class="fa-solid fa-circle-plus"></i>
                                          <div class="porfoliowarp__content" style="background: url({{image}}) no-repeat center;  background-position: center;
                              background-size: cover;"></div>
                                      </a>
                                  </div>
                                  {{/items}}
                                  <!-- END PORTFOLIO ITEM -->
                                  
                              </div>
                              <a href="#" class="btn linkbtn mt-5">
                                  More Works
                              </a>
                          </div>
                      </div>
                  </div>
              </div>
              <!-- end portfolio section -->
    type: portfolio
    enabled: true
  -
    id: lgnqrdux
    title: "Let's get intouch"
    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam itaque, eos a maxime numquam inventore officia quam.'
    address: '30 Unkown Street, Harrmony Hills Bogor, 16610 Indonesia'
    phone: '+918907289865'
    email: manup.rav@gmail.com
    social_media:
      -
        id: lgnqrgqx
        icon: fa-facebook
        link: 'http://www.facebook.com'
      -
        id: lgnqrj2q
        icon: fa-twitter
        link: 'http://www.facebook.com'
      -
        id: lgnqrlgn
        icon: fa-github
        link: 'http://www.facebook.com'
    edit_template: true
    template: |-
      <!-- contact section -->
              <div id="contactsection" class="sectionblock">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                      <path fill="#ffffff" fill-opacity="1" d="M0,96L60,117.3C120,139,240,181,360,186.7C480,192,600,160,720,138.7C840,117,960,107,1080,117.3C1200,128,1320,160,1380,176L1440,192L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z"></path>
                    </svg>
                  <div class="container">
                      <div class="row">
                          <div class="col-lg-6 pr-lg-5">
                              <div class="contactdetail">
                                  <h3 class="contactdetail__title mb-4">
                                      {{title}}
                                  </h3>
                                  <p>{{description}}</p>
                                  <ul class="contactdetail__list">
                                      <li>
                                          <span class="contactdetail__span">
                                              {{address}}
                                           </span>
                                      </li>
                                      <li>
                                          <span class="contactdetail__span">
                                              {{phone}}
                                          </span>
                                      </li>
                                      <li>
                                          <span class="contactdetail__span">
                                              {{email}}
                                          </span>
                                      </li>
                                  </ul>
                                  <ul class="contactdetail__sosmed">
                                      
                                      {{social_media}}
                                      <li>
                                          <a href="{{link}}" target="_blank">
                                              <i class="fa-brands {{icon}}"></i>
                                          </a>
                                      </li>
                                      {{social_media}}
                                      
                                  </ul>
                              </div>
                          </div>
                          <div class="col-lg-6">
                              <div class="contactform">
                                {{ form:contact }}
       
          
          {{ if success }}
              <div class="bg-green-300 text-white p-2">
                  {{ success }}
              </div>
          {{ else }}
             
              {{ if errors }}
                  <div class="bg-red-300 text-white p-2">
                      {{ errors }}
                          {{ value }}<br>
                      {{ /errors }}
                  </div>
              {{ /if }}
       
            
              {{ fields }}
                  <div class="p-2">
                      <label>{{ display }}</label>
                      <div class="p-1">{{ field }}</div>
                      {{ if error }}
                          <p class="text-gray-500">{{ error }}</p>
                      {{ /if }}
                  </div>
              {{ /fields }}
       
             
              <input type="hidden" class="hidden" name="{{ honeypot ?? 'honeypot' }}">
       
              
              <button type="submit" class="btn mt-5  contactform__submitbuton linkbtn mt-5 mb-3">Submit</button>
          {{ /if }}
       
      {{ /form:contact }}
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
              <!-- end contact section -->
    type: contact_us
    enabled: true
---
