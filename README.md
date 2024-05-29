# Hi! Nice to meet you👋
## I'm currently studying web development

**what am I studying now?**
1. next js
2. react
3. deep js
4. start TypeScript


### **My skills**
|skill|ownership percentage|
|-|--------|
|react|20%|
|html|70%|
|css|70%|
|js|45%|
|vue js|40%|
|gulp|50%|


### Coolness?
1. Every day I learn something new
	> Regularity is the only secret of success!
2. Communication?
  > You don't have to understand every person! You can either accept it or not.
3. Relaxation?
  > Maybe there is no point in straining?


###### We'll see you again 😉

> Today I’ll write down a thought here... I wonder if it’s true that if you do something every day for 30-60 minutes for several years, a person will easily achieve success in this matter...

> A funny day... I practiced English, comprehended some unthinkable things, and of course practice writing code. The Internet just isn't buzzing today... if nothing happened, where would you be?

### Good evening! There will be no access to a computer for a couple of days, but we will not stop studying and repeating. These days I’ll add here the points that I’ll study, and maybe a couple of ideas!
1. Today we remembered prototypical inheritance in JS. Yes, quite a useful technology. It’s cool that there is extensibility... of course, don’t forget that today I read a book in English and repeated the words. Quite a productive day combined with active recreation! Good night😋
2. Good evening! Today we discussed the topic of working with memory when using methods and prototypes in a constructor. Yes, it is useful to remember such information. And
 it will even be useful to me! p.s. I'll attach some code for fun.

Kind! So the Internet was turned off. I wrote the code today. I remembered the basics of react-query. Maybe it's time to put together a good portfolio, design it beautifully. In general, I want to swear harshly
```

function Character(name, health) {
  this.name = name;
  this.health = health;
}

Character.prototype.greet = function() {
  console.log("Привет! Меня зовут " + this.name + ".");
};

let characters = [];

for (let i = 0; i < 100; i++) {
  characters.push(new Character(`Character ${i}`, 100));
}

console.log(characters);
```

3. Great evening! Today we repeat the dynamic update. I’m writing a little late, but of course I don’t forget about studying. Think about the difference between discipline and motivation😋

4. Hello! We continue to study the advantages of prototypes. Today, flexibility and modularity are the order of the day. In general, take a look at the example ✌️

```
function Mage(name, health, spell) {
  Character.call(this, name, health);
  this.spell = spell;
}

Mage.prototype = Object.create(Character.prototype);
Mage.prototype.constructor = Mage;

Mage.prototype.castSpell = function(target) {
  console.log(this.name + " произносит заклинание " + this.spell + " на " + target + ".");
};

let mage = new Mage("Маг", 80, "Огненный шар");

mage.attack("Монстр");  
mage.castSpell("Враг");
```

5. Great day! Tomorrow I will move on to more difficult practice. We will write code using object prototypes. I think I'll be able to post the sketches tomorrow. Just like that... Should I take care of business? Have a nice evening, buddy💪

6. Cool day! Today I mostly rested and practiced. Repeated Vue js. We were talking about styles and classes. Back to code tomorrow! Good luck guys ✌️
7. Interesting day! Lots of interesting experiences. It is worth thinking about hardness and softness. What is better at a distance...
8. Anger! Force! Breaking point... To be reborn, you must die...
9. It's a great day! Played a mind game. Good progress😁 Repeated Vue Js a bit. Tomorrow to coding. Have a nice weekend!
10. 

> ¡Buenas noches niños y niñas! Hoy se apagó Internet, así que actualicé un poco la teoría. Mañana editaré este archivo si vuelve Internet😋 Por cierto, tengo algunas noticias y pensamientos interesantes😁 ¡Quizás incluso los veas aquí algún día!


> Today I was working on connecting to the Internet. It should be done the day after tomorrow, then I’ll push it to the repository. I write code little by little, more to maintain knowledge. We need to think and decide, continue writing code and start working on something interesting. Or shift your focus to another area. Just questions, just solutions... I don’t really feel like swearing today 😋
> Hey! Refreshing my knowledge of css and html. Tomorrow there will be Internet. There are, of course, questions about the relevance of all this. I think I'll take a closer look at typescript. Okay, we'll see tomorrow. Good evening!

<!--
**LikeKod/LikeKod** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
