# design-checklist
Down the line, I've often come to realize during (or after) design hand-off: "hmm.. is this well-thought" or "this design does not seem to take this into account". Therefore I've created a checklist to go through, before and during design phase, to make sure most design decisions has been properly addressed sooner rather than later.

Feel free to fork it, contribute, etc.


## How should this be interpreted?
This is NOT a set in stone "my way or the high way" document. This is a checklist to verify that design principles are well-thought AND an overview of approaches that deviate from these, to make sure that we have proper argumentation for doing so.

## The Checklist

### General
- [ ] How does this look like on tablet/desktop (in case of mobile first approach)
- [ ] How does tihs look like on mobile (in case of desktop first/only approach)

### CTAs
- [ ] Consistency on "save" actions. Either always click a "submit" button or always auto-save.

### Viewport
- [ ] First section doesn't take up whole viewport height size _(at least give user an indication that more is to come by scrolling/clicking)_.

### Content
- [ ] Design is not only useful with "perfect" data.
- [ ] Design does not restrict content to "perfect" data.

### Search
- [ ] Search is visible on page _(if only visible by click, then at least autofocus search field when clicked)_.

### Headings
- [ ] Headings follow an ordering pattern _(e.g. .h1 more prominent than .h2 and .h3, etc)_.

### Input fields
- [ ] Text inputs has labels _(not only placeholders)_.
- [ ] Text inputs take advantage of native scrollwheels on mobile _(e.g. datetime-local)_.
- [ ] Show restrictions to input up front _(e.g. "We only accept VISA and MasterCard" or "Should be a valid email format")_.

### Selects / Dropdowns
- [ ] Select inputs doesn't disable native behavior _(e.g. scrollwheel on mobile)_.

### Errors
- [ ] Show all possible errors at once to prevent circle feedback and multiple user tries
