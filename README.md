# Sitrus Global Design System

This design system is part of the broader Sitrus development framework for rapid application development. It's comprised of plug-and-play CSS files for your project and features the following:

- Centralized design tokens for global style updates including light & dark colors, typography, spacing, and more. Color mixing is applied to automatically generate a rich palette of custom CSS variables from a handful of base colors.
- Modular stylesheets for each UI  component - keep the ones you need and toss the ones you don't.
- Theme variables and opinionated styles are applied to HTML selectors, reducing the need for classes and verbose markups.
- Pairs excellently with TailwindCSS, with CSS variables also made availabile as custom utility classes for inline overrides.


## Instructions
1. Copy the `style` folder into your project directory.
2. Add `style/main.css` in your index.
3. To reduce payload, remove any CSS files in `style/elements` for UI components not required by the project, and eliminate their reference in `main.css`.

## Usage
- `mains.css` imports all other CSS files for reference in your index.
- `theme.css` contains all design tokens for updating.
- `default.css` is a normalizer for the development framework.
- `elements` folder contains modular stylesheets for each UI component:
    - `accordion`
    - `aside`
    - `badge`
    - `button-group`
    - `button`
    - `checkbox`
    - `code block`
    - `divider`
    - `dropdown`
    - `figure`
    - `footer`
    - `form`
    - `header`
    - `image`
    - `input`
    - `logo`
    - `modal`
    - `nav drawer`
    - `prose`
    - `quote`
    - `radio button`
    - `section`
    - `segment`
    - `select`
    - `switch`
    - `table`
    - `text-code`
    - `text-kbd`
    - `textarea`
    - `ticker`
    - `tooltip`
    - `typography`
    - `video`

### Dark Mode


### Icons


### Tooltips


### TailwindCSS Integration

#### Animations

#### Background Patterns

#### Masks