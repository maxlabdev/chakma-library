# Chakma Language Library
A systematic linguistic database for the Chakma language.

## Use via API

### Get all words
```http
GET https://raw.githubusercontent.com/maxlabdev/chakma-library/main/dictionary.json
```

### Get metadata and statistics
```http
GET https://raw.githubusercontent.com/maxlabdev/chakma-library/main/meta.json
```

### Get by category (nouns sample)
```http
GET https://raw.githubusercontent.com/maxlabdev/chakma-library/main/categories/nouns.json
```

## Data Structure
Each entry contains:
- `id`: Unique identifier
- `chakma_script`: Written form in native Chakma script
- `romanized`: Roman alphabet transliteration
- `english_meaning`: Meaning of the word in English
- `pronunciation`: Phonetic spelling
- `grammar_type`: Grammatical classification
- `helping_verbs`: Associated helping/auxiliary verbs if applicable
- `example`: Sentence usages containing Chakma script, romanized, and English

## Contributing
Use the mobile client app to submit entries and commit sync requests directly via the GitHub API.

## License
MIT
