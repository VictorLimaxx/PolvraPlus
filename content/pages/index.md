---
title: Inicio
slug: /
sections:
  - type: GenericSection
    title:
      text: Bem Vindo ao Site do PolvoraCraft
      color: text-dark
      type: TitleBlock
      styles:
        self:
          fontWeight: 700
    subtitle: O melhor servidor de minecraft java e bedrock
    text: >+
      <div style="text-align: left">O site Pólvora foi criado para fortalecer e
      expandir a comunidade em torno do nosso servidor de Minecraft. Ele serve
      como um ponto de encontro para jogadores que compartilham a paixão por
      explorar, criar e se aventurar em um universo único.

      Nosso objetivo é oferecer um espaço completo, onde os jogadores possam
      encontrar informações sobre o servidor, regras, eventos, suporte e
      novidades, além de fortalecer as conexões entre a comunidade.

      O Pólvora é mais do que um site: é o coração digital de uma comunidade
      vibrante, feita por jogadores e para jogadores. Aqui, você sempre
      encontrará um lugar para explorar e crescer!

      Seja bem-vindo ao Pólvora! Construa sua história com a gente.</div>

    actions:
      - label: começar
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/abstract-feature1.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Inicio
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        margin:
          - mt-2
      subtitle:
        fontWeight: 500
  - type: FeaturedItemsSection
    title:
      text: Java e Bedrock
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: IP's de conexão
    items:
      - type: FeaturedItem
        title: Bedrock
        subtitle: IP de conexão
        text: >
          <div style="text-align: left">Endereço:
          PolvoraCraftPlus.aternos.me</div>


          Porta: 62763
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/19d0ccd35aa96bac4f7f4c4c422c052e.png
          styles:
            self:
              borderRadius: x-large
      - title: Java
        subtitle: IP de conexão
        text: |
          IP:
          PolvoraCraftPlus.aternos.me:
          62763
        image:
          url: /images/19d0ccd35aa96bac4f7f4c4c422c052e.png
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Servidor Do discord
        subtitle: Link's
        text: |
          [https://discord.gg/pb3Q73raer ](https://discord.gg/pb3Q73raer)
        image:
          url: /images/19d0ccd35aa96bac4f7f4c4c422c052e.png
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    badge:
      label: Nossos servidores
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: Empresas premiadas confiam em nós
    images:
      - url: /images/empathy-logo.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - altText: Sanity logo
        type: ImageBlock
      - altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Fundadores presentes do PolvoraCraft
        tagline: Feature 1
        subtitle: Credito's
        text: >+
          **Limaaxx** – Desenvolvedor web, especializado em organizar e
          solucionar problemas dentro da comunidade com eficiência e dedicação.


          **Rouxx** – Fundador principal, responsável por implementar novas
          ideias para o servidor e gerenciar contratos de forma estratégica.



        image:
          type: ImageBlock
          url: /images/19d0ccd35aa96bac4f7f4c4c422c052e.png
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Social Media Management
      color: text-dark
      type: TitleBlock
    subtitle: Increase your reach
    text: >
      A service that helps businesses to manage their social media accounts and
      posts.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero2.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Business Consulting
      color: text-dark
      type: TitleBlock
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: CarouselSection
    title: null
    subtitle: O que você precisa saber
    items:
      - title: >-
          “Um designer sabe que alcançou a perfeição não quando não há mais nada
          a acrescentar, mas quando não há mais nada a retirar.”
        tagline: ''
        subtitle: 'Limaaxx, Company'
        text: ''
        image:
          url: /images/Limaax.gif
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “Um designer sabe que alcançou a perfeição não quando não há mais nada
          a acrescentar, mas quando não há mais nada a retirar.”
        tagline: ''
        subtitle: 'Limaaxx, Company'
        text: ''
        image:
          url: /images/Limaax.gif
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design pode ser arte. Design pode ser estética. Design é tão simples,
          por isso é tão complicado."
        tagline: ''
        subtitle: 'Limaaxx, Company'
        text: ''
        image:
          url: /images/Limaax.gif
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Entre em contato com nossa equipe
      color: text-dark
      type: TitleBlock
    subtitle: Envie um Gmail para nossa equipe web
    text: "**Por que entrar em contato com nossa equipe?**\n\nNossa equipe está sempre pronta para ajudar! Seja para tirar dúvidas, resolver problemas, compartilhar ideias ou sugerir melhorias, queremos garantir que você tenha a melhor experiência possível com o servidor Pólvora.\n\nEntre em contato conosco para:\n\n*   Obter suporte técnico ou esclarecer dúvidas.\n\n*   Reportar problemas ou sugestões de melhorias.\n\n*   Saber mais sobre nossos eventos, parcerias ou projetos.\n\n*   Conectar-se com a administração para propostas e oportunidades.\n\nEstamos aqui para ouvir você e tornar o Pólvora um lugar ainda melhor para todos! Não hesite em nos procurar. \U0001F60A\n"
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: enviar
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contato
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
