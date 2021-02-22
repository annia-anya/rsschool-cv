# [RS-school](https://github.com/annia-anya/rsschool-cv/cv)
________________


## Hanna Shatsko
![N|Solid](./assets/elitefon.ru_17023.jpg)
________________

## Contact Info
- telegram: link to [telegram](https://t.me/annia_anya)
- skype: link to [skype](https://join.skype.com/invite/liKjy4KiEpmJ)
- GitHub: link to [GitHub](https://github.com/annia-anya)

________________
## Skills
- HTML5/CSS3
- Javascript (beginner level)
- Git (beginner level)
- Java (skills related to automated testing)
- functional, regression, exploratory, API testing
- creation of documentation (Jira, Confluence experience)
- requirements analysis
________________
## Code example
```js
function withCheckEmpty(fn) {
    return (array) => {
        if (!array || array.length === 0) {
            return 0;
        }
        return fn(array);
    }
}

exports.min = withCheckEmpty(function(array) {
  let currentMin = array[0];
  for (let i = 1; i < array.length; i++) {
      if(array[i] < currentMin){
          currentMin = array[i];
      }
  }
  return currentMin;
});

exports.max = withCheckEmpty(function(array) {
    let currentMax = array[0];
    for (let i = 1; i < array.length; i++) {
        if(array[i] > currentMax){
            currentMax = array[i];
        }
    }
    return currentMax;
  })

exports.avg = withCheckEmpty(function(array) {
  const length = array.length;
  let sum = 0;
//   let sum = array.reduce((result, item) => result + item, 0);

  for(let i = 0; i < array.length; i++) {
      sum += array[i];
  }
  return sum / length;
  // return array.reduce((result, item) => result + item, 0) / array.length;
})


```

## Experience
Currently no working experience as a frontend engineer. Two and a half year working experience as a Software Testing Engineer. 
________________
## Education
- 2014-2019 BSU, Faculty of Philology (Bachelor)
- 2019 QATestLab EPAM Training Center
- 2019-2021 BSU, Faculty of Philosophy and Social Science (Master of Psychology)

__________________
## Language skills
- Russian: native
- English: B1
- German: B1




