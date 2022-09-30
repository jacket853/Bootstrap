# Bootstrap

Required elements
  1. Grid design: three different grids with the same elements (e.g. col-2, col-sm-12, col-md-6, col-lg-6, etc.)
  2. Navbar: I did a horizontal tab-pill design that incorporated a dropdown menu

5 flexible elements (included in BS5 tutorial)
  1. Spinners: I used both spinner-grow and spinner-border types in a button
  2. Badges: In this same button, I put a badge that would hold the "spinner-grow" element, contributing to visual appeal (or the lack thereof)
  3. Carousel: I put this in the "toast" popup that came from the spinner button on the home page, essentially a toggleable slideshow of pictures
  4. Progress Bars: I used animated and striped progress bars not as tools for the user, but more of a visual design choice (the color scheme could be improved upon, but hey, this is an introductory project anyway)
  5. Utilities: Specifically, I used the video aspect ratio, which functioned similarly to "img-fluid" but had a set ratio of dimensions, making the video's scale consistent on any screen. Also, I used the "shadow-lg" attribute from utilities to make the iframe pop out a bit more.

2 "more open" elements (that not included in topics list)
  1. tab-pane fade with tabcontent nav-pill: getting "nav-item dropdown"/"nav-link dropdown-toggle" and its resulting "menu" to work in conjunction with the structure of the <li> "nav-item" in the unorded list was a giant pain (see notes)
  2. "toast" with JS onclick event of spinner/badge button on home page
  
Notes: I attempted to use a dropdown with the nav pills, but the hide/show, hidden/shown events did not work with the dropdown. I talked with Dr. J about it, and it seems that BS5 recognizes the first element in the dropdown and hides it, but  the next elements are seen as tabs too, yet inside another element restricting how the content is removed after switiching tabs (which may result in adding it to another tab's content).
