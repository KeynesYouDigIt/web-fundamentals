---
title: Class 6 Prep
currentMenu: classes
---

## Templates

Thus far, on the back-end, we have managed HTML by storing it in long strings within our Python code. You probably found this process tedious and annoying. Fortunately, there is a much nicer way of constructing HTML content to send back to the client.

Using what's called a *template* engine, we can specify our HTML as a "template" inside a regular `.html` file, and simply leave a few "blank spaces", so to speak, wherever we want to place dynamically-generated content. Then our back-end code simply needs to "fill in the blanks". In this lesson you will learn how to use a Python template engine called Jinja 2.

Done |Task | Resource Type | Link | Instructions
|----|-----|---------------|------|-------------|
<input type="checkbox" v-model="checks.p6a" /> |Do | Interactive Lesson | [Using Jinja2 Templates in Flask](../../videos/using-jinja/) | Set up a Jinja2 template loader and render templates
<input type="checkbox" v-model="checks.p6b" /> |Do | Interactive Lesson | [Variable Expressions in Jinja2 Templates](../../videos/jinja-variable-expressions/) | Use variable expressions in Jinja2 templates
<input type="checkbox" v-model="checks.p6c" /> |Do | Interactive Lesson | [A Task List App](../../videos/task-list/) | Create a minimal task list that uses conditionals and loops in its template
<input type="checkbox" v-model="checks.p6d" /> |Do | Interactive Lesson | [Template Extensions](../../videos/template-extensions/) | Create base templates and template extensions
<input type="checkbox" v-model="checks.p6e" /> |Watch | Lesson | [Using render_template](../../videos/render-template) | Learn how to use the `flask.render_template` function to more easily render templates when using our most common template setup
<input type="checkbox" v-model="checks.p6f" /> |Do | Review | [Class 6 Prep Review](review.html) | Solidify your knowledge of the concepts covered in these lessons
