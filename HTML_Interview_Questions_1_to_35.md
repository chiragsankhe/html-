# HTML Interview Questions and Answers

## 1. What is HTML?

HTML (HyperText Markup Language) is the standard markup language used to
create web pages.

## 2. What are HTML tags?

HTML tags are special keywords enclosed in angle brackets `< >` that
define how elements should appear or behave.

## 3. What is the difference between HTML and XHTML?

-   HTML is flexible with syntax, while XHTML is stricter.
-   XHTML requires properly nested, lowercase tags and properly closed
    elements.

## 4. What are semantic HTML elements?

Semantic elements clearly describe their meaning to both browsers and
developers, e.g., `<header>`, `<footer>`, `<article>`, `<section>`.

## 5. Difference between `<div>` and `<span>`?

-   `<div>` → block-level element (takes full width).
-   `<span>` → inline element (takes only necessary width).

## 6. What are void (empty) elements in HTML?

Tags that don't have a closing tag, like `<br>`, `<hr>`, `<img>`,
`<meta>`, and `<input>`.

## 7. What is the difference between inline and block-level elements?

-   **Block-level**: starts on a new line and takes up the full width.
    (e.g., `<div>`, `<p>`)
-   **Inline**: stays in the same line and takes up only as much width
    as necessary. (e.g., `<span>`, `<a>`)

## 8. What is the difference between `<link>` and `<a>`?

-   `<link>` → connects external resources like CSS.
-   `<a>` → creates hyperlinks.

## 9. What is the difference between `<strong>` and `<b>`?

-   `<b>` → bolds text visually only.
-   `<strong>` → bolds text **and** gives semantic meaning (important
    content).

## 10. What is the difference between `<em>` and `<i>`?

-   `<i>` → italicizes text visually.
-   `<em>` → emphasizes text semantically.

## 11. What is the difference between `id` and `class`?

-   **id**: unique per page.
-   **class**: reusable on multiple elements.

## 12. What is the difference between relative, absolute, and fixed positioning in CSS?

-   **Relative** → positioned relative to itself.
-   **Absolute** → positioned relative to nearest positioned ancestor.
-   **Fixed** → stays fixed relative to viewport.

## 13. What is the difference between `<ol>`, `<ul>`, and `<dl>`?

-   `<ol>`: ordered list.
-   `<ul>`: unordered list.
-   `<dl>`: definition list.

## 14. What is the purpose of `<meta>` tags?

They provide metadata like character encoding, viewport settings, and
SEO-related info.

## 15. What is the difference between HTML5 and HTML4?

-   HTML5 introduces semantic tags (`<header>`, `<footer>`), multimedia
    tags (`<audio>`, `<video>`), and APIs like `canvas`.

## 16. What are the new form input types in HTML5?

`email`, `url`, `number`, `range`, `date`, `color`, `datetime-local`,
etc.

## 17. What is the difference between `<section>` and `<article>`?

-   `<section>` → groups related content.
-   `<article>` → represents independent, self-contained content.

## 18. What is the difference between `<header>` and `<head>`?

-   `<head>`: contains metadata, scripts, and styles.
-   `<header>`: visible top content for a section or page.

## 19. What is the difference between `<canvas>` and `<svg>`?

-   `<canvas>` → pixel-based rendering.
-   `<svg>` → scalable vector graphics (XML-based).

## 20. What is the difference between `<script>` and `<noscript>`?

-   `<script>` → defines JavaScript.
-   `<noscript>` → content shown when JS is disabled.

## 21. What are HTML data attributes?

Custom attributes prefixed with `data-` to store extra data in
elements.\
Example:

``` html
<div data-user="123" data-role="admin"></div>
```

## 22. What is the difference between `<iframe>` and `<frame>`?

-   `<iframe>`: embeds another webpage within the current page.
-   `<frame>`: obsolete, used for framesets in older HTML versions.

## 23. How do you make a hyperlink open in a new tab?

``` html
<a href="https://example.com" target="_blank">Open</a>
```

## 24. What is the difference between absolute and relative URLs?

-   **Absolute URL**: full path (`https://site.com/page`).
-   **Relative URL**: path relative to current page (`/page` or
    `../page`).

## 25. What are web storage APIs in HTML5?

-   **localStorage** → stores data permanently until cleared.
-   **sessionStorage** → stores data for one session only.

## 26. What is the difference between cookies, localStorage, and sessionStorage?

  ------------------------------------------------------------------------
  Feature          Cookies             localStorage       sessionStorage
  ---------------- ------------------- ------------------ ----------------
  Size             \~4KB               \~5MB              \~5MB

  Expiry           Set manually        No expiry          Ends on tab
                                                          close

  Sent to server   Yes                 No                 No
  ------------------------------------------------------------------------

## 27. What are the advantages of HTML5?

-   Semantic tags
-   Better form controls
-   Multimedia support
-   Offline storage (`localStorage`)
-   Mobile-friendly

## 28. What is the difference between inline CSS, internal CSS, and external CSS?

-   **Inline**: in the element via `style`.
-   **Internal**: inside `<style>` in `<head>`.
-   **External**: linked via `<link>`.

## 29. What are favicons in HTML?

Small icons shown in browser tabs.

``` html
<link rel="icon" href="favicon.ico" type="image/x-icon">
```

## 30. How to include audio and video in HTML5?

``` html
<audio controls>
  <source src="song.mp3" type="audio/mp3">
</audio>

<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

## 31. What is the difference between `<progress>` and `<meter>`?

-   `<progress>` → shows progress of a task.
-   `<meter>` → displays a scalar measurement within a known range.

## 32. What is the difference between `<datalist>` and `<select>`?

-   `<select>` → dropdown with predefined options.
-   `<datalist>` → text input with suggested options.

## 33. What are ARIA roles in HTML?

Attributes like `role="button"` improve accessibility for screen
readers.

## 34. What are the advantages of using semantic tags?

-   Better SEO
-   Easier readability
-   Better accessibility
-   Cleaner code

## 35. How to make an image clickable?

``` html
<a href="https://example.com">
  <img src="image.jpg" alt="Example">
</a>
```
