# Shulhan Andrei

- **telegram**: [@shulhan](http:/t.me/shulhan)
- **mail**: shulhan-dev@gmail.com

## Summary

Hi, my name is Andrey Shulgan and I am a beginner front-end developer. I want, with the help of your course, to structure the training and, after my passion, to translate into a full-fledged work.

## Skills

- HTML
- CSS, SASS
- БЭМ
- JS, JQUERY
- GULP
- GIT
- React

## Code examples

```sh
export default (str) => {
  let acc = 0;
  for (let i = 0; i < str.length; i += 1) {
    const symbol = str[i];
    acc = symbol === '(' ? acc + 1 : acc - 1;
    if (acc < 0) {
      return false;
    }
  }
  return acc === 0;
};
```
