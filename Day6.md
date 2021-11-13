# Day reading Notes

> ## ~~JavaScript~~ 

- *is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else.*

  * *an example we can see is by creating a button that is interactive. see below:*

  HTML  - < p> Player 1: Chris < /p>

 > <p>Player 1: Chris</p>

 With CSS - 
 p {
  font-family: 'helvetica neue', helvetica, sans-serif;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-align: center;
  border: 2px solid rgba(0,0,200,0.6);
  background: rgba(0,0,200,0.3);
  color: rgba(0,0,200,0.6);
  box-shadow: 1px 1px 2px rgba(0,0,200,0.4);
  border-radius: 10px;
  padding: 3px 10px;
  display: inline-block;
  cursor: pointer;
}

![button](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript/html-and-css.png)

- Applying *JS* to this button -

const para = document.querySelector('p');

para.addEventListener('click', updateName);

function updateName() {
  let name = prompt('Enter a new name');
  para.textContent = 'Player 1: ' + name;

  Will allow you to click on the buttun and rename the Player.

  
  
