# Projects related to DOM

## project link
[Click here]([https://](https://stackblitz.com/edit/dom-project-chaiaurcode?file=1-colorChanger%2Findex.html)https://stackblitz.com/edit/dom-project-chaiaurcode?file=1-colorChanger%2Findex.html)

# Solution code

## project 1

```javascript
console.log("Mijbah")

const body = document.body;
const button = document.querySelectorAll('.button');
button.forEach(function (btn) {
  btn.addEventListener('click', function (e) {
    if (e.target.id === 'grey') {
      body.style.backgroundColor = e.target.id;
      body.style.color = 'white';
    }
    if (e.target.id === 'white') {
      body.style.backgroundColor = e.target.id;
      body.style.color = 'black';
    }
    if (e.target.id === 'blue') {
      body.style.backgroundColor = e.target.id;
      body.style.color = 'white';
    }
    if (e.target.id === 'yellow') {
      body.style.backgroundColor = e.target.id;
      body.style.color = 'black';
    }
    if (e.target.id === 'purple') {
      body.style.backgroundColor = e.target.id;
      body.style.color = 'white';
    }
  });
});


```