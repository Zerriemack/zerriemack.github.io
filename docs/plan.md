# Project Plan

## Project overview
This plan covers the build and submission of my Professional Project Hub Site. The site is hosted on GitHub Pages and is designed to organize my work in one place. The hub includes clear navigation to Home, Projects, Sources, Notes, and Contact. The Projects page includes a locked list of projects with working links, including Milly Maker Tracker at https://millymakertracker.com/.

## Risk analysis using the TAME framework

### Risk 1: Broken internal navigation between pages
Threat: A visitor cannot move between Home, Projects, Sources, Notes, and Contact because a link is incorrect, a file name mismatch exists, or a relative path is wrong.

Avoid: Keep file naming consistent and simple. Build the page structure first and confirm navigation before styling.

Mitigate: Run a manual click test for every navigation link on every page in a local preview and again on the live GitHub Pages site. Confirm a visitor can reach any page within two clicks from any location.

Escalate: If an issue appears close to the deadline, remove any non essential navigation items temporarily and submit a stable version that preserves the required pages and the required docs. Follow up with a fix commit immediately after submission if needed.

### Risk 2: Broken external links to locked projects
Threat: A visitor clicks a project card and hits a 404, a redirect loop, or a dead external page. This includes Milly Maker Tracker, Milly Map Sources, CMPA Notes, and the TeamWork Online business card.

Avoid: Use the exact canonical URLs from my scope statement and keep them consistent across the Projects page and README.

Mitigate: Perform a final link check on the live site for each locked project link:
1. https://zerriemack.github.io/milly-map-sources/
2. https://millymakertracker.com/
3. https://zerriemack.github.io/CMPA-Notes/
4. https://zerriemack.github.io/
5. https://www.teamworkonline.com/business_cards/06d554866f6521c2

Escalate: If one external destination is down on submission day, keep the link but confirm the URL is correct and add a short note on the Projects page. If the URL itself is wrong, correct it and push a fix immediately.

### Risk 3: GitHub Pages deployment or publishing delay
Threat: The repository pushes successfully but the live site does not update, the Pages setting points to the wrong branch, or the root file structure prevents the site from loading correctly.

Avoid: Keep required files in the root directory and use simple relative paths for navigation and the CSS file.

Mitigate: After each major update, check the live URL and confirm the site loads correctly. Hard refresh and test in a mobile sized window.

Escalate: If GitHub Pages fails close to the deadline, isolate the problem by pushing only the required root website files and the docs folder, then re check Pages settings and re test.

### Risk 4: Scope creep and time pressure
Threat: Time gets pulled into extra pages or features and I lose time needed for the required documentation and link testing.

Avoid: Finish docs first, then complete the core pages, then style last.

Mitigate: Use a short checklist for minimum requirements and stop adding features once the acceptance criteria are met.

Escalate: If time becomes tight, freeze enhancements and submit a stable version with complete docs and working navigation.

### Risk 5: Inconsistent visual design across pages
Threat: Spacing, typography, and layout vary between pages, making the site feel unfinished.

Avoid: Use one stylesheet and reuse the same header and navigation markup across pages.

Mitigate: Do a quick cross page review on desktop and mobile size views and adjust CSS to keep spacing and typography consistent.

Escalate: If consistency is still off, simplify styling and prioritize readability and alignment across pages.

## Work breakdown structure and simple task schedule

### WBS 1.0 Repository and structure
Task 1.1: Confirm single public repository structure for Project 03  
Owner: Zerrie Mack  
Duration: 30 minutes  
Output: Repo has root website files and a docs folder.

Task 1.2: Confirm GitHub Pages publishing settings  
Owner: Zerrie Mack  
Duration: 20 minutes  
Output: Live site loads at https://zerriemack.github.io/.

### WBS 2.0 Documentation
Task 2.1: Finalize docs/scope.md  
Owner: Zerrie Mack  
Duration: 60 minutes  
Output: Scope statement aligned to deliverables and acceptance criteria.

Task 2.2: Write docs/plan.md with TAME and WBS  
Owner: Zerrie Mack  
Duration: 60 minutes  
Output: Plan includes risks and schedule aligned to scope.

Task 2.3: Write docs/retrospective.md  
Owner: Zerrie Mack  
Duration: 45 minutes  
Output: Reflection covers what went well, what went wrong, and what I would change.

### WBS 3.0 Website build and content
Task 3.1: Confirm navigation across pages  
Owner: Zerrie Mack  
Duration: 45 minutes  
Output: Navigation links appear on every page and work correctly.

Task 3.2: Update Projects content with locked project links  
Owner: Zerrie Mack  
Duration: 45 minutes  
Output: Projects section includes Milly Maker Tracker and the other locked projects with short descriptions and working links.

Task 3.3: Update Sources and Notes content  
Owner: Zerrie Mack  
Duration: 45 minutes  
Output: Sources and Notes pages link to Milly Map Sources and CMPA Notes and explain how to navigate them.

Task 3.4: Confirm Contact section and resume link  
Owner: Zerrie Mack  
Duration: 30 minutes  
Output: Contact section has at least one clear professional contact path and resume link works.

### WBS 4.0 Styling
Task 4.1: Apply consistent styling across pages  
Owner: Zerrie Mack  
Duration: 45 minutes  
Output: style.css applies consistent typography, spacing, and layout.

### WBS 5.0 Testing and submission
Task 5.1: Internal navigation test  
Owner: Zerrie Mack  
Duration: 20 minutes  
Output: All internal links work across the site.

Task 5.2: External link validation on the live site  
Owner: Zerrie Mack  
Duration: 20 minutes  
Output: All locked project links work, including https://millymakertracker.com/.

Task 5.3: README final update  
Owner: Zerrie Mack  
Duration: 20 minutes  
Output: README links to the live site and the docs folder and lists key project links.

Task 5.4: Final commit, push, and live verification  
Owner: Zerrie Mack  
Duration: 20 minutes  
Output: Repo is ready to submit as one link and the live site reflects the final version.
