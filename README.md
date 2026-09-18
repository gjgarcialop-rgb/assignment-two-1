# Academic Connections

## Project Description

Academic Connections is a small campus-events website designed to help college students discover activities, organizations, and opportunities to connect with other students. The site gives students one place to find upcoming events, learn about a featured event, and see what to expect before attending.

The intended audience is new and returning college students who want to become more involved on campus. The site is especially useful for students looking for social events, student organizations, work-study information, volunteer opportunities, and ways to meet people.

## Layout Description

The website has two pages:

- index.html is the home page. It includes the site introduction, a welcome section, a grid of upcoming event cards, and an About Us section.
- event.html is the featured-event page. It includes an introduction with an image, event details, a schedule, accessibility information, an event-information sidebar, and related events.

Both pages use a header with the site title and navigation links. The main content is centered and limited to a maximum width so that it remains readable on larger screens. A footer provides another set of navigation links and contact information.

### Flexbox and Grid

Flexbox is used for the navigation, hero section, and related events. it arranges items, controls spacing, and allows content to wrap on smaller screens.

Grid is used for the upcoming event cards and featured-event main content/sidebar. Grid keeps everythig organized and changes to fewer columns on smaller screens.

## Responsive Design

The pages use two responsive breakpoints:

- **Above 850px:** This gave the desktop layout with horizontal hero sections, three event columns and a two column event page.

- **850px and below:** The hero sections stack vertically, the home-page event cards change to two columns, and the featured-event layout changes to one column. This gives the main content more room on tablets and smaller laptop screens.

- **500px and below:** Mainly for navigation and event cards stack vertically for easier viewing

The pages were tested by resizing the browser with my desktop to check the layout, navigation, images, and the responsiveness from the website.

## Semantic HTML

The pages use semantic HTML elements to make the structure clearer and improve accessibility:

1. **header** identifies the introductory area of each page, including the site title and primary navigation.
2. **nav** identifies the groups of navigation links so users and assistive technologies can recognize how to move around the site.
3. **main** identifies the primary content of each page and separates it from the repeated header and footer content.
4. **article** identifies each individual event and related-event item because each one is a self-contained piece of information that can stand on its own.



## Sources and Credits

### Images and image ideas

- Welcome image/sign: [Vecteezy Welcome Back Sign](https://www.vecteezy.com/free-vector/welcome-back-sign)

- Fall festival image/idea: [Liberty County Fall Festival Calendar](https://libertycounty.org/calendar/tag/fall-festival/list/?tribe-bar-date=2025-02-13&eventDisplay=past)

- Work-study image/idea: [College Finance Work-Study Guide](https://collegefinance.com/work-study/work-study-explained-how-it-works-a-simple-guide)

- Greek-life image/idea: [Sporcle Greek Life Article](https://www.sporcle.com/blog/2019/08/why-are-college-fraternities-and-sororities-called-greek-life/)

- Volunteer image/idea: [CFC H&P Kids Volunteer Campaign](https://cfchpkids.org/campaign/volunteer-with-us/)

- Club-fair image/idea: [The New and Improved Club Fair](https://www.whsforum.com/campus-and-clubs/2020/12/10/the-new-and-improved-club-fair/)

- Event-page layout and event inspiration: [Haddon Events](https://shophaddon.com/haddon-events/)

The image files used locally are stored in the images/ folder. The image files are referenced in the HTML with descriptive alternative text.

### Font

The site uses the system font stack Arial, sans-serif in style.css. No external font was imported.

### Borrowed content

The event topics and general ideas for Greek life, work-study, fall festivals, volunteering, and club fairs were informed by the sources listed above. The page layout, event dates, locations, descriptions, schedule, accessibility information, and navigation copy were written for this project.