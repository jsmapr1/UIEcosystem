# UI Ecosystem
*DEG UI Code Standards, Design Patterns, Frameworks & Tooling*

## Table of Contents
  1. [Code Standards](#code-standards)
    - [HTML](#html)
    - [CSS](#css)
    - [Javascript](#javascript)
  2. [Design Patterns](#design-patterns)
    - [Atomic Design](#atomic-design)
    - [Browser Support](#browser-support)
    - [Accessibility](#accessibility)
    - [Performance](#performance)
    - [Detailed Design Patterns & Anti-Patterns](#detailed-design-patterns--anti-patterns)
  3. [Frameworks](#frameworks)
    - [Skeletor](#skeletor)
    - [Pattern Lab](#pattern-lab)
  4. [Tooling](#tooling)
    - [IDEs](#ides)
    - [CSS](#css-1)
    - [Javascript](#javascript-1)
    - [ALM](#alm)
    - [Version Control](#version-control)
    - [Testing](#testing)


## Code Standards

### HTML

### CSS
**Atomic CSS**
* Modular
* Organisation: Basics, Components, Templates, Pages

**Pseudo BEM**

Classes should be lowercase and follow pseudo BEM practices

**Selectors**
* ID selectors
* Javascript hooks
* Nested Selectors

**Variables**

**Breakpoints & Media Queries**
* Mobile First

### Javascript
**ES6**
* Template Strings

**DEGJS**

## Design Patterns

### Atomic Design
The DEG UI team encourages the use of the [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design) methodology for creating design systems. The basic gist of atomic design is to break interfaces down into fundamental building blocks and work up from there. Traditional atomic design consists of 5 distinct levels:
- __Atoms__: Basic building blocks. HTML tags, such as a form label, an input or a button.
- __Molecules__: Groups of atoms bonded together. Form label, input & button combined together.
- __Organisms__: Groups of molecules joined together to form a distinct section of an interface.
- __Templates__: Groups of organisms stitched together to form pages.
- __Pages__: Specific instances of templates.

DEG uses a modified version of these levels to simplify development, tie in better with design processes & deliverables, and to use terminology that is easier for clients to understand. Our version of atomic design consists of 4 dinstinct levels:
- __Basics__: Basic building blocks. Typography, colors, & basic HTML tags.
- __Components__: Groups of basics or other components combined together. Components should be nested into parent & child relationships when applicable.
- __Templates__: Groups of components combined together to create pages.
- __Pages__: Specific instances of templates.

### Browser Support
DEG uses the concept of Graded Browser Support, which defines the set of browsers that should receive a verified, usable experience. However, trying to deliver the same "A-grade" experience across all tested browsers is neither cost-effective nor common. We support a tiered approach to user experience design, development, and testing, and encourage each project to define their own tiers that serve their users and stakeholders best. For a more detailed explanation and a guide to help determine what browsers to support, view our [Browser Support Guide](https://docs.google.com/document/d/1RDcfLoOyj-zwz7JmFxV6KQVlZ_yuZhhSMornd-uikaE/edit#) on Google Docs.

### Accessibility
[Accessibilty guidelines here]

### Performance
Because speed and performance is a vital part of any website, DEG encourages the use of performance budgets to help guide design and development decisions.

A performance budget is like any other project budget: it defines a clear goal that the project can be evaluated against to determine success. More specifically, a performance budget sets limits for individual pages of a website that should not be exceeded. These limits can be expressed in the form of several metrics, such as how long it takes for a page to load and how many kilobytes a page weighs.
A performance budget helps you choose how to display content or define functionality. It does not dictate what content should be displayed. Removing something important to decrease page weight is not a good performance strategy.
The overall benefit of a performance budget is a fast, lightweight website.

For more details on how and when DEG sets performance budgets, view our [Performance Budget Guide](https://docs.google.com/document/d/1JobZThkKpRAtSGHGZ7aCJ5Ub_1q2SJqohDPjQmjeLiE/edit) on Google Docs.

### Detailed Design Patterns & Anti-Patterns
Although projects do often present unique challenges, there are certain challenges we see repeated across many projects. Because of this, the DEG UI team maintains a set of client facing documentation on the best practices for using and implementing common design patterns & anti-patterns including:
- [Carousels](https://docs.google.com/document/d/1iBiWISTsRwTv-Jc7VEJGHhVXnru8Tyf2YZ4olHvjg-g/edit)
- [Hover Interactions](https://docs.google.com/document/d/1L_ppJEh24ly_R_LgC_9whqylc9FnkAokNAEJFuDLbY8/edit)
- [Infinite Scrolling vs Pagination](https://docs.google.com/document/d/1C4XFaIfv2Pt0dyRjGYZVUTo5sTw-RzqYk8ingLuxfOI/edit)
- [Mega Menus](https://docs.google.com/document/d/1l7t2MpYf1Ux-RtRyzD2NKWinuLwmD4IYFX8emtpJFcc/edit)
- [The Fold](https://docs.google.com/presentation/d/1baCcqMkYE0h3S7oP637ZMjK106bUpyHNRMw2NW7a4BE/edit?usp=drive_web)
- [Web Fonts](https://docs.google.com/document/d/16_8FOMAAdCp2FL-vtSkj72uUVYpiBaYRUw0JrlAdpQE/edit)

## Frameworks

### Skeletor

Skeletor is a [Grunt](http://gruntjs.com)-powered, [Pattern Lab](http://patternlab.io)-centric, highly-customizable web project boilerplate and build tool created by the [DEG](http://www.degdigital.com) UI team. Skeletor uses [PostCSS](http://postcss.org) for CSS processing and [JSPM](http://jspm.io)/[SystemJS](https://github.com/systemjs/systemjs) for Javascript package management, module bundling/loading, and transpilation. Full Skeletor documentation is available [here](https://github.com/degdigital/skeletor).

### Pattern Lab


## Tooling

### IDEs
* Sublime Text
* PHPStorm

### CSS
**PostCSS**

**Legacy**
* Sass
* Compass

### Javascript
**General**
* JSPM - Package Management
* SystemJS - Module Bundling
* DEGJS

**Magento**
* jQuery

### ALM
* JIRA
* Assembla

### Version Control
**Git**

**Git Workflows**

### Testing
* BrowserStack
