# FEUARTS | Feuture Arts Website

### Final Project — Website Development
**FEU Alabang | Multimedia Arts**

**Group Members:**
- Hanny Grace Araña
- Juliana Claire Lee
- Venice Mae Payna

**GitHub Repository:**  
https://github.com/haarana/FEUARTS

**Published Website:**  
https://haarana.github.io/FEUARTS

---

## 1. Project Overview

FEUARTS is a website developed for Feuture Arts, a student organization at FEU Alabang that focuses on promoting creativity, artistic expression, and collaboration among multimedia arts students.

The website serves as an online platform where students can learn more about the organization, explore artworks created by fellow students, discover past events and workshops, and find opportunities to become part of the creative community.

Our goal was to create a website that represents the identity of FEUARTS while providing an organized, accessible, and visually engaging experience for its visitors.

The website was developed using HTML, CSS, JavaScript, and the Bootstrap framework.

---

## 2. Website Objectives

The main objectives of our website are:

- To introduce FEUARTS and provide information about the organization's purpose, vision, and mission.
- To showcase the artistic talents and creative works of FEU Alabang students.
- To promote events, workshops, exhibitions, and other organization activities.
- To encourage students to participate in creative projects and join the organization.
- To provide accessible contact information and social media links.
- To create a responsive website that works on desktop computers, tablets, and mobile phones.

---

## 3. Website Features and Sections

Our website contains six main sections that visitors can access through the navigation bar.

### Home

The homepage introduces FEUARTS through a welcoming message and the organization's official logo.

It also features selected student artworks and provides navigation buttons that direct visitors to the gallery and events sections.

### About Us

This section provides background information about Feuture Arts.

It includes the organization's overview, vision, mission, and a community photograph.

Its purpose is to help visitors understand what FEUARTS represents and how it supports student artists.

### Events

The Events section showcases past activities, workshops, and other events involving FEUARTS.

Each event includes its corresponding poster and description.

Visitors can also click the event posters to open their original Facebook posts for additional information.

### Art Gallery

The Art Gallery displays artworks created by student artists.

It includes several categories, such as digital art, traditional art, photography, videography, and graphic design.

The gallery also contains interactive features:

- **Category Filters:** Allow visitors to browse artworks based on their category.
- **See More Button:** Displays additional artworks.
- **Artwork Preview:** Allows visitors to view artworks in a larger size.
- **Artwork Submission Form:** Allows visitors to enter their information and select an artwork image.

The submission form collects the student's name, section, year level, course/program, artwork title, artwork category, and image.

**Note:** The artwork submission feature currently functions as a browser-based demonstration. Submitted information is stored locally in the user's browser and is not uploaded to an online database.

### Join FEUARTS

This section encourages students to become part of the FEUARTS community.

It highlights the benefits of joining the organization, including developing artistic skills, meeting fellow artists, and participating in creative activities.

It also includes the organization's committee application posters.

### Contact Us

The Contact section provides ways for visitors to communicate with FEUARTS.

It contains the organization's email address, location, and official social media accounts.

The section also includes a contact form that prepares an email draft using the visitor's email application.

---

## 4. Tools and Technologies Used

The following technologies were used in developing the website.

| Technology | Purpose |
|---|---|
| HTML5 | Used to create the website's structure and content. |
| CSS3 | Used to style the website, including colors, typography, spacing, and layouts. |
| JavaScript | Used to create interactive features such as gallery filters, image previews, and artwork submissions. |
| Bootstrap 5 | Used to support responsive layouts and website components. |
| Google Fonts | Used to improve the website's typography. |
| Visual Studio Code | Used to organize, edit, and test the website files. |
| GitHub | Used to store and manage the website's source code. |
| GitHub Pages | Used to publish the website online. |

---

## 5. Website Design

The website's appearance was based on our approved high-fidelity wireframes.

We followed the existing FEUARTS branding to maintain consistency with the organization's visual identity.

### Color Palette

- **Purple:** Represents creativity and imagination.
- **Orange:** Represents enthusiasm and artistic energy.
- **Pink:** Adds personality and visual interest.
- **White:** Used as the main background to provide a clean and readable layout.

### Typography

The website uses **Outfit** and **DM Sans** from Google Fonts.

These fonts were selected for their modern appearance and readability.

### Layout

We used a single-page scrolling layout to make navigation easier.

Instead of opening different pages, visitors can click the navigation links to move directly to the corresponding sections.

The website also adjusts its layout depending on the user's screen size.

---

## 6. Project Folder Structure

Our website files are organized into separate folders to make the project easier to manage and maintain.

```text
FEUARTS_FinalProject/
│
├── index.html
├── about.html
├── events.html
├── gallery.html
├── join.html
├── contact.html
│
├── css/
│   ├── style.css
│   └── hifi-restore.css
│
├── js/
│   ├── config.js
│   ├── content.js
│   └── main.js
│
├── images/
│   └── Website images and graphics
│
├── vendor/
│   └── bootstrap/
│
├── favicon.ico
├── favicon.png
│
├── README.md
├── START-HERE.txt
└── .nojekyll
```

