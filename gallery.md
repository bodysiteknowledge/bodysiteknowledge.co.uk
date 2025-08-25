---
images:
  - slug: "cosmic-consciousness"
    title: "Cosmic Consciousness"
  - slug: "interdepence II"
    title: "Interdepence II"
  - slug: "kinship-women-in-conversation-III"
    title: "Kinship Women In Conversation III"
  - slug: "salutogenic-orientation"
    title: "Salutogenic Orientation"
  - slug: "women-in-conversation-II-sentient"
    title: "Women In Conversation II Sentient"
  - slug: "dancers-and-development"
    title: "Dancers And Development"
  - slug: "interdepence-I-on-being"
    title: "Interdepence I On Being"
  - slug: "light-language-I"
    title: "Light Language I"
  - slug: "there-to-be-close-to-her"
    title: "There To Be Close To Her"
  - slug: "focus-a-sense-of-coherence"
    title: "Focus A Sense Of Coherence"
  - slug: "its-a-process-interdepence-III"
    title: "It‘s A Process Interdepence III"
  - slug: "mosses-and-waterbears"
    title: "Mosses And Waterbears"
  - slug: "women-in-conversation-1-spirit"
    title: "Women In Conversation 1 - Spirit"
---

# Gallery

![Women in Conversation 1 - Spirit](images/gallery/women-in-conversation-1-spirit.jpg)
Women in Conversation 1 - Spirit

{% for image in page.images %}

  <h2>{{ image.title }}</h2>
  ![{{image.title}}](images/gallery/{{image.slug}}.jpg)

{% endfor %}
