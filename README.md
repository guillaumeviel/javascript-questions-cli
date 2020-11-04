# JavaScript Questions Random CLI

Takes questions from [lydiahallie/javascript-questions](https://github.com/lydiahallie/javascript-questions) and starts a randomized quiz in your terminal. The quiz will randomly pick questions among the ones that haven't been answered correctly yet. You can stop whenever you want, your progress can be saved and resumed next time.

Based on the work from Nicolas Chambrier: [naholyr/javascript-questions-cli](https://github.com/naholyr/javascript-questions-cli)

## Usage

```sh
npx javascript-questions-random-cli [lang]
```

![javascript-questions-cli](https://raw.githubusercontent.com/naholyr/javascript-questions-cli/master/screenshot.png)

### Supported languages:

- `en` (default)
- `ru`
- `vi`
- `bz`
- `de`
- `cz` should be supported as it's contributed in `lydiahallie`'s repository, but in current version there are issues parsing the Markdown for this language

Please note that not all languages have the same set of questions, the reference is `en`.
