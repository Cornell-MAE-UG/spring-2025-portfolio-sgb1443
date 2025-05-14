---
layout: default
title: Sarah Grace Brown - Portfolio
permalink: /projects/
---

## Portfolio Projects

<ul>
  <li><a href="https://sgb1443.github.io/ece4160/" target="_blank">⚡ Fast Robots Portfolio (ECE 4160)</a> — control, mapping, and planning for high-speed autonomous vehicle</li>
  <li><a href="https://github.com/Cornell-Robotics-Mechatronics-Lab/mechatronics-project-sgb1443" target="_blank">🤖 Mechatronics Final Project</a> — full-stack design, build, and control of a BLE-driven autonomous robot</li>
</ul>

---

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url | relative_url }})
{% endfor %}
