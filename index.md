---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: blox
# title: 



header:
  topbar:
    - phone: "[+36 66 45 89 54](tel:+36 66 45 89 54)"
    - envelope: "[aze@exemple.com](mailto:aze@exemple.com)"
    - geo-alt: Ardèche / Côte d'Azur
  mode: fixed-top
#   offset: 500px
  logo:
    text: |
      Mathieu  
      Sarrazy
    # image: 
    url: "#"
  nav:
    align: right
  
hero:
  center-text:
    image: ./assets/img/backgrounds/w1920/Acceuil.jpg
    title: "Mathieu **Sarrazy**"
    texts:
      - Technicien, accordeur / restaurateur de piano
      - Diplômé de l’école Ignace Pleyel à Loos (59)
    actions:
      - label: Contactez moi
        url: "#contact"  


# Accord
accord:
  columns:
    - size: 7
      offset: 1
      content: _subjects/accord.md
      class: content

# Réglage mécanique
reglage:
  columns:
    - size: 7
      offset: 4
      content: _subjects/reglage.md
      class: content

# Harmonisation
harmonisation:
  columns:
    - size: 6
      offset: 5
      content: _subjects/harmonisation.md
      class: content

# Réparation
reparation:
  columns:
    - size: 7
      offset: 1
      content: _subjects/reparation.md
      class: content

# Restauration, Ébénisterie & Laque
restauration:
  columns:
    - size: 7
      offset: 1
      content: _subjects/restauration.md
      class: content

# Le numérique dans l’acoustique
numerique:
  columns:
    - size: 7
      offset: 4
      content: _subjects/numerique.md
      class: content



# Présentation
about:
  columns:
    - size: 12
    #   offset: 4
      content: _subjects/presentation.md
      class: content


# Gallerie
atelier:
  gallery: _subjects/atelier.md
    # photos:
    #   - assets/img/gallery/piano-462320.jpg
    #   - assets/img/gallery/piano-915784.jpg

# Contact
contact:
  contact:
    title: |
      ## **Contactez** moi
      Ut possimus qui ut temporibus culpa velit eveniet modi omnis est adipisci expedita at voluptas atque vitae autem.
    form:
      mailto: contact@exemple.com



---
