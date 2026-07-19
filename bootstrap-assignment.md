# Bootstrap Assignment: Building a Responsive "About Me" Page

## Objective
Practice using Bootstrap's **grid system**, **columns**, **typography utilities**, and **image classes** by building a single responsive HTML page.

## Instructions
- Create a **new HTML file** (e.g., `index.html`) separate from this assignment sheet — do NOT write your answers here.
- Link Bootstrap via CDN in your new file.
- Complete all the tasks below inside that file.
- Test your page at different screen sizes (resize your browser or use dev tools) to confirm it's responsive.

---

## Part 1: Page Setup
1. Create a basic HTML5 document.
2. Link the Bootstrap CSS (and JS bundle, if needed) via CDN in the `<head>`.
3. Wrap your page content in a `.container`.

## Part 2: Typography
1. Add a main heading (`<h1>`) with your name — style it using a Bootstrap **display heading** class (e.g. `display-4`).
2. Add a subheading (`<h3>` or `<h4>`) that says "Frontend Developer in Training" (or a title of your choice), and give it a **muted text** style.
3. Write a short paragraph (3–4 sentences) introducing yourself. Apply at least:
   - One **text alignment** utility (e.g. `text-center` or `text-md-start`)
   - One **font-weight** utility (e.g. `fw-bold` or `fw-light`)
4. Add a blockquote (using Bootstrap's `.blockquote` class) containing your favorite quote.

## Part 3: Grid & Columns
1. Create a row (`.row`) with **three columns** (`.col-*`) that represent three of your **skills** (e.g. HTML, CSS, JavaScript). Each column should contain:
   - A heading (skill name)
   - A short description
2. Make the columns **responsive**:
   - Full width on small screens (mobile)
   - 3 per row on medium screens and up
3. Create a **second row** with **two unequal columns**:
   - Left column: takes up **8/12** of the width on large screens — put a short "About My Journey" paragraph here.
   - Right column: takes up **4/12** of the width on large screens — put a small "Fun Facts" list here (use an unordered list).
4. Add appropriate **gutter spacing** (`g-*` classes) between your columns so they don't touch.

## Part 4: Images
1. Add a profile image (use any placeholder image, e.g. from `https://placehold.co/300x300`) and apply:
   - The `.img-fluid` class so it resizes responsively
   - A **rounded** or **rounded-circle** style
2. Inside one of your skill columns from Part 3, add a small relevant icon/image and make sure it doesn't overflow its column (again using `.img-fluid`).
3. Add a **thumbnail-style** image (using `.img-thumbnail`) somewhere on the page — for example, a "certificate" or "project screenshot" placeholder.

## Part 5: Bringing It Together
1. Add a footer at the bottom of the page with your name and the current year, centered using text utilities.
2. Make sure the whole page:
   - Has no horizontal scroll on mobile view
   - Uses at least **one breakpoint prefix** (`sm`, `md`, `lg`, or `xl`) somewhere in your column classes
   - Looks organized and readable at all screen sizes

---

## Bonus (Optional)
- Add a border and padding to each skill column using Bootstrap spacing/border utilities.
- Use `.text-uppercase` or `.text-lowercase` on one of your headings.
- Nest a small row/column structure *inside* one of your existing columns.

---

## Submission Checklist
- [ ] Separate HTML file created (not written in this document)
- [ ] Bootstrap linked via CDN
- [ ] Typography utilities used (heading, muted text, alignment, font-weight, blockquote)
- [ ] Grid with 3 responsive columns (skills)
- [ ] Grid with 2 unequal columns (8/4 split) + gutter spacing
- [ ] At least 3 image classes used (`img-fluid`, `rounded`/`rounded-circle`, `img-thumbnail`)
- [ ] Page is responsive with no horizontal scroll on mobile
- [ ] Footer included
