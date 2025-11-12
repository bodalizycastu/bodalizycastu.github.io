## Javier & Elizabeth Wedding Website

This project is an HTML template adapted for a wedding website. It is based on the Neela one-page/multi-page theme and customized to present event details, invitations, maps, and RSVP options.

### Tech stack
- HTML5, CSS (Bootstrap 5), JavaScript (jQuery)
- UI libraries: Owl Carousel, Lightbox, Waypoints, NiceScroll, ZoomSlider
- Google Maps (with styled markers)

### Structure (key files)
- `index.html`: One-page layout with hero, invitation, location map, and sections
- `index-multipage.html`: Multi-page landing with links to inner pages
- `rsvp.html`: Dedicated RSVP page
- `js/variables.js`: Site configuration (slideshow, map, labels)
- `js/scripts.js`: UI behaviors and form handling
- `contact.php`: Email handler for contact/RSVP forms (optional if using Google Forms)

### First review requirements (to implement in the site)
- Remove the navigation bar.
- Simplify hero/about: use a single photo and remove extra text and animations.
- Remove the timeline; jump directly to the invitation with the headline “Our love story begins!”.
- Optionally show two locations on the same Google Map.
- Replace the Bridesmaids and Groomsmen sections with an Itinerary (timeline-style schedule).
- Add a Dress Code section. codigo de vestimenta... imagen texto
- Add a Hotels (accommodations) section. 
- Replace the built-in RSVP form with Google Forms.
- Add a gift registry link and bank account details.
- Remove the Gallery section.
- Remove the Wedding Blog section.
- “Will you Attend?”: embed a Google Form that collects name, number of guests, and attendance confirmation. Provide two versions (for 1-pass and 2-pass invitations).
- Attendance options should allow 0, 1, or 2 guests (confirm 0/1/2).
- Update/add the event logo.


Crea abajo de la seccion de itinerario una nueva sección que maneje los siguientes parametros
Titulo: Codigo de Vestimenta
Imagen: images/suits.png
Texto: Formal - All Black <br>
Texto: Mujeres Vestido negro <br>
Texto:Hombres Traje negro

Todo ello ocupando el mismo diseño que maneja la plantilla es decir tipografia colores etc

nombre del hotel y boton

### Notes
- If using Google Forms for RSVP, disable or remove the built-in AJAX form (`contact.php`) and embed the Forms instead.
- Replace Google Maps API key in HTML pages with your key; update markers in `js/variables.js`.
- Swap logo assets in `images/` and update references where needed.


