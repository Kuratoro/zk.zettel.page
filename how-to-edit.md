---
title: How to edit this site
---

TODO: Explain in more detail (summarize the documentation for Neuron - both technical(short version) and layperson's terms?)
- PR
- YAML
- linking files
- Simple Markdown guide

To edit a page,

1. If you don't already have one, create a GitHub account.
2. Go to a zettel page you wish to edit, and click the edit icon below.
3. Edit, and save (PR).

To create a new page,

1. Go to the repository: <https://github.com/srid/reddit.zettel.page>
2. Click the "Create new file" button
3. Add the title of the zettel between two `---` lines. (the YAML metadata).

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
* <file-name.md> --> this will show the link in the Zettel
<file-name.md>  --> this will not be shown in the Zettel but will be shown as linked (EDIT: Hmm, it worked last time but I guess not)

```
## Markdown Guidelines

* The title of the Zettel will be a first level heading.
