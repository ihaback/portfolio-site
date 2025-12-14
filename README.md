# IHS Portfolio Frontend

This project is a simple portfolio website created as a school assignment. It aims to demonstrate basic skills in HTML, CSS with a focus on clear structure, accessibility, and good web practices. The site uses semantic HTML elements, ARIA labels, and visually hidden text to help make the content more accessible.

CSS is mostly organized with BEM naming conventions and custom properties (variables) for colors, spacing, and fonts, which helps keep the design flexible and easy to maintain.

SVG icons are used throughout the site for navigation (header and footer), social media links, favicon, technology section, portfolio link indicators, and dynamic weather display, providing clear graphics and better performance. Responsive design is included with media queries, and utility classes help with layout and accessibility.

The codebase is intended to be modular, readable, and easy to update or extend, but there is always room for improvement.

## Project Structure

```
index.html
assets/
	fonts/
		(custom web fonts)
	icons/
		favicon.svg
	images/
		(Image of me and testimonal section images)
	pdf/
		cv.pdf
	styles/
		style.css
```

### index.html

- The main HTML file for the portfolio site.
- Navigation and content sections are organized for easy reading and maintenance.

### assets/styles/style.css

- Contains all styles for the site.
- Responsive design for mobile and desktop layouts.
- Utility classes (e.g., `.text-center`, `.visually-hidden`) help with layout and accessibility.

### assets/

- `fonts/`: Custom web fonts used in the site.
- `icons/`: Contains favicon.svg. Other icons (header, footer, social media, technology section, portfolio links, weather) are inline SVG symbols in the HTML.
- `images/`: Any images used in the portfolio.
- `pdf/`: Contains downloadable files, such as a CV.

## Key Features

- **Semantic HTML**: Easy to read and maintain.
- **Accessible**: ARIA labels, visually hidden text, and good color contrast for screen readers and users with disabilities.
- **Responsive**: Works well on both mobile and desktop devices.
- **Modular CSS**: BEM methodology and CSS variables for easy updates and scalability.
- **SVG Icons**: Used throughout the site (navigation, social media, favicon, technology section, portfolio links, and weather), providing clear graphics and better performance.

## About Section

This is the first section visitors see when they open the site. It includes:

- A heading with my name.
- A short paragraph about my skills.
- Two buttons: one downloads my CV, the other goes to the contact form.
- A photo of me with a description for screen readers.
- Special labels and tags that help screen readers understand the page.
- The layout changes on mobile phones so content shows in the best order.

## Portfolio Section

This section shows my completed projects. It includes:

- Six project cards that link to GitHub.
- Each card has a title and short description.
- Hidden text tells screen readers the links open in new tabs.
- Links are secure and have clear descriptions for screen readers.
- The grid adjusts automatically to fit different screen sizes.

## Technologies Section

This section shows the tools and technologies I use. It includes:

- Ten icons for different technologies (C#, TypeScript, CSS, Node.js, NPM, Azure, AWS, Ubuntu, GitHub, Storybook).
- Each icon has hidden text that screen readers can read.
- The icons are organized in a list with clear labels.
- The spacing between icons adjusts to fit different screen sizes.

## Testimonials Section

This section shows what clients and colleagues say about me. It includes:

- Four cards with feedback from different people.
- Each card has a photo, name, job title, and their comment.
- Photos have descriptions so screen readers can explain who the person is.
- Hidden text tells screen readers when quotes start.
- Cards stack vertically on smaller screens.

## Contact Section

This section has a form for people to contact me. It includes:

- Five fields: first name, last name, email, phone, and message.
- The form checks that information is entered correctly before sending.
- Names must be 2-50 characters with letters (including å, ä, ö) and spaces. Email must be valid. Phone allows optional + prefix followed by numbers. Message must be at least 10 characters.
- Each field has a clear label and helpful placeholder text.
- The message box takes up the full width.
- The browser shows error messages if something is wrong and won't send the form until everything is correct.
