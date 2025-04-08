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
        I am a research scientist in the Department of Radiology at Brigham and Women’s Hospital and an Instructor in Radiology at Harvard Medical School. My work lies at the intersection of engineering, imaging, and medicine, with a focus on developing MR-compatible robotic systems to enhance the precision and effectiveness of minimally invasive procedures.
        
        My background is in electrical and biomedical engineering, and I have spent the last several years designing, building, and validating image-guided robotic devices for clinical use. I am especially interested in how advanced imaging technologies, such as MRI, can be paired with robotic assistance to guide needle-based interventions in a way that is safer, more accurate, and less invasive.
        
        Beyond the lab, I am passionate about interdisciplinary collaboration -- bringing together clinicians, engineers, and scientists to solve real-world medical problems. Whether it is helping guide a needle to a deep-seated tumor or building the tools to make that possible, I am always looking for ways to translate engineering innovations into meaningful clinical impact.
        
        You can explore more about my projects, publications, and teaching using the menu above, or reach out if you’d like to connect or collaborate.
      
        _(Header Image: [Pont du Gard Aqueduct](https://pontdugard.fr/en). Image by Renata Condé da Frota Moreira.)_

    design:
      columns: '1'
    appearance:
      font_size: 's'

---
