<!-- My Advanced Blog -->

This is a responsive blog website built using HTML, CSS, and Bootstrap. It includes several articles, a sidebar with useful links, a footer with a contact form, and a "Back to Top" button that becomes visible on scroll.

<!-- Features -->

    Responsive Navbar: A collapsible navigation bar with links.
    Responsive Layout: A multi-column layout for articles and a sidebar using Bootstrap's grid system.
    Articles: Sample articles with hover effects for interactivity.
    Sidebar: Includes "About the Blog" and "Useful Links" sections.
    Footer: A footer with a contact form and social media links.
    Back to Top Button: A button appears on scrolling down and brings the user back to the top of the page.

<!-- Technologies Used -->

    HTML5: For structuring the webpage  "semantic elements"  .
    CSS: For styling the components.
    Bootstrap 5: For the responsive grid system and UI components like the navbar, buttons, etc.
    JavaScript: For adding the "Back to Top" button functionality.


<!-- Project Structure -->
 index.html        # Main HTML file
 styles.css        # External CSS file for custom styles
 README.md         # Project documentation (this file)


<!-- Back to Top Button -->

This button is hidden by default but appears when the user scrolls down the page. Clicking it brings the user back to the top.

<!-- JavaScript Code for "Back to Top" Button: -->

<!-- javascript -->

const backToTopBtn = document.getElementById("backToTopBtn");
window.onscroll = function () {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    backToTopBtn.style.display = "block";
  } else {
    backToTopBtn.style.display = "none";
  }
};
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}


