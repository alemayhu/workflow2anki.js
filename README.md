# workflowy2anki.js

JavaScript library for converting Workflowy outlines to Anki Flashcards.

## Usage

We currently only support the plain text outlines and hopefully more to come soon. This project produces the
following structure you can use

```js
// data is the plain text
const reader = new DeckReader();
const decks = reader.readText(data);
```

### Format

```json
[
  {
    "name": "Deck Name",
    "cards": [{ "front": "", "back": "" }]
  }
]
```

## RoadMap

- [x] Plain text
- [ ] OPML
- [ ] HTML

## Development

Make sure to update [test.js](./test.js)

```bash
npm run tt
```
