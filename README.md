# SvelteKit Starter Project
This is a base starter project in SvelteKit that can be used as a template for future projects.

## New Project

1. Clone starter
2. Rename project
3. Install dependencies
4. Update site configuration
5. Add branding/fonts
6. Configure environment variables
7. Start development server
8. Build pages
9. Add optional features as needed
10. Deploy to Netlify
11. Transfer ownership to client

## CSS
The style sheets have been broken up for clarity and ease of use. The app.css has imports of all the other sheets and is the only one referenced in the project layout. The reset is basically a copy of Andy Bell's CSS reset. Typography and Forms have the styles for the copy, headings, form elements, and buttons.

### Variables
The variables style sheet contains size and space variables from Utopia.fyi. It also contains some default fonts from ModernFontStacks.com (no downloading needed). There are also variables for light and dark neutral colors and a primary and secondary color. For colors, it's best to use a few colors and create variation with opacity.

### Layout
The layout style sheet has a few useful layout options that commonly occur.
* .container is used on every page to keep content a regular distance off the edge.
* .auto-grid will take a set of grid items (usually product cards) and display them to automatically fit the space with uniform widths regardless of screen size.
* .flex-group will automatically cluster a group of items (like filter chips) that don't need uniform width, but should be grouped together and able to wrap to the next row to prevent overflow.
* .stack (and variations) are used to provide regularly spaced stacks of elements.
* The sidebar layout uses a few different classes
    * .with-sidebar defines the container that has a sidebar and other content.
    * .sidebar is a child inside the .with-sidebar element and will stay the same size until it automatically switches to be on top of the other content at certain screen sizes (no media query required).
    * .not-sidebar is the child that contains the main content. Its size will automatically adjust to fill the width.
* .switcher will automatically switch from row to column depending on the screen size, also without media queries.