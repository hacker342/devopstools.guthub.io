---
layout: home
header:
  title: Комплексные IT-решения для вашего бизнеса
  text: >
        Внедрение DevOps, разработка ботов, разработка и внедрение CRM на Django.
        Настройка серверов,удаленный доступ,системы мониторинга. 
  action: # action button is optional
    label: О НАС
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: Начните работать с нами!
    text: Разрабатываем IT-решения для вашего бизнеса! Внедряем DevOps,разрабатываем веб-системы, ботов, оказываем поддержку. Оказываем полный спектр ИТ решений. 
    actions:
      - title: Связаться с нами!
        url: '#page-top'
        class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: Услуги
    services:
      - title: Внедрение DevOps
        text: Внедряем ci/cd, обучаем DevOps.
        icon: fa-laptop-code
      - title: Разработка ботов
        text: Разрабатываем ботов с помощью API Telegram
        icon: fas fa-robot
      - title: Разработка сайтов
        text: Разработка веб-систем на Django.
        icon: fas fa-keyboard
      - title: Настройка серверов
        text: Настройка Linux серверов
        icon: fas fa-server
      - title: Тех.поддержка
        text: Техническая поддержка
        icon: fas fa-server

     

  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This is a very short project description.
        icon: 2.jpg
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'

  
  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: +1 (202) 555-014
      icon: fa-phone
    - title: E-Mail
      icon: fa-envelope
      url: mailto:contact@yourwebsite.com
    - title: Twitter
      icon: fa-twitter
      icon_type: fab
      url: '#'
    - title: Facebook
      icon: fa-facebook
      icon_type: fab
      url: '#'

---
