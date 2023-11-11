![avatar](man.png "Stanislau Turasau")

# Turasau Stanislau

## Junior Frontend Developer

### Contacts:

- Phone: +375-29-738-13-89
- Telegram: https://t.me/stanislau_fe
- E-mail: stanislau.t7@gmail.com
- [LinkedIn](https://www.linkedin.com/in/stanislau-turasau-b527381b0/ "Stanislau on LinkedIn")

### About Myself

Hello! I am a frontend developer with practical experience in web and mobile development. I am constantly developing my technical skills. I also don’t forget about improving my English language skills. And currently I am looking for my dream team.

### Skills

- HTML / CSS / Javascript
- Typescript
- React
- React Native
- Redux
- MobX
- Git
- Agile methodology

### Code Example

Range Extraction KATA from Codewars:
A format for expressing an ordered list of integers is to use a comma separated list of either.

- individual integers
- or a range of integers denoted by the starting integer separated from the end integer in the range by a dash, '-'. The range includes all integers in the interval including both endpoints. It is not considered a range unless it spans at least 3 numbers. For example "12,13,15-17"

Complete the solution so that it takes a list of integers in increasing order and returns a correctly formatted string in the range format.

```
function solution(list){
  let duration = 0;

  return list
    .reduce((prev, cur, i, arr) => {
      duration = arr[i] === arr[i + 1] - 1 ? duration + 1 : 0;

      if (duration > 1) return `${prev.slice(0, -1)}-`;

      return `${prev}${cur},`;
    }, "")
    .slice(0, -1);
}
```

### Courses

I have successfully completed EPAM's external JS training, as well as EPAM JS Lab.

### Languages

English level - B1 (EPAM assessment)
