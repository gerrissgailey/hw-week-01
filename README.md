# Code Refactor

This was a code refactoring project of a webpage for Horiseon Social Solution Services. Code was optimized for better search engine results, restructured to follow the with the flow of the webpage, and consolidated/condensed to eliminate redundancy.

---

## Itemized Breakdown of Changes Made to Code

### HTML Updates...

- Updated title text.

- Changed `<div>` class="header" to `<header>`.

- Changed `<div>` class="content" to `<section>`.

- Moved class="hero" image link from CSS into HTML sheet and added alt tag. Changed from class to id.

- Added id="search-engine-optimization" for the Search Engine Optimization deatils to correct the broken nav link.

- Removed class attributes for Search Engine Optimization, Online Reputation Management, & Social Media Marketing detail areas & changed `<div>` to `<figure>` for this section.

- Changed `<header> <div>` to `<header> <nav>`.

- Changed `<div>` class="benefits" to `<aside>`.

- Changed individual classes of benefit-lead, benefit-brand, & benefit-cost to one class="benefit".

- Added alt tags to each img.

- Changed `<div>` class="footer" to `<footer>`.

- Changed class="seo" to id="seo".



### CSS Updates...

- Updated .header class selectors to header element selectors.

- Updated .content class selector to section element selector.

- Updated .hero class selector to #hero id selector.

- Updated class selectors for Search Engine Optimization, Online Reputation Management, & Social Media Marketing detail areas to a figure element selector. Consolidated separate class selectors for these detail areas under the updated figure element. 

- Updated header div to a nav element selector & header div ul li to a nav ul li selector.

- Removed header selector for list-style-type. Seemed like a redundant function.

- Updated .benefits class selector to aside element selector.

- Changed use of class attributes tied with h3 selector to use only h3 element selector alone. Consolidated from three individual selectors to one under the h3 element selector.

- Updated selectors for the three benefit related classes, consolidating them to one .benefit selector. Did the same for the .benefit img elements as well.

- Changed .footer class selector to footer element selector. 

- Added margin: auto and display: block properties, and removed width: 100% property under #hero id selector to correct image formatting.

---

## Site Preview

![site preview](site_preview.png)