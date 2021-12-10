# Requirements
**This repo is based on [tatupesonen/aoc-typescript-starter](https://github.com/tatupesonen/aoc-typescript-starter)**

## Setup
```
npm install
```
You also need to create a `.env` file at project root with the contents of:
`SESSION_COOKIE=your advent-of-code session cookie`

## Usage
Let's say you want to create the project structure for 2020's day 1 challenge. To scaffold the project, get input & README, you would run:
```
npm start create 2020 1
```

To run the challenge, you would run:
```
npm start run 2020 1
```

## Improvements
- [ ] Day folders should be zero-padded to two digits, so sorting will always occur the same
- [ ] Allow for processing test files as `test#.txt`
- [ ] Improve ESLint settings (remove JsDoc require etc.)
