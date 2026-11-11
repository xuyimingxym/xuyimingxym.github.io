- 2026.11: I joined Columbia University as a Postdoctoral Research Scientist in Civil Engineering and Engineering Mechanics.

- 2026.10: 4 papers have been accepted by TRB 2027.

{% assign paper = site.publications | where: 'key', 'robophys-3d' | first -%}
- 2026.10: Our paper, "{{ paper.title }}," has been accepted at WACV {{ paper.year }}.

{% assign paper = site.publications | where: 'key', 'mode-choice' | first -%}
- 2026.08: Our paper, "{{ paper.title }}," has been published in {{ paper.venue }}. [[Paper Link]]({{ paper.paperurl }})

{% assign paper = site.publications | where: 'key', 'xr-dt' | first -%}
- 2026.06: Our paper, "{{ paper.title }}," has been accepted by IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026.

{% assign talk = site.talks | where: 'key', 'traveler-agents' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave an invited talk, "{{ talk.title }}," at the [{{ talk.venue }}]({{ talk.event_url }}) in {{ talk.location }}.

- 2026.03: Our project, “Neuro-Symbolic Edge AI for AV Safety: A Knowledge-Graph Guided VLM,” has been selected for the [NVIDIA Academic Grant Program](https://www.nvidia.com/en-us/industries/higher-education-research/academic-grant-program/)! 🎉

{% assign talk = site.talks | where: 'key', 'texas-ml' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave an invited talk, "{{ talk.title }}," at [{{ talk.venue }}]({{ talk.event_url }}), {{ talk.location }}.

{% assign talk = site.talks | where: 'key', 'trb-smarter-cities' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave an invited talk, "{{ talk.title }}," at TRB 2026 Lectern Session 4039 - Digital Twins: Simulating Systems Across Sectors.

{% assign talk = site.talks | where: 'key', 'trb-road-infrastructure' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave an invited talk, "{{ talk.title }}," at TRB 2026 Lectern Session 4068 - Digitization of Road Infrastructure.

{% assign paper = site.publications | where: 'key', 'arcas' | first -%}
- 2026.01: Our paper, "{{ paper.title }}," has been accepted by 2026 IEEE Intelligent Vehicles Symposium (IV).

{% assign paper = site.publications | where: 'key', 'decentralized-twin' | first -%}
- 2025.11: Our paper, "{{ paper.title }}," has been accepted by AAAI 2026 Deployable AI workshop.

{% assign paper = site.publications | where: 'key', 'agent-sumo' | first -%}
- 2025.10: Our paper, "{{ paper.title }}," has been accepted by NeurIPS 2025 UrbanAI workshop. [[Code]]({{ site.data.research.agent_sumo.code_url }})[[Video]](https://www.youtube.com/watch?v={{ site.data.research.agent_sumo.youtube_id }})

- 2025.10: 2 papers have been accepted by TRB 2026.

{% assign paper = site.publications | where: 'key', 'street-semantic-tree' | first -%}
- 2025.10: Our paper, "{{ paper.title }}," has been published in {{ paper.venue }}. [[Paper Link]]({{ paper.paperurl }})

{% assign paper = site.publications | where: 'key', 'ev-crashes' | first -%}
- 2025.10: Our paper, "{{ paper.title }}", has been published in {{ paper.venue }}. [[Paper Link]]({{ paper.paperurl }})

{% assign paper = site.publications | where: 'key', 'llm-ethics' | first -%}
- 2025.10: Our paper, "{{ paper.title }}," has been published in AI Ethics. [[Paper Link]]({{ paper.paperurl }})

{% assign paper = site.publications | where: 'key', 'hlcg' | first -%}
- 2025.10: Our paper, "{{ paper.title }}," has been published in {{ paper.venue }}. [[Paper Link]]({{ paper.paperurl }})

{% assign paper = site.publications | where: 'key', 'charger-equity' | first -%}
- 2025.09: Our paper, "{{ paper.title }}", has been published in {{ paper.venue }}. [[Paper Link]]({{ paper.paperurl }})

{% assign talk = site.talks | where: 'key', 'austin-partnership' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave a talk, "{{ talk.title }}," at the City of Austin - Digital Twin Partnership In Action workshop in {{ talk.location }}.

{% assign talk = site.talks | where: 'key', 'smart-cities-ai' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave a talk, "{{ talk.title }}," at the 2025 {{ talk.venue }} in {{ talk.location }}.

{% assign talk = site.talks | where: 'key', 'good-systems' | first -%}
- {{ talk.sort_month | replace: '-', '.' }}: I gave a talk, "{{ talk.title }}," at the 2025 {{ talk.venue }} in {{ talk.location }}.

{% assign paper = site.publications | where: 'key', 'austin-digital-twin' | first -%}
- 2025.01: I presented our work, "{{ paper.title }}," at TRB {{ paper.year }}.

- 2024.10: 8 papers have been accepted by TRB 2025, including 1 presentation and 7 posters.

- 2024.10: Excited to deploy my new personal website.
