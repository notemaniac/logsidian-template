# logsidian-template
Template for Logseq and Obsidian compatible note taking system

## Usage

Download zip file from one of the followings

- [Steady and slow release](https://github.com/somidad/logsidian-template/releases/latest)
- [Nightly release](https://github.com/somidad/logsidian-template/archive/refs/heads/main.zip)

## Logseq

`logseq/config.edn`:

```edn
{
 ; Daily note filename has a form of 2023-11-07
 :journal/file-name-format "yyyy-MM-dd"
}
```
## Obsidian

`app.json`:

```json
{
  "attachmentFolderPath": "./assets",
  "userIgnoreFilters": [
    "logseq/"
  ],
  "alwaysUpdateLinks": true,
  "newFileLocation": "folder",
  "newFileFolderPath": "pages",
  "useTab": true
}
```

`daily-notes.json`:

```json
{
  "folder": "journals"
}
```
