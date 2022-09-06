# Iurii Mokhovikov

## Contact information

- **Phone number:** +380 67 606 99 96
- **Email:** iurii.mokhovikov@gmail.com
- **Telegram:** https://t.me/Darth_Marr_official
- **Discord:** DarthMarr
- **GitHub:** https://github.com/DarthMarr

## About me

I am 40 years old, I work in medical laboratory as product manager. It's a good job with a good salary, but it's not what I always dreamed of. The time has come to close the biggest gestalt in my life and finally do what brings me both pleasure and a good salary.
I chose front-end because I am visual, so I need to see the result of my work - this motivates me a lot.

**Regarding my strengths:**

1. Quick learner
2. I always get things done
3. High level of soft skills
4. Team player
5. I can in time management
6. Meticulousness and perseverance

## Scils

- HTML
- CSS
- JS
- Git/GitHub

## Code Examples

```
function cakes(recipe, available) {
  let intArr = [];
  let trueArr = [];
  let recArr = Object.keys(recipe).map((key) => key);
  let isKey = recArr.filter((key) => {
    if (available.hasOwnProperty(key) == true) {
      trueArr.push(key);
    }
  });
  if (recArr.length > trueArr.length) {
    return 0;
  }
  for (let i = 0; i < trueArr.length; i++) {
    intArr.push(Math.floor(available[trueArr[i]] / recipe[trueArr[i]]));
  }
  intArr.sort();
  return intArr[0];
}
```

## Work experience:

No IT experience currently

## Education and courses:

- CSS, HTML: video course by Dmitry Valak "Fundamentals of creating sites. HTML and CSS for beginners"
- JavaScript: video course by Bogdan Stashchuk "Complete course in JavaScript" and https://learn.javascript.ru/
- Git/GitHub: video course by Bogdan Stashchuk "Complete course Git and GitHub for Beginners"

## Language:

English level - A2
