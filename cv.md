![Mariya Ivanova](img/photo.jpg)

## _Mariya Ivanova_

### _Contacts_

Phone number: _+7 (916) 127-54-38_
Email: _marie555iv@gmail.com_
Discord: _Mariya#1216_
GitHub: _IvMarie_

### _Summary_

My goal is to obtain a position as a Front-end Developer. I have no experience in this area, before that I worked for a long time in the production and sale of garments. I was interested in web development and decided to change my specialization. At the moment I am engaged in self-education and taking online courses on the front-end. I am self-motivated, diverse, diligent person.

### _Professional Skills_

- HTML/CSS
- JavaScript
- Git

### _Code Examples_

```js
//The function that takes a string of words and returns the length of the shortest word(s).

function findShort(s) {
  let arr = s.split(" ").map((item) => item.length);
  return Math.min(...arr);
}
```

```js
//The method that takes a sequence of objects with two keys each (country or state, and capital) and returns an array of sentences declaring the state or country and its capital.

function capital(capitals) {
  let result = capitals.map((item) => {
    let newMap = new Map(Object.entries(item));
    return `The capital of ${
      newMap.get("country") || newMap.get("state")
    } is ${newMap.get("capital")}`;
  });
  return result;
}
```

### _Experience_

### _Education_

Specialist Degree:
_Saratov state technical university (SSTU), department of Light industry product design, Technical Garments Design, 2004-2009_

Professional retraining program:
_Voronezh institute of high technologies (VIHT), Software testing, 2021_

### _Languages_

Russian - Native
English - A2
German - A1
