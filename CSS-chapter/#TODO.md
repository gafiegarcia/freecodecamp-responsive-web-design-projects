# TODOs

## styles-template.css
- [x] Finish creating styles-template.css
- [x] Add prefers-reduced-motion @media query and an appropriate section for it in CSS file structure

## Personal Portfolio page
- [x] Optimize image assets by converting them pngs to webp
- [x] Add text ::selection color
- [ ] Unify margin-block-start for all section containers if I decide to use the same value for all of them
- [ ] Time to start trying out theme toggle button implementation!
  - [ ] Find Toggle theme icons online and add proper hover animation
- [ ] INTRO animation (aria-hidden="true"):
    - Welcome...
    - You weren't supposed to find this... <br> but,
- [ ] Create README.md; assume the project is live on github pages when writing it
- [ ] Remove .radio-btn component if it's not used
- [x] Experiment with using Jekyll build by changing the names of some project screenshots to exclude "_" at the start. Take note of whether the image load speed improve.
- [x] IMPORTANT: add .project-title class and have it replace .project-tile > h4 selector as the projects within All Projects might use h5 for the project title because of HTML and CSS sub-sub-section potentially (have to) use h4 to keep the semantic hierarchy clean.
  - [x] set color: --light
- [x] Add extra padding for .nav-link when min-width: ~400px
- [x] Add :target styling for the sections: text-decoration: underline; text-decoration-color: 