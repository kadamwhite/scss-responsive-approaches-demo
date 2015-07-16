Two options for responsive tabular display without SCSS

Navigate to [kadamwhite.github.io/scss-responsive-approaches-demo/](http://kadamwhite.github.io/scss-responsive-approaches-demo/) to see the two demo pages live

## Overview

- mq-generator uses a SCSS mixin to generate explicit layout classes which will set certain behavior at certain breakpoints. Different layouts of tables are achieved by authoring each table layout in separate, sibling containers, which are conditionally hidden or shown.
- respond-to uses responsive mixins to instruct semantic classes to respond conditionally to different screen sizes. Which type of layout is used is goverened by a parent class. Rather than duplicating the entire layout's markup, only the headings for the data need to be repeated throughout the table.

## Local Installation

1. Download the repo and navigate to the repo's root folder in the terminal
2. Run `npm install` to install the build dependencies
3. Run `npm start` to compile the SCSS and start a local server
4. Navigate to [http://localhost:3000](http://localhost:3000) to see the two demo pages
