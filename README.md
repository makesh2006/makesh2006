        <li>Public Relations</li>
        <li>Teamwork</li>
        <li>Time Management</li>
        <li>Leadership</li>
      </ul>
    </div>
    
    
  <section id="projects">
    <div class="section-content">
      <h2>Projects</h2>
      <ul>
        <li><a href="weather server.html">Weather Report</a></li>
        <li><a href="#">Cloud Security IBM</a></li>
        <li><a href="#">Ai Chatbot</a></li>
        <li><a href="Contact.html">Contact Request</a>
          </section>
          <section id="resume">

    

        <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="file.pdf" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2025 </p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^=""]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
