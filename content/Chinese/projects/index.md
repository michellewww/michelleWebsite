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

## Experience

<div class="experience-card" id="project1">
  <h3>dearYou Health</h3>
  <a href="https://www.dearyouhealth.org/" class="external-link" target="_blank">
    <img src="ext_link_icon.png" />
  </a>
  <p class="skills">
    <span>React Native</span>
    <span>TensorFlow</span>
    <span>Firebase</span>
    <span>Git Version Control</span>
  </p>
  <details>
    <summary><strong>Position:</strong> Tech Board Lead | <strong>Year:</strong> 01/2024 - current</summary>
    <!-- Your detailed content for Project Name 1 goes here -->
    <p><strong>Overview:</strong> DearYou Health is a youth-powered nonprofit dedicated to providing culturally-competent mental health support to underrepresented high school and college students, bridging connections to various therapy modalities and fostering an inclusive environment for prioritizing well-being.</p>
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li>Cross-Platform Compatibility: Spearheaded the tech team in utilizing React Native to ensure seamless user experience across various devices.</li>
      <li>AI-Driven Matching Algorithm: Implemented a sophisticated AI algorithm utilizing TensorFlow for precise matching of students with suitable counselors/therapists. This involved intricate neural network design and parameter fine-tuning to achieve exceptional accuracy and efficiency.</li>
      <li>Enhanced Functionality: Integrated Firebase for secure user authentication and data storage. Incorporated third-party APIs to verify therapist credentials, ensuring user safety and enhancing app functionality.</li>
    </ul>
  </details>
</div>

<div class="experience-card" id="project2">
  <h3>Quest2Learn</h3>
  <a href="https://www.q2l.app/" class="external-link" target="_blank">
    <img src="ext_link_icon.png" />
  </a>
  <p class="skills">
    <span>Unity</span>
    <span>React3Fiber</span>
    <span>React</span>
    <span>ARKit</span>
    <span>Git Version Control</span>
  </p>
  <details>
    <summary><strong>Position:</strong> Software and UI/UX Engineer | <strong>Year:</strong> 01/2023 - 10/2023</summary>
    <!-- Your detailed content for Project Name 1 goes here -->
    <p><strong>Overview:</strong> Quest2Learn revolutionizes science education by transforming any environment into an immersive laboratory through augmented reality.</p>
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li>Cutting-Edge Technologies: Utilized Unity and React3Fiber to create immersive AR environments with hyperrealistic 3D model construction and interactive functionalities.</li>
      <li>University Collaboration: Collaborated with CUHK University in Hong Kong to design user-centered modules, combining React for frontend development and Unity for interactive simulations.</li>
      <li>Enhanced User Satisfaction: Resulted in a significant 15% improvement in user satisfaction through the seamless integration of technology and user-centered design principles.</li>
    </ul>
    <p><strong>Testing and Optimization:</strong></p>
    <ul>
      <li>Conducted comprehensive unit, system, and usability testing to ensure app functionality and optimization.</li>
      <li>Gathered insights through user interviews, refining the user experience to achieve maximum engagement and satisfaction.</li>
    </ul>
  </details>
</div>

## Projects

<div class="experience-card" id="project3">
  <h3>JHU Delineo (demo in descripion)</h3>
  <a href="https://github.com/Delineo-Disease-Modeling" class="external-link" target="_blank">
    <img src="github_icon.png" />
  </a>
  <p class="skills">
    <span>Python</span>
    <span>Unreal Engine 5</span>
    <span>AWS</span>
    <span>React</span>
    <span>Mass Crowd AI</span>
  </p>
  <details>
    <summary><strong>Year:</strong> 08/2023 - current</summary>
    <!-- Your detailed content for Project Name 1 goes here -->
    <p><strong>Overview:</strong> The Delineo Disease Modeling Project aims to revolutionize infectious disease spread modeling by creating a massively parallel, scalable system. Our goal is to assess the impact of non-pharmaceutical interventions (NPIs) and events on disease spread, envisioning populations in highly localized "modules" comprising people, dwellings, and community spaces.</p>
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li>Designed and integrated features in the new algorithm enabling the retrieval of disease information and real-time tracking of disease timelines for newly infected individuals, enhancing the accuracy and reducing the simulation time by 20%.</li>
      <li>Collaborated with AWS to integrate Mass Crowd AI for simulating crowd movement and infection patterns in airports on UE5, enhancing disease spread modeling accuracy.</li>
      <li>Developed the "Intervention Manager" module, allowing users to define and apply interventions within simulations, utilizing Python for backend logic and React for frontend implementation.</li>
    </ul>
    <p>This is a demo of the airport simulation working with AWS.</p>
    <video controls width="300">
      <source src="predefined_path_spawn.mp4" type="video/mp4">
    </video>
  </details>
</div>

<div class="experience-card" id="project4">
  <h3>JHU CBID VectorCam</h3>
  <a href="https://cbidvectorcam.wordpress.com/" class="external-link" target="_blank">
    <img src="ext_link_icon.png" />
  </a>
  <p class="skills">
    <span>Java</span>
    <span>Android Studio</span>
    <span>Firebase</span>
    <span>CV</span>
  </p>
  <details>
    <summary><strong>Year:</strong> 06/2023 - 08/2023</summary>
    <!-- Your detailed content for Project Name 1 goes here -->
    <p><strong>Overview:</strong> A portable, easy-to-use field tool that allows entomologists to accurately speciate different mosquito species to help malaria intervention efforts.</p>
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li>Developed an Android app for vector surveillance, providing vector control in malaria prevention and elimination in sub-Saharan Africa. Leveraged Java and Android Studio to improve mosquito classification accuracy.</li>
      <li>Engineered a robust Firebase-based data transmission system, ensuring secure and efficient transfer of user-generated mosquito data to the cloud, with offline functionality for data integrity in challenging conditions.</li>
      <li>Implemented advanced image processing and computer vision technique (YOLO - you only look once) for rapid mosquito analysis, resulting in a remarkable 40% accuracy improvement.</li>
    </ul>
  </details>
</div>

<div class="experience-card" id="project5">
  <h3>NLP Tagging Project</h3>
  <a href="https://github.com/michellewww/NLP-HW6-Tagging" class="external-link" target="_blank">
    <img src="github_icon.png" />
  </a>
  <p class="skills">
    <span>NLP</span>
    <span>HMM</span>
    <span>CRF</span>
    <span>Python</span>
  </p>
  <details>
    <summary><strong>Year:</strong> 10/2023 - 11/2023</summary>
    <!-- Your detailed content for Project Name 1 goes here -->
    <p><strong>Overview:</strong> Attained over 95% accuracy in tag prediction utilizing taggers based on HMM and CRF, incorporating a biRNN for context feature extraction.</p>
  </details>
</div>


## Awards
<li>Received the Singhal Family Entrepreneurship Award and the 2023 Dean’s Design Award, securing $20,000 in funding for Quest2Learn.</li>
<li>Earned a presentation slot at the 2022 ASCEND conference with my proposal with Nathaniel Gordon, titled "Spacecraft Diagnostic Generation from Remote Sensing for OSAM Mission”.</li>