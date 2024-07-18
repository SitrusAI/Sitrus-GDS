# Sitrus Global Design System

This design system is part of the broader Sitrus development framework for rapid application development. It's comprised of plug-and-play CSS files for your project and features the following:

- Centralized design tokens for global style updates including light & dark colors, typography, spacing, and more. Color mixing is applied to automatically generate a rich palette of custom CSS variables from a handful of base colors.
- Modular stylesheets for each UI  component - keep the ones you need and toss the ones you don't.
- Styles applied directly to common HTML selectors, reducing the need for classes and verbose markups.
- Semantic classes also present for common UI elements without dedicated HTML tags.
- Pairs excellently with TailwindCSS, where CSS variables can be made availabile as custom utility classes for inline overrides.


## Instructions
1. Copy the `style` folder into your project directory.
2. Add `style/main.css` in your index.
3. To reduce payload, remove any CSS files in `style/elements` for UI components not required by the project, and eliminate their reference in `main.css`.
4. Modify `theme.css` with your design token values
5. Modify any other stylesheet with your style needs

## Usage
- `mains.css` imports all other CSS files for reference in your index.
- `theme.css` contains all design tokens for updating.
- `default.css` is a normalizer for the development framework.
- `elements` folder contains modular stylesheets for each UI component, which reference the theme's design tokens by default.
    - `accordion` - applies to the `<details>` and `<summary>` tags.
    - `aside` - applies to the HTML `<aside>` tag for callout blocks.
    - `badge` - applies to the `<mark>` tag for text and icon badges.
    - `button-group` - semantic class for multi-button containers.
    - `button` - applies to the `<button>` tag.
    - `checkbox` - applies to the `<input type="checkbox">` tag.
    - `code-block` - applies to the inline `<pre>` tag.
    - `divider` - applies to the `<hr>` tag, plus the `<div>` tag with the `divider` class and applicable modifier classes.
    - `dropdown` - for `<ul>` menus with the `dropdown` class, leveraging the HTML Popover API.
    - `figure` - applies to the `<figure>` tag for media and charts with a `<figcaption>` text caption.
    - `footer` - applies to the `<footer>` tag, plus nested `<nav>` and `<a>` elements.
    - `form` - applies to the `<form>` tag.
    - `header` - applies to the `<header>` tag for a page's top navigation, plus nested `<nav>` and `<a>` elements.
    - `image` - applies to the `<img>` tag.
    - `input` - applies to the `<input>` tag for text fields.
    - `logo` - semantic class for an element representing or containing the project logo, typically seen in headers and footers.
    - `modal` - applies to the `<dialog>` tag for modal menus, leveraging the HTML Popover API.
    - `nav-drawer` - applies to container elements for slide-out navigation drawers, leveraring the HTML Popover API.
    - `prose` - applies to container elements for opinionated styling of long form text articles like blogs and help docs.
    - `quote` - applies to the `<blockquote>` tag.
    - `radio-button` - applies to the `<input type="radio">` tag.
    - `switch` - applies to the `<input type="checkbox">` tag.
    - `table` - applies to the `<table>` tag.
    - `text-code` - applies to the inline `<code>` tag.
    - `text-kbd` - applies to the inline `<kbd>` tag.
    - `textarea` - applies to the `<textarea>` tag.
    - `tooltip` - applies to tooltips when using AlpineJS' alpine-tooltip extension.
    - `typography` - applies to all common text tags, with distinctions for inline and standalone links.
    - `video` - applies to the `<video>` tag.

### Dark Mode


### TailwindCSS Integration

#### Animations

#### Background Patterns

#### Masks

### Add-On Libraries

### Icons


### Tooltips