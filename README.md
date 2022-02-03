![Accessibility can be written a11y](images/a11y-spelled.PNG "")

# a11y (WIP)

## About a11y

### What is accessibility?

### Why should my product be accessible?

+ Responsibility
+ SEO
+ Brand image
+ Performance
+ Legal

#### Responsibility

#### SEO

#### Brand image

#### Performance (progressive enhancement)

#### Legal

Dissability Discrimination Act (DDA): https://humanrights.gov.au/our-work/employers/disability-discrimination#:~:text=The%20Disability%20Discrimination%20Act%201992,places%2C%20because%20of%20their%20disability.

> The Disability Discrimination Act 1992 (DDA) makes it unlawful to discriminate against a person, in many areas of public life, including employment, education, getting or using services, renting or buying a house or unit, and accessing public places, because of their disability.

The 2020 Sidney Olimpic Games website:

+ https://www.w3.org/WAI/business-case/archive/socog-case-study

+ http://www.tomw.net.au/2001/bat2001f.html#:~:text=A%20decision%20on%20the%20web,start%20of%20the%20Sydney%20Olympics.

United States web accessibility related laws: https://dynomapper.com/blog/27-accessibility-testing/569-united-states-accessibility-laws

## Articles

+ [CSS outline property] (https://www.outlinenone.com/)

## Pills

+ Twitter de Eric Meyer: https://twitter.com/meyerweb/status/1072202246241144832

## Talks

+ Lo veo todo negro, Juanjo Montiel (TarugoConf 2020): https://www.tarugoconf.com/blog/tarugo20-juanjo-montiel/

## Docs

### W3C - WAI

#### Links

+ WAI (Web Accessibility Initiative)
+ WCAG (Web Content Accessibility Guidelines): https://www.w3.org/WAI/standards-guidelines/wcag/
+ ATAG: (Authoring Tool Accessibility Guidelines): https://www.w3.org/WAI/standards-guidelines/atag/
+ UAAG (User Agent Accessibility Guidelines): https://www.w3.org/WAI/standards-guidelines/uaag/
+ ARIA (Accessible Rich Internet Applications): https://www.w3.org/WAI/standards-guidelines/aria/

#### Principles

1. Perceivable
2. Operable
3. Understandable
4. Robust

#### Levels

+ A
+ AA
+ AAA

#### Highlights

+ Success criteria for contrast evaluation: https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html

### MDN

+ About CSS outline in MDN: https://developer.mozilla.org/es/docs/Web/CSS/outline
+ About CSS prefers-reduced-motion in MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion

## Action inputs

### HTML5

+ Use semantic tags as much as possible: `<header>`, `<nav>`, `<footer>` instead of always `<div>`.

### Headings

+ Use headings hierarchically.
+ 

### Images

+ Use the `alt` attribute for providing a short description.
+ Do not use the word _image_ or _picture_ in the `alt` attribute.
+ Descriptions in `alt` attributes should be 125 characters or less (restriction most screen readers have). 
+ Decorating images (CSS background images, sometimes icons...) should not be part of the info, they should not have `alt` attribute.

### Forms

+ Use `<label>` tags with `for` attriutes , `aria-labelledby`...
+ Do not rely only on color to mark required fields.
+ Use `<legend>` to explain the whole form.

### Tables

+ Do not use tables for layout.

### Audio

+ Text transcripts

### Video

+ Captions
+ If autoplayed, disable it if the user has the prefers-reduce-motion flag enabled. 

## Tools

### Development

+ Chrome devtools report
+ Chrome DOM inspector highlights
+ Contrast checker: https://webaim.org/resources/contrastchecker/

### Screen magnifiers

### Screen readers

+ NVDA download: https://www.nvaccess.org/download/

### Alternate input devices

Braille, etc...

## Samples

+ prefers-reduced-motion, Video vs Image: https://codepen.io/agarcav/pen/eYezwNj

## Worth reading

+ CSS tricks articles for accessibility: https://css-tricks.com/tag/accessibility/

+ The a11y project: https://www.a11yproject.com/

## Miscelanea

+ Australia colour map helper: https://www.visionaustralia.org/services/digital-access/resources/colourmap
+ Twitter uses `lang` attribute to mark each Tweet language. 

## Questions to ask yourself...

+ Can left-handed people use your website the same way a right-handed person?
+ Is your web application keyboard accessible?
+ Can we consider not knowing a language a dissability?
+ Would your web application be usable/understanded in black and white?
+ Can we consider novice users (in terms of technology knowledge) are suffering a dissability?
+ Can we consider not having a cutting edge device a dissability?
+ Why government websites do not use React/Angular/Vue/FancyNewJsFramework?

---

But the most important thing you can do is... put yourself in the place of other people.
