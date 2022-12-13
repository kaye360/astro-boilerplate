# 🚀 Astro Component Library

This is my astro component library to build out static sites quicker.

## /src file structure

/assets -> static assets for fonts, global css, and images

/components -> smaller components such as cards, buttons, logos etc

/layout -> Should only have 1 Layout.astro file here. This is the base layout for the site and will contain section blocks, components, and HTML

/pages -> All pages for the site

/sections -> larger groups of components/HTML that are used frequently

### Components

#### Back to Top
Fixed back to top of page link

#### Card
Basic card component

#### CTA Link
2 (usually) call to action buttons that go in the hero section

#### Logo
Site Logos

#### Mobile Menu Button
Button to toggle mobile menu. Javascript and CSS animation all self contained

#### Skip to Content
Accessible Skip to content Link

#### Social Icon
Social media icons

### Sections

### Nav
Different styles of NavBars. Top, TopFixed, Left etc.

### Hero
Hero section of the site

### Equal Columns
Equal columns that collapse down to single columns on small screen

### Even Colums
Similar to even columns, but must have an even amount of children and no more than 4. Collapses from 4 to 2 to 1 columns depending on screen size