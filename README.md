# xss-labs

A comprehensive collection of hands-on Cross-Site Scripting (XSS) labs for security enthusiasts, developers, and penetration testers.

!(https://github.com/yogsec/xss-labs/blob/main/Screenshot%20From%202026-05-24%2014-07-52.png?raw=true)
---

## Overview

xss-labs is a frontend-only training that demonstrates various XSS vulnerabilities in a safe, controlled environment. Each lab focuses on a specific XSS vector, allowing you to understand how these attacks work and how to prevent them.

All labs run entirely in your browser. No backend server is required.

---

## Live Demo

The labs are hosted online via GitHub Pages. Access all 39 labs at:

   https://yogsec.github.io/xss-labs/

---

## Lab Categories

### Reflected XSS (Client-Side Simulation)

- GET parameter reflection
- POST parameter with sessionStorage
- URL hash reflection
- Referer header mock
- User-Agent reflection

### Stored XSS (Frontend Storage)

- Cookie value reflection
- document.title injection
- window.name reflection
- localStorage key reflection
- sessionStorage value reflection
- localStorage stored and displayed later
- sessionStorage shown on reload
- IndexedDB read and render
- Cookie injection XSS
- window.name cross-page navigation
- history.state with pushState
- sessionStorage with search filter
- localStorage as JSON parsed and injected
- Base64 decode and inject
- Multi-key local storage

### DOM-Based XSS

- document.write with location.search
- innerHTML with unsanitized input
- insertAdjacentHTML injection
- outerHTML replacement
- eval() of user-controlled string
- setTimeout with user string
- setInterval injection
- Function() constructor
- javascript: pseudo-protocol in location.href
- Dynamic script src injection

### Event Handler XSS

- onclick injection
- onmouseover XSS
- img onerror trigger
- body onload payload
- onfocus autofocus
- oninput injection
- onchange select XSS
- onkeyup injection
- onsubmit form hijack

---

## How to Use

1. Visit https://yogsec.github.io/xss-labs/
2. Browse the lab index page to see all available labs
3. Click on any lab to open it
4. Each lab contains:
   - A description of the vulnerability
   - An interactive vulnerable component
   - A solution button that reveals the answer
5. Experiment with different payloads to understand the attack vectors

---

## Lab Structure

Each lab file follows a consistent pattern:

- Vulnerable code demonstration
- Interactive input area
- Real-time output reflection
- Collapsible hints section
- Solution panel with explanation and fix

---

## Educational Purpose

These labs are designed for:

- Security professionals learning XSS detection
- Developers understanding secure coding practices
- Students studying web application security
- Penetration testers practicing exploit techniques

All labs run locally in your browser. No malicious code is transmitted externally.

---

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap 5

---

## Author

Created and maintained by Abhinav Singwal (yogsec)

- GitHub: github.com/yogsec
- Linktree: linktr.ee/abhinavsingwal

---

## License

Educational use only. Use responsibly.
