---
title: How to edit this site
---

TODO: Explain in more detail (summarize the documentation for Neuron - both technical(short version) and layperson's terms?)
- PR
- YAML
- ~~linking files~~
- ~~Simple Markdown guide~~

## How to edit an existing page/note/Zettel

1. If you don't already have one, create a GitHub account.
2. Go to a Zettel page you wish to edit, and click the edit icon in the navigation below.
3. Edit, and save (creates a PR (pull request) which the moderators can review and merge).

## How to create a new page/note/Zettel

1. Go to the repository: <https://github.com/srid/reddit.zettel.page>
2. Click the "Create new file" button
3. Add the title and creation date of the Zettel between two `---` lines. (the YAML metadata which ensures that the file becomes a page).

**Tip**: It helps to have the list of all the file names handy in case you want to link to any of them.

## Template for Metadata

```yml
---
title:
date:
tags:
---
```

## How to Link to Other Zettel

Linking to a file within a Zettel indicates that it is branching off from it. Backlinks are automatically shown on the web browser. 

```markdown
<file-name.md> --> this will show the link in the Zettel
```

Example: This is an example of a link using an <example.md> note.

## Markdown Guidelines

* Markdown is a way to format text that is easier to read and write (compared to HTML).
* Notes in this Zettelkasten should be formatted in Markdown.
* Link to a basic Markdown [primer](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Notes (specific to Neuron)
  *  The title of the Zettel will be a first level heading.
  *  URL's must be enclosed in angle brackets to be formatted as a link `<url-example>`
