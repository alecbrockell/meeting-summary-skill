# Meeting Summary

`meeting-summary` is a Codex skill for turning one local meeting record into a meeting summary and action items, or for cleaning handwritten and near-verbatim notes.

The skill treats the supplied material as a closed record by default. It keeps the source file unchanged, does not follow embedded links, and does not upload meeting content or use external transcription or OCR services. Audio and video transcription are outside its scope.

## Install

In Codex, run:

```text
$skill-installer Install the skill from https://github.com/alecbrockell/meeting-summary-skill/tree/main/skills/meeting-summary
```

The installed skill is available on the next turn. If it does not appear, restart Codex.

## Use

```text
$meeting-summary '/absolute/path/to/transcript.txt'
```

You can add a modifier such as `summary only`, `only action items`, or `clean the verbatims`.

Supported inputs:

- Plain text and Markdown: `.txt`, `.md`
- Rich text and Word: `.rtf`, `.doc`, `.docx`
- Searchable or scanned PDF: `.pdf`
- Images and scans: `.png`, `.jpg`, `.jpeg`, `.heic`, `.tif`, `.tiff`

Local extraction or OCR support depends on the tools available in the Codex environment. The skill asks for a converted supported file if local extraction fails.

## License

MIT
