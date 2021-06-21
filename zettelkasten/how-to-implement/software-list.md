---
date: 2020-05-14
---

# Software list

There are numerous digital Zettelkasten programs available. This note collects
links and pointers for choosing the right one. For comparison, see [[software-comparison]].

Note that it is likely that the tool you use doesn't really matter all that much. The original Zettelkasten was a huge stack of paper slips and even that worked great. There is one case where the choice of the tool has a huge impact, namely the case where the tool you use is discontinued. To avoid being left with a stack of 5000 notes that you can no longer access, prefer tools that export/save to common formats, like txt files.

Source: This is collected from [this discussion thread](https://www.reddit.com/r/Zettelkasten/comments/flygc4/lets_build_a_list_of_zettelkasten_software/). The discussion also lists lots of other tools by name.

## Software (ordered alphabetically)

### DEVONthink
* Videos
  *  <https://www.youtube.com/watch?v=nx6JhJH7du0.>
  *  <https://www.youtube.com/watch?v=lvDuVG6J3Xk>

### Emacs
* Videos
  * Zetteldeft: <https://www.youtube.com/watch?v=azOPZGO2vso>
  * Orgmode: <https://www.youtube.com/watch?v=UWB6ZABRVq0>

### [Neuron](https://neuron.zettel.page/) -- Zettelkasten - plain-text and editor-independent
* Platform: Linux, OS X and Windows (Windows support requires [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10))
* Note storage: Markdown
* Why would you choose Neuron:
  * Future-proof 
  * Open source
  * Statically generated web interface
  * Folgezettel Heterarchy
  * Built on Pandoc, with note-linking support
  * Use from command-line with any editor
  * Or, use the upcoming web app [Cerveau](https://www.cerveau.app/)

### Notion
* Video: <https://www.youtube.com/watch?v=e2tttUPGlB8>

### nvALT
* Video: <https://www.youtube.com/watch?v=jgZOMN5KfTE>

### [Passfindr](https://passfindr.com) -- Security and Productivity
* Platform: Android, Web
* Note storage: Plain Text/Rich text
* Why would you choose Passfindr:
    * Can encrypt notes
    * Plain text notes without templates. You can design each note however you wish.
    * Fast
    * Can publish notes on web

### [Org-roam](https://www.orgroam.com/) -- A plain-text personal knowledge management system

* Platform: Windows, macOS, Linux (requires Emacs)
* Note storage: Plain Text
* Why would you choose org-roam:
    - Connections, backlinks and built-in graph visualization.
    - Extensible using the Emacs ecosystem
    - [Open Source](https://github.com/org-roam/org-roam); licensed under GPL3
    - Inclusive and active community of users passionate about Personal Knowledge Management; on [Discourse](https://org-roam.discourse.group/) and [Slack](https://orgroam.slack.com/).
    - Well documented; see [the manual](https://www.orgroam.com/manual.html).

### [Roam Research](https://roamresearch.com) -- A Note taking tool for networked thought
* Platform: Web
* Note storage: Markdown
* Videos
  *  <https://www.youtube.com/watch?v=ljyo_WAJevQ>
  *  Playlist: <https://www.youtube.com/playlist?list=PLralmZwl_8jJuJMIebWFqm6K5I20a5Qve>
* Why would you choose Roam Research?
    * Top of the line in creating and following links
    * Automatic backlinks
    * Super easy creation of zettels.
    * Encourages taking Daily Notes


### [TiddlyWiki](https://tiddlywiki.com) -- A Non-linear personal web notebook
* Platform: Web browser (self-hosted)
* Note storage: Single HTML file
* Why would you choose TiddlyWiki
    * Self-hosted
    * Browser based
    * Numerous plugins
    * Can typeset math
    * Network graph for exploring notes

### The Archive
* Video: <https://www.youtube.com/watch?v=JHuuoYMsYI4>

### [Trilium Notes](https://github.com/zadam/trilium)
* Platform: Linux, Windows, OS X
* Note storage: SQLite + HTML
* Why would you use Trilium Notes?
    * Fully offline, but sync server (which is also full web app) can be setup to synchronize multiple clients
    * Strong encryption of "protected notes"
    * Auto back linking and visualization of relationships between notes
    * It's relatively easy to script the app with custom behavior
    * Automatic versioning of the notes
    * Exports to a nice directory hierarchy with MD/HTML file per note
  

### [Vim-Zettel](https://github.com/michal-h21/vim-zettel) -- Zettelkasten in VIM
* Platform: Linux, Windows, OS X, maybe others
* Note storage is plain text/markdown/wikiformat
* Why would you use Vim-Zettel?
    * If you already use Vim, this is a natural option
    * Backlink generation 
    * Fuzzy searching
    * Custom note templates and custom file naming
    * External links
    * Link verification

### Visual Studio Code

[VS Code](https://code.visualstudio.com/) can be used with certain Markdown / Zettelkasten extensions:

* [linkist](https://github.com/gladed/linkist): create persistent links between markdown documents in your workspace
* [vscode-memo](https://github.com/svsool/vscode-memo#memo): Markdown knowledge base with bidirectional links built on top of VSCode ([works with neuron](https://neuron.zettel.page/editor.html))
* [Insert Date String](https://marketplace.visualstudio.com/items?itemName=jsynowiec.vscode-insertdatestring). One can configure a customized ID (timestamp) when creating notes.
* [Markdown Notes](https://marketplace.visualstudio.com/items?itemName=kortina.vscode-markdown-notes). Another extension in the same genre of vscode-memo (see above). provides the links, backlinks, and tagging capabilities. Supports auto-completion via Intellisense. 

### [Zettlr](https://zettlr.com) -- A Markdown Editor for 21st Century
* Platform: Linux, Windows, OS X 
* Note storage: plain text/markdown
* Video: <https://www.youtube.com/watch?v=vStbtF4_grE>
* Why would you choose Zettlr?
    * Integrates with literature managers like Zotero and JabRef. Easy
      citations
    * Heatmap search
    * Good language support

## Storage Management (The Kasten)

Plain text, file system-based zettels will require some level of protection. 

### Backup
One should always backup their data. Select a mechanism for your particular operating system. For example, macOS users should include their zettels as part of the regular backup process on their machine. 

### Offsite synchronization and versioning

Option | Description
--- | ---
Cloud synchronization (e.g., OneDrive, Google Drive, Dropbox) | these provide the synchronization of data to a cloud-based server in the event of loss or theft of one's machine. 
Version control system (e.g., GitHub, GitLab, BitBucket) | These services provide offsite storage and automatic synchronization (if configured correctly). Additionally, these services provide versioning so one can track the evolution of their knowledge base. *Note: this option is probably more attractive to individuals with an IT / engineering background.*