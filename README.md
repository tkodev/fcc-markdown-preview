# FreeCodeCamp - Front End Libraries Projects - Build a Markdown Previewer
[View Challenge](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-markdown-previewer)

## Project Criteria:
- **Objective:** Build a [CodePen.io](https://codepen.io) app that is functionally similar to this: [https://codepen.io/freeCodeCamp/full/GrZVVO](https://codepen.io/freeCodeCamp/full/GrZVVO).
- Fulfill the below [user stories](https://en.wikipedia.org/wiki/User_story) and get all of the tests to pass. Give it your own personal style.
- **User Story #1:** I can see a `textarea` element with a corresponding `id="editor"`.
- **User Story #2:** I can see an element with a corresponding `id="preview"`.
- **User Story #3:** When I enter text into the `#editor` element, the `#preview` element is updated as I type to display the content of the textarea.
- **User Story #4:** When I enter GitHub flavored markdown into the `#editor` element, the text is rendered as HTML in the `#preview` element as I type (HINT: You don't need to parse Markdown yourself - you can import the Marked library for this: [https://cdnjs.com/libraries/marked](https://cdnjs.com/libraries/marked)).
- **User Story #5:** When my markdown previewer first loads, the default text in the `#editor` field should contain valid markdown that represents at least one of each of the following elements: a header (H1 size), a sub header (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text.
- **User Story #6:** When my markdown previewer first loads, the default markdown in the `#editor` field should be rendered as HTML in the `#preview` element.
- **Optional Bonus (you do not need to make this test pass):** My markdown previewer interprets carriage returns and renders them as `br` (line break) elements.
- You can use this CDN link to run the tests in any environment you like: `https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js`.