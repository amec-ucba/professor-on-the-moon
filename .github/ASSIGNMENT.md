# 🌙 The Professor Who Walked on the Moon

## 🎯 Overview

A typography exercise for Web Design I.

You're given a finished feature article about Neil Armstrong's eight years teaching at the University of Cincinnati.
The HTML is done, and `css/base.css` already handles layout, spacing and background colors. What the page doesn't have
is any typography. Every font, size, weight and line height is still the browser default, and the text has no color
accents. Your job is to write `css/typography.css` and turn a plain page into one that reads like a polished magazine
feature.

## 📋 Requirements

### Setup

- [ ] Create `css/typography.css` and link it in `index.html` **after** `css/base.css`.
- [ ] Do not edit `css/base.css` or change the content of `index.html`. The only change to `index.html` is adding your
  stylesheet link (and a Google Fonts link, if you use one).

### Typefaces

- [ ] Use at least **two** typefaces with a clear purpose for each, such as a sans-serif for headings and labels and a
  serif for body text. Google Fonts is fine.
- [ ] Every `font-family` ends with a generic fallback (`serif`, `sans-serif`, etc.).

### Hierarchy

- [ ] The `h1` is clearly the largest, boldest text on the page.
- [ ] Section `h2` headings are clearly smaller than the `h1` and clearly larger or heavier than body text.
- [ ] The deck (`.deck`) reads as an introduction: larger than body text, and set apart with style (italic, for
  example).
- [ ] Small supporting text is smaller than body text: the byline, the figure caption and the footer.

### Readability

- [ ] Body text is comfortable to read: about `1rem`–`1.25rem` with a `line-height` of about `1.5`–`1.7`.
- [ ] Headings use a tighter `line-height` than body text.
- [ ] Lines of body text are a readable length, roughly 60–75 characters. Set a `max-width` on `header`, `main` and
  `footer` (`base.css` doesn't).

### Details

- [ ] The kicker (`.kicker`) is small, uppercase and letter-spaced.
- [ ] The pull quote is the largest text in the article body. Its `cite` is small and styled differently from the quote.
- [ ] The photo credit (`.credit`) is styled differently from the rest of the caption.
- [ ] In the Fast Facts sidebar, each term (`dt`) is styled differently from its description (`dd`).
- [ ] Use `text-transform` and `letter-spacing` for small labels, such as the kicker, the `cite`, and the Fast Facts
  and Sources headings. Don't use them on body text.

### Color

`base.css` keeps the text mostly black, gray and white. Add a few **splashes of color** to make the page pop.

- [ ] Give links a color so they stand out from the text around them.
- [ ] Add color to at least **two** more pieces of text, such as the kicker or the Fast Facts terms.
- [ ] Use color as an accent, not on everything. One or two accent colors is plenty.
- [ ] Every text color has a contrast ratio of at least **4.5:1** against its background. Check with the
  [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/). Check each color against the background it
  sits on: UC red (`#e00122`) passes on the cream page (4.79:1) but fails on the navy Fast Facts box (3.35:1).

## 🖼️ Example Output

This is one possible solution. Yours doesn't need to match it. It needs to meet the requirements and be easy to read.

![The finished feature article with a sans-serif headline, italic serif deck, serif body text, a large italic pull
quote, a navy Fast Facts box with pink labels, and red source links](../images/final.png)

Notice how little color it uses: a red kicker, pink terms in the Fast Facts box and red links in the Sources list. Those
few accents are enough to guide the eye.

## 📂 Starter Files

| File / Folder                    | Purpose                                                        |
|----------------------------------|----------------------------------------------------------------|
| `index.html`                     | The finished article. Only add your `<link>` tags.             |
| `css/base.css`                   | Layout, spacing and background colors. **Don't edit.**         |
| `css/typography.css`             | **You create this.** All of your work goes here.               |
| `images/professor-armstrong.webp` | The feature photo.                                            |
| `images/final.png`               | The example screenshot above.                                  |

## 🧮 Grading

| Criteria                                                                 | Points |
|--------------------------------------------------------------------------|--------|
| Setup: `typography.css` is created and linked, and no other files are edited | 2      |
| Typefaces: at least two typefaces, each with a purpose and a fallback     | 3      |
| Hierarchy: the `h1`, `h2`, deck and small text are clearly different     | 5      |
| Readability: body size, line height and line length                      | 4      |
| Details: kicker, pull quote, caption credit and Fast Facts               | 3      |
| Color: links and two more accents, all passing 4.5:1 contrast            | 3      |
| **Total**                                                                | **20** |

## 📚 Resources

- [MDN: Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Fundamentals)
- [MDN: Web fonts](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Web_fonts)
- [Google Fonts](https://fonts.google.com/)
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Butterick's Practical Typography](https://practicaltypography.com/)

## 🆘 Getting Help

Ask during class or office hours, or post on the Canvas discussion board.

---

The AI policy and submission instructions are in the [README](../README.md).
