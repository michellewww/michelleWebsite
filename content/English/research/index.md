<style>
.experience-card {
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px;
  margin-bottom: 10px;
  cursor: pointer; /* Add cursor pointer to indicate clickable */
  transition: transform 0.3s ease; /* Add transition for smooth animation */
  position: relative;
}

.experience-card:hover {
  transform: scale(1.05); /* Enlarge the card on hover */
}

.experience-card h3 {
  margin-top: 0;
}

.experience-card p {
  margin: 5px 0;
}

.experience-card ul {
  margin-top: 5px;
  margin-bottom: 5px;
}

.experience-card li {
  margin-left: 20px;
}

.experience-card .skills {
  margin-top: 5px;
}

.experience-card .skills span {
  background-color: #D3D3D3;
  color: #000000;
  padding: 3px 8px;
  border-radius: 10px;
  margin-right: 5px;
  font-size: 12px;
}

.external-link {
  position: absolute;
  top: 10px;
  right: 30px;
  width: 35px;
  height: 35px;
  cursor: pointer;
}
</style>

<script>
// JavaScript to toggle expand/collapse when clicking on the card title
document.addEventListener("DOMContentLoaded", function() {
  var cards = document.querySelectorAll('.experience-card');
  cards.forEach(function(card) {
    var title = card.querySelector('h3');
    var details = card.querySelector('details');
    title.addEventListener('click', function() {
      details.open = !details.open;
    });
  });
});
</script>

# Research

<div class="experience-card" id="research1">
  <h3>JHU Autonomy OWL</h3>
  <a href="https://owl.wse.jhu.edu/projects-2/" class="external-link" target="_blank">
    <img src="ext_link_icon.png" />
  </a>
  <p class="skills">
    <span>Machine Learning</span>
    <span>Edge Detection</span>
    <span>Remote Sensing</span>
  </p>
    <strong>Year: 01/2022 - 08/2022</strong>
    <p><strong>Overview:</strong></p>
    <p>An AI observatory, workshop and laboratory for critical infrastructure resilience.</p>
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li>Leveraged machine learning techniques to adapt terrestrial applications to the unique constraints of the space domain.</li>
      <li>Showcased web development expertise by strategically redesigning and updating the lab website, creating a fresh visual
        identity, and optimizing content for improved search engine visibility.</li>
      <li>Earned a presentation slot at the 2022 ASCEND conference with my proposal, titled "Spacecraft Diagnostic Generation from
        Remote Sensing for OSAM Mission," emphasizing my contributions in remote sensing and mission diagnostics.</li>
    </ul>
  </details>
</div>

<div class="experience-card" id="research2">
  <h3>JHU ARCADE Lab</h3>
  <a href="https://arcade.cs.jhu.edu/" class="external-link" target="_blank">
    <img src="ext_link_icon.png" />
  </a>
  <p class="skills">
    <span>DaVinci Machine</span>
    <span>wavelets</span>
    <span>Brain Signals</span>
  </p>
    <strong>Year:</strong> 01/2022 - 06/2022
    <!-- Your detailed content for Project Name 1 goes here -->
    <p><strong>Overview:</strong> Design Systems that pioneer human-centered solutions that are enabled by synergistic advancements across imaging, computer vision, machine learning, and interaction design that are embodied in emerging technology such as mixed reality and robots.</p>
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li>Collaborated closely with professors to conduct comprehensive research on the Da Vinci surgical machine and enhance
        surgical precision and mitigate medical accidents caused by surgeon fatigue.</li>
      <li>Contributed to the development of algorithms using wavelets to enable cognitive load-aware user interfaces for mixed reality
        nvironments, delving into the analysis of cognitive load factors such as eye movement patterns and brain signals.</li>
    </ul>
</div>
