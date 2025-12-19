# README: North & Hillard Latin Prose Composition

The transcribed document derives from [archive.org](https://archive.org/details/north-m.-hilladr-a.-latin-prose-composition-1913/page/n1/mode/1up).

## Description

### Special Vocabularies

`special_vocabularies.md` is a Markdown transcription of the Special Vocabularies at pages 204 to 238.

The Markdown file is organised by Exercise (a h2 heading) with a list of vocabulary items for each exercise in English, following by the Latin. The various notes are preserved, though errors in the text have been corrected where identified.

## Workflow

```
sed -i "s/^Exercise/## Exercise/" special_vocabularies.md
sed -i '/^[#]/b; /^[[:space:]]*$/b; s/^/- /' special_vocabularies.md
```

Replace "- - " with "- "
