Orphan notes are listed here using Obisidna Dataview plugin.

⚠️ Note that if a note contains an image, it is treated to have an outgoing link and not to be an orphan note.

Refences: https://forum.obsidian.md/t/find-orphan-notes/817/16

## Orphan notes

```dataview
list
from "pages" or "journals"
where length(file.inlinks) =0 and length(file.outlinks) = 0 and length(file.tags) = 0
```

