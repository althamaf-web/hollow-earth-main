# Hollow Earth

This repository contains the starter files for a Web Design 1 coding exercise about building a small multi-page website with HTML.

In this exercise, you will create a fictional website about the Hollow Earth theory. The topic is intentionally strange and playful, but the coding concepts are important. You will practice turning several plain content files into connected HTML pages that work together as a small website.

You've already practiced basic HTML structure, headings, paragraphs, lists, images, and links. In this project, you'll use those same skills again while adding several new ideas, including sections, class names, embedded maps, image editing, and site navigation.

The goal is still not to create an attractive visual design. These pages will look plain because we are still focused mostly on HTML structure. Soon we'll learn CSS, which will allow us to control colors, fonts, spacing, layout, and visual design.

---

## Use Canvas for the Full Assignment Instructions

Canvas has the full assignment description, screencast videos, due date, and submission instructions.

This GitHub repository is just where the starter files are stored.

For this exercise, follow the instructions in Canvas and watch the screencast videos in order. This README is here to help you understand what is in the folder and remind you what to check before submitting.

---

## What You Will Practice

By completing this exercise, you will practice how to:

- Download starter files from a GitHub repository
- Unzip a project folder
- Keep your course files organized in a class folder
- Open a full project folder in Visual Studio Code
- Use the Emmet `!` shortcut to create basic HTML page structure
- Add meaningful page titles
- Move starter content inside the `body` element
- Use `h1`, `h2`, and `h3` headings based on page structure
- Use paragraphs and lists
- Use the `section` element to group related content
- Use `class` attributes to identify different sections
- Use the `strong` element for important text
- Use the `abbr` element with a `title` attribute
- Create hyperlinks with the `a` element
- Use the `href` attribute
- Create links with readable clickable text instead of showing long URLs
- Add images with the `img` element
- Use `src` and `alt` attributes
- Crop and resize images using built-in computer tools
- Embed a Google Map using an `iframe`
- Create navigation with the `nav` element
- Build a consistent navigation menu across multiple pages
- Link multiple HTML pages together into a small website
- Preview and test your pages in a browser
- Zip and submit a complete project folder in Canvas


---

## Recommended Folder Organization

Before you start coding, put the unzipped project folder somewhere organized.

A good setup would be to have one main folder for this course, then place each coding exercise inside it.

Example:

- `web-design-1`
  - `handsome`
  - `learning-html`
  - `hollow-earth`

This will make your life much easier as the course continues. You'll be downloading lots of files and folders throughout the semester, and it's easy to lose track of them if everything is scattered across your Desktop or Downloads folder.

After you unzip the starter files, you should delete the original ZIP file so you do not confuse it with the completed ZIP file you will submit later.

---

## Important: Open the Folder, Not Just One File

When working in Visual Studio Code, open the entire project folder.

Do not open only one HTML file by itself.

Opening the folder allows VS Code to see all of the files that belong to the project. This is important when you are working with images, links, and file paths.

---

## Page 1: index.html

The `index.html` file is the homepage of the website.

In this file, you will practice:

- Using the Emmet `!` shortcut to create the required HTML structure
- Adding a useful page title
- Moving starter content inside the `body` element
- Adding an `h1` for the main page heading
- Using `h2` headings for major sections
- Using `p` elements for paragraphs
- Adding links to related resources or pages
- Adding an image
- Previewing the page in a browser

This is also the first exercise where the file name `index.html` becomes especially important.

A website’s homepage is usually named `index.html` because web servers commonly look for that file first when loading a folder or website.

---

## Page 2: monument.html

The `monument.html` file is a page about the Hollow Earth monument in Hamilton, Ohio.

In this file, you will practice:

- Creating the basic HTML document structure
- Adding a page title
- Moving the closing `body` and `html` tags to the correct location
- Adding an `h1`
- Using headings and paragraphs
- Using the `strong` element to emphasize important content
- Embedding a Google Map using an `iframe`
- Adding images to support the page content

This page also introduces the idea that a website can have a homepage and supporting subpages.

---

## Image Editing

Part of this exercise asks you to crop and resize images before adding them to the page.

You don't need Photoshop for this. You can use built-in tools on your computer:

- On Windows, you can use the Photos app
- On a Mac, you can use Preview

When editing images, think about what the viewer actually needs to see. Cropping can remove distracting parts of an image, and resizing can help an image fit better on a page.

Don't delete the original image files unless the assignment specifically tells you to. It is usually safer to save edited versions with clear file names.

---

## Page 3: truth.html

The `truth.html` file is the “hidden truth” page of the site.

In this file, you will practice:

