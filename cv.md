# Vladislav Petrusevich
### Junior Software Developer

### CONTACT INFORMATION
---


Email: vladislav.petrusevich.uk@gmail.com

Linkedin:
linkedin.com/in/władysław-pietrusiewicz

Address: Warszawa, aleje Jerozolimskie 135,26

---

### SKILLS
- Communication
- Self-motivation
- Active Listening
- Quick Learning
- HTML5
- CSS3
- Javascript
- Salesforce.com
- Apex Basic
- Github
- Reading and understanding
documentation in English
- Microsoft Office
- Advanced computer skills

---
### last saved code in webstorm
```
let data = {
    "Рыбы": {
        "форель": {},
        "лосось": {}
    },

    "Деревья": {
        "Огромные": {
            "секвойя": {},
            "дуб": {}
        },
        "Цветковые": {
            "яблоня": {},
            "магнолия": {}
        }
    }
};

function createTree(container, obj) {
    container.innerHTML = createTreeText(obj);
}

function createTreeText(obj) { // отдельная рекурсивная функция
    let li = '';
    let ul;
    for (let key in obj) {
        li += '<li>' + key + createTreeText(obj[key]) + '</li>';
    }
    if (li) {
        ul = '<ul>' + li + '</ul>'
    }
    return ul || '';
}


createTree(calendar, data);
```

---

### INTERSHIPS AND COURSES
https://learn.javascript.ru/

https://www.freecodecamp.org/learn/(not finished yet)

https://www.codewars.com/users/mosk120(5kyu)

https://www.w3schools.com/

---
### Languages
- English - Upper-Intermediate
- Polish - Advanced
- Russian - Native
---


