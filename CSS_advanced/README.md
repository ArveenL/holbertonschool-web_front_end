1.When scrolling is triggered on the html element itself, we'd like the behavior of the scroll to be as fluid as possible.

html {
  scroll-behavior: smooth;
}

2. Do you know your color values?
Based on styles/1-style.css, create the following declarations:

For the body, set the foreground color value to #161616
For all anchor elements, set the foreground color value to #161616
All elements with the class visually-hidden should have their display to none
All elements with the class card-category, should have their foreground color set to #D73953
All elements with the class section-tagline should have their foreground color set to #D73953

/* Body foreground color */
body {
  color: #161616;
}

/* All anchor elements foreground color */
a {
  color: #161616;
}

/* Hide elements visually hidden */
.visually-hidden {
  display: none;
}

/* Card category color */
.card-category {
  color: #D73953;
}

/* Section tagline color */
.section-tagline {
  color: #D73953;
}