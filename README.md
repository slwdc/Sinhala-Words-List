Sinhala Words List
==================

A list of words in Sinhalese language, sorted by alphabetical order. 

## Format
The list of words is trimmed, and stored in a flat text file `si.txt`. Each word is separate by a new line character `\n`. 

An additional `package.json` is provided to ease updating the list. 

## Installation
`npm install --save sinhala-words`

## Usage
For Node-based projects, you can use this words list by splitting the list of words by `\n` new line character. 
```javascript
const fs = require('fs');

// Get path to the words list.
onst sinhala_words_path= require('word-list');

const sinhala_words= fs.readFileSync(sinhala_words_path, 'utf8').split('\n');
// ['අභිචෝදකයා', 'අංකනය', 'අංකන', ...]
```