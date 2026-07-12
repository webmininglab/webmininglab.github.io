---
title: "吴令飞"
excerpt: "匹兹堡大学副教授"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-18.jpg
  teaser: /assets/images/author/lingfei.jpg
sidebar:
  - title: "吴令飞"
    image: "/assets/images/author/lingfei.jpg"
    image_alt: "logo"
author: "吴令飞"
---

Lingfei Wu is an Associate Professor of Information Science at the University of Pittsburgh. He studies a foundational question for a world increasingly shaped by science and technology: How does innovation work?

His research draws on big data, complexity science, and AI to pursue this question along three lines. To measure innovation, he tracks the spread of ideas by analyzing millions of research papers and their citation patterns. This work helped establish the Disruption Index, the first validated metric for identifying breakthroughs by detecting when new ideas overtake the old (Nature, 2019; Science, 2026). To understand how innovation is produced, he studies the way researchers work together. His work shows that dividing labor across team members can increase productivity and impact, but it also leaves less room for individuals to take risks or be creative (PNAS, 2022; Nature, 2023). To connect innovation and society, he studies how science is increasingly driven by societal needs rather than scientists’ curiosity alone, and how those advances eventually change the world in return (PNAS, 2018; Nature Communications, 2025).

Wu’s work is widely recognized in Computational Social Science and the Science of Science. His research has been featured in The New York Times, Harvard Business Review, Forbes, The Atlantic, and Scientific American. He has advised organizations including the Novo Nordisk Foundation and the John Templeton Foundation, and his contributions have been supported by the NSF CAREER Award, an NIH R01 grant, the Richard King Mellon Award, and the Oxford Martin Fellowship.

[https://lingfeiwu.github.io/](https://lingfeiwu.github.io/)

<ul>
{% for post in site.posts %}
  {% if post.author == page.author %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
