### Hi there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> welcome to my code lab.

<img src="https://i.ibb.co/Sx8cmck/13.gif" alt="13" width="70">

---
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="15" > main.js

````js
import Developer from './developer.js'

const Dev = new Developer()
````

<img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="15" > Human.js
````js
class Human {
    constructor(){
        this.name = 'Álex Rueda';
        this.age = 28;
        this.country = 'Spain';
        this.speaks = ['Spanish', 'English', 'German'];
    }
}
````
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="15" > Developer.js
````js
class Developer extends Human {
    constructor() {
        super();
        this.currentJob = 'Freelancer';
        this.devLangs = ['HTML', 'CSS', 'JavaScript', 'PHP'];
    }
}
````
---
