# Meeting Summary

`meeting-summary` is a Codex skill for turning a meeting transcript into a meeting summary and action items, or for cleaning handwritten and near-verbatim notes.

## Install

In Codex, run:

```text
$skill-installer Install the skill from https://github.com/alecbrockell/meeting-summary-skill/tree/main/skills/meeting-summary
```

## Use

```text
$meeting-summary '/absolute/path/to/transcript.txt'
```

You can add a modifier such as `summary only`, `only action items`, or `clean verbs`.

Supported inputs:

- Plain text and Markdown: `.txt`, `.md`
- Rich text and Word: `.rtf`, `.doc`, `.docx`
- Searchable or scanned PDF: `.pdf`
- Images and scans: `.png`, `.jpg`, `.jpeg`, `.heic`, `.tif`, `.tiff`

## License

MIT
