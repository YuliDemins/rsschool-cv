# My CV

## **Yulia Demina**

### My Contact Info:

- **Phone**: +79000000000
- **email**: yudemina@mail.ru
- **GitHub**: YuliDemins

### About Me:

I am 35 years old, I work an accountant. I want to get new knowledge, interesting projects and new life

### Skills:

- HTML
- CSS (SASS/SCSS, BEM)
- Gulp
- JS (in progress)
- Git/GitHub
- Photoshop, Figma, Avocode
- VSCode

### Education:

1. **Higher Education** - National Research Lobachevsky State University of Nizhni Novgorod

2. JS, CSS, HTML, Git video courses on YouTube channel Glo Academy,
   JavaScript https://learn.javascript.ru/

### Code example

By clicking the mouse, you can select the number of rating stars then use this number

```
const ratingItemsList = document.querySelectorAll('.rating__item');

const ratingItemsArray = Array.prototype.slice.call(ratingItemsList);

ratingItemsArray.forEach(item =>
    item.addEventListener('click', () => {
    const { itemValue } = item.dataset;
    item.parentNode.dataset.totalValue = itemValue
    console.log(itemValue)
})
    );
```

### Languages:

- Russian - native speacker
- English - A2 (B1 in progress)
