---
layout: single
classes: wide
permalink: /schedule/
comments: true
---

### Schedule

| Time | Event |
|------|-------|
| 09:00 - 09:10 | Welcome and Introduction |
| 09:10 - 10:15 | **Presentation Session 1: Emerging Algorithms and Techniques** <br><span class="expand-link" onclick="toggleSession('session1')">[Click to view speakers]</span> |
| 10:15 - 10:30 | Poster Lightning Talks |
| 10:30 - 11:00 | Coffee Break |
| 10:40 - 11:30 | Poster Session (coincides with Coffee Break and Session #2) |
| 11:00 - 11:45 | **Presentation Session 2: Flight Infusion** <br><span class="expand-link" onclick="toggleSession('session2')">[Click to view speakers]</span> |
| 11:45 - 12:25 | Panel Discussion with Flight and Research Leaders |
| 12:25 - 12:30 | Conclusion |

<div id="session1" class="session-details" style="display: none;">
  <h4>Presentation Session 1: Emerging Algorithms and Techniques</h4>
  <ul>
    <li><strong>09:10 - 09:25</strong> Prof. Feifei Qian (USC) - "Towards Terrain-aware, High-mobility Robots for Planetary Explorations" </li>
    <li><strong>09:25 - 09:40</strong> Prof. Soon-Jo Chung (Caltech) - "Caution and Failure: AI for Space Robotics" </li>
    <li><strong>09:45 - 10:00</strong> Prof. Kazuya Yoshida (Tohoku) - "Toward Modular and Heterogeneous AI Robots: Challenges for Lunar Exploration and Outpost Construction" </li>
    <li><strong>10:00 - 10:15</strong> Prof. Giusy Falcone (Michigan) - "From Physical Insight to Autonomy: Toward Decision-Making Systems for Space Mobility" </li>
  </ul>
</div>

<div id="session2" class="session-details" style="display: none;">
  <h4>Presentation Session 2: Flight Infusion</h4>
  <ul>
    <li><strong>11:00 - 11:15</strong> Dr. Jean-Pierre de la Croix (NASA JPL) - "CADRE: A Technology Demonstration of Multi-Agent Autonomy on the Moon" </li>
    <li><strong>11:15 - 11:30</strong> Sofia Kwok (Starfish Space) - "Moving Towards Affordable and Available Satellite Servicing: Developing Novel Hardware for On-Orbit Satellite Servicing" </li>
    <li><strong>11:30 - 11:45</strong> Dr. Andrew Horchler (Astrobotic) - "Safe and Precise Lunar Landing" </li>
  </ul>
</div>

<style>
.expand-link {
  color: var(--usc-red);
  cursor: pointer;
  font-size: 0.9em;
  text-decoration: underline;
}

.expand-link:hover {
  color: var(--usc-dark-red);
}

.session-details {
  margin: 20px 0;
  padding: 20px;
  background-color: var(--usc-light-gray);
  border-radius: 8px;
  border-left: 4px solid var(--usc-red);
}

.session-details h4 {
  margin-top: 0;
  color: var(--usc-red);
}

.session-details ul {
  margin: 0;
  padding-left: 20px;
}

.session-details li {
  margin-bottom: 10px;
  line-height: 1.5;
}

.session-details strong {
  color: var(--usc-red);
}
</style>

<script>
function toggleSession(sessionId) {
  const details = document.getElementById(sessionId);
  
  if (details.style.display === 'none') {
    details.style.display = 'block';
  } else {
    details.style.display = 'none';
  }
}
</script>

