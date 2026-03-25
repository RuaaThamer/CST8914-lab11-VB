## Q1: What keyboard function can you improve to increase usability?

The accordion can be improved by adding optional navigation keys recommended by the WAI‑ARIA accordion pattern, including Arrow Up, Arrow Down, Home, and End. These keys are not required for basic accessibility but significantly improve usability by allowing faster and more intuitive navigation between accordion headers.

---

## Q2: What ARIA attributes were missing?

- aria-expanded on each accordion header button  
- aria-controls to link each button to its corresponding content panel     
- aria-labelledby on each panel to associate it with its controlling button   
