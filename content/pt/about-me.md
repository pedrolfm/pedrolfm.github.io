---
title: "Sobre mim"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: markdown
    id: section-2
    content:
      title: ""
      subtitle: ""
    design:
      background:
        image:
          # Name of image in `assets/media/`.
          filename: maracana_3.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 1
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: actual
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: top
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0px', '0', '325px', '0']
  - block: markdown-wide
    content:
      title: Sobre mim
      subtitle: 
      text: |-
        Sou um pesquisador no Departamento de Radiologia do Brigham and Women's Hospital e instrutor de Radiologia na Harvard Medical School. Meu trabalho está na intersecção entre engenharia, imagem e medicina, com foco no desenvolvimento de sistemas robóticos compatíveis com ressonância magnética para aprimorar a precisão e a eficácia de procedimentos minimamente invasivos.

        Minha formação é em engenharia elétrica e biomédica, e passei os últimos anos projetando, construindo e validando dispositivos robóticos guiados por imagem para uso clínico. Tenho especial interesse em como tecnologias avançadas de imagem, como a ressonância magnética, podem ser combinadas com assistência robótica para guiar intervenções com agulhas de forma mais segura, precisa e menos invasiva.

        Também sou apaixonado por colaboração interdisciplinar. A minha linha de pesquisa envolve o trabalho conjunto de clínicos, engenheiros e cientistas para resolver problemas médicos do mundo real. Seja ajudando a guiar uma agulha até um tumor profundo ou desenvolvendo as ferramentas para tornar isso possível, estou sempre buscando maneiras de traduzir inovações de engenharia em impacto clínico significativo.

        Você pode explorar mais sobre meus projetos, publicações e ensino usando o menu acima. Ou entre em contato comigo caso tenha interesse em se conectar ou colaborar.
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['3rem', '0px', '0px', '0px']
  - block: contact-network
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0px', '0px', '0px', '0px']
  - block: markdown-wide
    content:
      title: 
      subtitle: 
      text: |
        <em style="font-size: 14px;">(Imagem de cabeçalho: [Estádio Maracanã, Rio de Janeiro, Brasil](https://riotur.rio/que_fazer/maracana/). Imagem de Bianca Tarrisse da Fontoura.)</em>
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0px', '0px', '0px', '0px']

---
