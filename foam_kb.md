# Foam Knowledge Base Standards / Tutorials
## Foam Features
### Graph Visualisation
Execute: `Foam: Show Graph`

### Backlinking
- Link to other notes with ``[[FILENAME]]``
- Link to other notes sections with `[[FILENAME#section title]]`

### Creating new notes
- Write out a new ``[[wikilink]]`` and Cmd + Click to create a new file and enter it. 
- `Cmd` + `Shift` + `P` (`Ctrl` + `Shift` + `P` for Windows), execute `Foam: Create New Note` and enter a **Title Case Name** to create `Title Case Name.md`

### tags
- adding a ``#tag`` anywhere in the text of the note
- using the ``tags: tag1, tag2`` property in frontmatter
- Tags can also be hierarchical, so you can have #parent/child

### Note templates
#### Current templates
[[basic_note_template]]
[[journal_template]]

### Include note in a note
`![[wikilink]]`

## Rules
- All technical stuff should moved to a specific repository.


## Extensions
- mushan.vscode-paste-image
- skn0tt.markdown-link-expander
- markdown pdf

## Other stuff
### Make files public
To make files public add the speific file to [.github/sync.yml](.github/sync.yml) and let the pipeline run.

