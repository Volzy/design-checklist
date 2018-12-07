# design-checklist
Down the line, I've often come to realize during (or after) design hand-off: "hmm.. is this well-thought" or "this design does not seem to take this into account". Therefore I've created a checklist to go through, before and during design phase, to make sure most design decisions has been properly addressed sooner rather than later.

## How should this be interpreted?
This is NOT a set in stone "my way or the high way" document. This is a checklist to verify that design principles are well-thought AND an overview of approaches that deviate from these, to make sure that we have proper argumentation for doing so.

## The Checklist

### General
- [ ] How does this look like on tablet/desktop (in case of mobile first approach)
- [ ] How does tihs look like on mobile (in case of desktop first/only approach)

### Viewport
- [ ] First section doesn't take up whole viewport height size (at least give user an indication that more is to come by scrolling/clicking).

### Content
- [ ] Design is not only useful with "perfect" data.
- [ ] Design does not restrict content to "perfect" data.

### Search
- [ ] Search is visible on page (if only visible by click, then at least autofocus search field when clicked).

### Headings
- [ ] Headings follow an ordering pattern (e.g. .h1 more prominent than .h2 and .h3, etc).

### Input fields
- [ ] Text inputs has labels (not only placeholders).
- [ ] Text inputs take advantage of native scrollwheels on mobile (e.g. datetime-local).

### Selects / Dropdowns
- [ ] Select inputs doesn't disable native behavior (e.g. scrollwheel on mobile).
