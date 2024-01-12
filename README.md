# Last Day

Export all **Day One** entries (as markdown files) and some attachments (photos, audio, and PDFs).  

## Why

Day One is a great tool, but over time it's become less flexible for my needs. Unfortunately, the export options they provide are not very useful, if you want to transfer your notes to a different tool. 

## Dependencies

- Day One installed
- zsh
- sqlite3

## Instructions

> [!WARNING]\
> This is specific to my system you may need to tweak the script.  

1. Clone this repository.
2. Change into this repository's directory.
3. Run `gen-md`.

```sh
zsh gen-md
```

4. Go to `$HOME/.last-day`.
5. Export in `day-one-export`.
6. Profit!!!