### Folder and File Descriptions

**index.html**

Contains the main website, including all six sections.

**about.html, events.html, gallery.html, join.html, and contact.html**

These files redirect visitors to their corresponding sections within the main website.

**css/**

Contains the stylesheets responsible for the website's appearance, colors, typography, spacing, and responsive design.

**js/**

Contains JavaScript files responsible for the website's interactive features.

- `config.js` — Stores website settings and social media links.
- `content.js` — Contains artwork and event information.
- `main.js` — Handles interactive features and user actions.

**images/**

Contains the official FEUARTS logo, student artworks, event posters, organization photographs, application posters, and social media icons.

**vendor/bootstrap/**

Contains the Bootstrap files used for the website's responsive layout and components.

**favicon.ico and favicon.png**

Contain the FEUARTS logo used as the website's browser tab icon.

**README.md**

Provides information about the website, its features, technologies, and file organization.

**.nojekyll**

Allows GitHub Pages to publish the website without Jekyll processing.

---

## 7. How to Run the Website

To run the project locally:

1. Download or clone the GitHub repository.
2. Extract the project folder if necessary.
3. Open the folder using Visual Studio Code.
4. Locate `index.html`.
5. Right-click the file and select **Open with Live Server** if the extension is installed.
6. Alternatively, open `index.html` directly in a web browser.
7. Navigate through the website to explore its sections and features.

An internet connection may be needed to load Google Fonts and access external social media links.

---

## 8. Website Development Process

Our website was developed through four major phases.

### Phase 1: Project Proposal

We established the website's purpose, target audience, branding, content requirements, and navigation structure.

This phase helped us organize our ideas before beginning the design and development process.

### Phase 2: Low-Fidelity Wireframes

We created simple wireframes showing the initial arrangement of website elements.

These included desktop, tablet, and mobile layouts.

The wireframes helped us plan the navigation, content placement, and overall structure.

### Phase 3: High-Fidelity Wireframes

We developed more detailed designs that included the FEUARTS color palette, typography, artwork images, and other visual elements.

These served as our main references during website development.

### Phase 4: Website Development

We developed the website using HTML, CSS, JavaScript, and Bootstrap.

During this phase, we also added the actual artworks, event posters, organization images, and interactive features.

Several revisions were made to improve the website's appearance and functionality.

---

## 9. Major Design Revisions

Throughout development, we made several adjustments to improve the website.

Some of the major revisions included:

- Changing the website into a single-page scrolling layout.
- Using white backgrounds while preserving the original FEUARTS gradient colors.
- Improving the alignment and appearance of the FEUARTS logo.
- Removing unnecessary decorative elements.
- Adjusting typography and spacing to improve readability.
- Adding actual student artworks and organization materials.
- Creating category filters and a See More button for the gallery.
- Adding an artwork submission form.
- Making event posters clickable and linking them to their Facebook posts.
- Adding official social media icons and links.
- Adding the FEUARTS favicon.

These revisions helped us develop a website that remained consistent with our high-fidelity design while improving the overall user experience.

---

## 10. Current Limitations

Although the website includes several interactive features, some functions are currently designed for demonstration purposes.

**Artwork Submission**

The form stores uploaded artwork information locally in the visitor's browser. A shared online database or backend would be needed to receive submissions from different users.

**Contact Form**

The contact form prepares an email draft rather than directly sending messages through the website.

**Membership Application**

The website displays FEUARTS committee application materials. Membership applications are handled through the organization's designated channels.

These features can be expanded in future website development.

---

## 11. Resources and Credits

### Website Development and Design

**Project Group:**
- Hanny Grace Araña
- Juliana Claire Lee
- Venice Payna

### Student Artworks

The initial digital art gallery features artworks by **Hanny Grace Araña**:

- Self Portrait
- Zenko
- Reach
- Star Girl
- Birthday
- Gu Yuecheng

### Organization Materials

The following materials were provided for the website:

- Official FEUARTS logo
- FEUARTS community photograph
- Event posters and photographs
- Committee application materials
- Official social media icons

The organization materials remain credited to FEUARTS and their respective creators.

### Frameworks and Resources

- Bootstrap 5 — https://getbootstrap.com/
- Google Fonts — https://fonts.google.com/
- GitHub — https://github.com/
- GitHub Pages — https://pages.github.com/

---

## 12. Conclusion

Developing the FEUARTS website allowed our group to apply what we learned about website planning, UI/UX design, and web development.

From creating the initial proposal and wireframes to developing and revising the website, we learned the importance of balancing creativity with functionality.

We also gained experience organizing website files, creating responsive layouts, adding interactive features, and preparing a website for online publishing.

Overall, our goal was to create a website that represents FEUARTS as a creative and welcoming community for student artists.

The project also serves as a foundation for possible improvements and additional features in the future.
