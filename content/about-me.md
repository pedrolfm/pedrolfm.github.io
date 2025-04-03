---
title: "About Me"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

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
          filename: aqueduct.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 1
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['200px', '0', '200px', '0']
  - block: markdown-wide
    content:
      title: About Me
      subtitle: 
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus et ipsum tristique orci egestas sodales a non arcu. Ut nunc ligula, aliquam non tellus et, faucibus faucibus neque. Suspendisse urna odio, auctor quis lacus quis, fermentum sollicitudin urna. Proin non justo pulvinar felis molestie convallis quis ac metus. Aliquam ultrices id sapien vitae pellentesque. Pellentesque maximus posuere ante eu aliquet. Proin lacinia ut mauris ac commodo. Aenean ut varius leo. Suspendisse placerat nulla eu metus semper suscipit et at nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Donec ultrices sapien non pretium pellentesque. 

        Nulla leo magna, tempus a fringilla ac, lobortis ac metus. Sed volutpat finibus tempus. Integer tincidunt non neque eget vulputate. Quisque laoreet sapien vitae nulla dignissim, a maximus erat aliquam. Nullam imperdiet lorem id vulputate pulvinar. Aliquam nec neque in sem ultricies bibendum sit amet eget est. Vivamus facilisis augue at felis suscipit, sed lacinia nulla efficitur. Maecenas et lectus ac nibh porttitor convallis. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

        You can see more details about my academic and professional experience [here]({{< relref "experience" >}})
    design:
      columns: '1'
    appearance:
      font_size: 's'

---
