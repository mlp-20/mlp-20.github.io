---
layout: default
title: Home
---

# Manuel Leite Pinho — Process Engineer

*Simulation, process design and digital tools for the chemical industry.*

- **Dynamic simulation** at Air Liquide with Aspen HYSYS Dynamics and Aspen Plus
- **Digital delivery** at Galp: SAP S/4HANA and digitalisation projects across Portugal, Spain and Cabo Verde
- **Research** published in two peer-reviewed papers on biodiesel column modelling and control

<div class="cta-block">
  {% assign cv = site.static_files | where: "path", "/assets/cv.pdf" %}
  {% if cv.size > 0 %}<a class="primary" href="{{ '/assets/cv.pdf' | relative_url }}">Download CV</a>{% endif %}
  <a href="mailto:{{ site.social.email }}">Get in touch</a>
</div>

I'm a chemical engineer with four years of experience across process engineering, digital transformation and research. I'm based in Frankfurt, where I build process simulations and the tools around them. Before that I spent two and a half years at Galp running technology projects and improving processes.

---

## Featured Work

### Biodiesel washing column: modelling and control

> **Tools:** gPROMS, MATLAB, Simulink · **Result:** two peer-reviewed publications

A rigorous dynamic model of an industrial packed extraction column, with a control study built on top of it. It began as my master's thesis and continued as research work.

### PFD generator tool

> **Tools:** draw.io · **Result:** shared with colleagues through internal training

A tool that generates process flow diagrams, plus internal training sessions I lead so colleagues can use it.

### Root cause analysis from plant data

> **Tools:** Python · **Result:** clear dynamic plots from raw plant data

Turning raw plant data into plots that show how a disturbance developed, so the root cause can be found.

[View all projects →]({{ '/projects.html' | relative_url }})

---

## Experience

### Process Engineer, Air Liquide (2024 – present)
Dynamic simulation, process modelling for CO₂-to-methanol, P&ID design and internal tooling.

### Business Analyst / Project Manager, Galp (2022 – 2024)
Technology and digitalisation projects in oil and gas, SAP S/4HANA rollouts and process optimisation.

### Research Engineer, CERENA (2022)
Modelling and control of a biodiesel washing column.

**Education:** MSc (2021) and BSc (2019) in Chemical Engineering, Instituto Superior Técnico

[More about me →]({{ '/about.html' | relative_url }})

---

## Contact

- Email: [{{ site.social.email }}](mailto:{{ site.social.email }})
- LinkedIn: [linkedin.com/in/{{ site.social.linkedin }}](https://www.linkedin.com/in/{{ site.social.linkedin }})
- GitHub: [{{ site.social.github }}](https://github.com/{{ site.social.github }})