- Creating the basic HTML document structure
- Adding a page title
- Adding an `h1`
- Dividing content into multiple `section` elements
- Adding `class` attributes to sections
- Using class names such as `history`, `links`, or `faq`
- Creating unordered lists
- Using multiple cursors or other editing shortcuts
- Using the `abbr` element with a `title` attribute
- Creating links with readable text
- Using `h2` headings for sections
- Using `h3` headings for questions inside an FAQ section
- Adding images to support the page content

The `section` element is used to group related content together.

The `class` attribute gives an element a name or category. Class names will become especially important when we start using CSS because they allow us to style specific parts of a page.

For now, adding a class may not visibly change anything in the browser. That is normal. You are setting up structure that will be useful later.

---

## Links and Readable Link Text

In this exercise, you will create links using the `a` element and the `href` attribute.

The `href` attribute tells the browser where the link goes.

The text between the opening and closing `a` tags is what the user sees and clicks.

For example, it is usually better to show readable link text like:

- `Atlas Obscura`
- `Hollow Earth Insider`
- `Ancient Aliens Video`

instead of showing a long URL directly on the page.

Readable link text is easier to scan, easier to understand, and more professional.

---

## Navigation

Near the end of the exercise, you will add navigation to the site.

Navigation is the set of links that lets visitors move between pages.

In this project, you will create navigation that connects:

- the homepage: `index.html`
- the monument page: `monument.html`
- the hidden truth page: `truth.html`

You will use the `nav` element to identify the navigation area.

Inside the `nav`, you will use a list of links.

The same navigation should appear on all three pages. Keeping the navigation consistent helps visitors understand where they are and how to move around the site.

Even if the current page links to itself, that is okay. Consistent navigation is usually better than changing the menu from page to page.

---

## Important Concepts to Remember

### HTML is about structure and meaning

HTML tells the browser what each piece of content is.

A heading means “this is a heading.”

A paragraph means “this is a paragraph.”

A section means “this group of content belongs together.”

A navigation area means “these links help users move through the site.”

A link means “this content can be clicked to go somewhere.”

An image means “display this image file here.”

### Attributes add extra information

Some elements need extra information to work correctly.

For example:

- `img` uses `src` to locate an image file
- `img` should include `alt` to describe the image
- `a` uses `href` to identify the link destination
- `abbr` can use `title` to explain the abbreviation
- `section` can use `class` to identify what kind of section it is
- `iframe` uses attributes to control embedded content

Attributes go inside the opening tag.

### File names and folders matter

Web pages depend on exact file names and folder paths.

The browser does not understand what you meant. It only follows exactly what you typed.

For example, these are not the same to a browser:

- `truth.html`
- `Truth.html`
- `truth.htm`
- `truth.html.txt`

These are also not the same:

- `images/monument.jpg`
- `image/monument.jpg`
- `images/Monument.jpg`
- `monument.jpg`

Small differences matter.

---

## Before You Submit

Before submitting your work in Canvas, check the following:

- Your project folder is unzipped
- Your project folder is saved somewhere you can find it
- You opened the full project folder in Visual Studio Code
- You saved all of your HTML files
- Your homepage is named `index.html`
- Your supporting pages are named `monument.html` and `truth.html`
- Each HTML file has the basic HTML document structure
- Each page has a useful `title`
- All visible page content is inside the `body` element
- Each page has one main `h1`
- Section headings use appropriate heading elements
- Paragraphs are marked up with `p` elements
- Lists use `ul` or `ol` with `li` elements inside
- The `truth.html` page uses `section` elements
- Section elements on `truth.html` include useful class names
- Images display correctly in the browser
- Images include useful `alt` text
- The embedded map appears on the monument page
- Links are clickable and go to the correct locations
- The navigation menu appears on all three pages
- The navigation links work on all three pages
- File and folder names are spelled correctly
- You zipped the entire project folder, not just one HTML file

---

## What to Submit

When you are finished, compress the entire project folder into a ZIP file and submit that ZIP file in Canvas.

Do not submit only one HTML file.

Your completed website depends on multiple files working together. If you only submit one file, images or links may not work when the project is opened on another computer.

---

## Troubleshooting Tips

If something is not working, check these common issues first:

- Did you save the file?
- Is the file name spelled correctly?
- Is the file extension correct?
- Is the image or linked file in the correct folder?
- Did you accidentally move or delete a starter file?
- Is your content inside the `body` element?
- Are your opening and closing tags in the correct places?
- Are your quotation marks around attribute values?
- Are your image paths correct?
- Are your link paths correct?
- Did you copy the navigation to all three pages?
- Did you zip the correct folder?

Coding is detail-oriented. Small mistakes are normal, especially when you are learning. The goal is to slow down, check carefully, and practice troubleshooting.

---

## Reminder

This is your first small multi-page website.

It may not look visually exciting yet, and that is okay. You are learning how to structure several pages, connect them with navigation, add images, and make the files work together.

Those are major building blocks for the rest of the course.
