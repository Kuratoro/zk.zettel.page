---
title: How to edit this site
---

## Editing existing pages
1. Create a [GitHub](https://github.com/) account if you do not already have one. You will need this in order to edit this Zettelkasten.
    - Your GitHub will also allow us to give you the necessary rights in the future.
1. In order to edit a zettel, navigate to its footer at the bottom and click the edit icon (paper and pencil). It will you take to GitHub wherein you can make the edits, and create what is known as a "PR" (pull request). 
1. When a PR is created /u/srid- or /u/EyebrowHairs will "accept" it
1. Once accepted, the site is updated within a minute.

If you are a frequent editor, we can even give you access, so that step 3 & 4 are obviated.


## Creating new pages

1. Go to the repository: <https://github.com/srid/reddit.zettel.page>
2. Click the "Create new file" button
3. Copy the paste the following template

**Tip**: It helps to have the list of all the file names handy in case you want to link to any of them.

### Template for new Zettel

Note: in the metadata, `title` is required; but `date` and `tags` are optional.

```markdown
---
title:
---

Hello world!
```

## How to Link to Other Zettel

Linking to a file within a Zettel indicates that it is branching off from it. Backlinks are automatically shown on the web browser. 

See [Neuron documentation](https://neuron.zettel.page/2011504.html) on how to link between zettels.
```markdown
<<<<<<< HEAD
<file-name.md> --> this will show the link in the Zettel
```

* `<file-name.md>` -- This links to the zettel "file-name.md"

Example: This is an example of a link using an <example.md> note.

## Markdown Guidelines

* Markdown is a way to format text that is easier to read and write (compared to HTML).
* Notes in this Zettelkasten should be formatted in Markdown.
* Link to a basic Markdown [primer](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Notes (specific to Neuron)
  * The title of the Zettel will be a first level heading.
  * URL's must be enclosed in angle brackets to be formatted as a link `<url-example>`
  * To add headings to your zettel start from level 2 (`## Heading`) headers, as level 1 heading is used for the Zettel title.
* Full list of features supported by Neuron, [see here](https://neuron.zettel.page/2011404.html)

