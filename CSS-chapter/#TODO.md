# TODOs

## styles-template.css

### Done
- [x] Finish creating styles-template.css
- [x] Add prefers-reduced-motion @media query and an appropriate section for it in CSS file structure
- [ ] SEO Practice!

## Personal Portfolio page

### Misc
- [x] add webkit properties for Safari compatibility
- [x] update README and HTML content with info about this project finishing (went {too} far beyond what I was taught) and how proud I am with this last curriculum project

### v1.0--progressive-enhancement-draft
- [x] try out deleting 100dvh lines and let 100vh lines be on #welcome-section and #contact-section for consistent scrolling experience on mobile without layout jitters when the browser menu bar shows and hides
- [x] optimize up to 1024px
- [x] (optional) create new layout >1024px to make use of the full viewport width
- [x] Create README.md; assume the project is live on github pages when writing it

### (planned) v1.1 with nice to have features(animation and theme toggle)
- [ ] Time to start trying out theme toggle button implementation!
  - [ ] Find Toggle theme icons online and add proper hover animation
- [ ] INTRO animation (aria-hidden="true"):
    - Welcome...
    - You weren't supposed to find this... <br> but,

### Archive
- [x] Move ::selection rule to BASE as it is a base styling, not section-specific
- [x] Unify margin-block-start for all section containers if I decide to use the same value for all of them
- [x] Remove .radio-btn component if it's not used
- [x] Optimize image assets by converting them pngs to webp
- [x] Add text ::selection color
- [x] Experiment with using Jekyll build by changing the names of some project screenshots to exclude "_" at the start. Take note of whether the image load speed improve.
- [x] IMPORTANT: add .project-title class and have it replace .project-tile > h4 selector as the projects within All Projects might use h5 for the project title because of HTML and CSS sub-sub-section potentially (have to) use h4 to keep the semantic hierarchy clean.
  - [x] set color: --light
- [x] Add extra padding for .nav-link when min-width: ~400px
- [x] Add :target styling for the sections: text-decoration: underline; text-decoration-color: 