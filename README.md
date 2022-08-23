### 
<div style="text-align:center">
    <img src="https://i.ibb.co/Sx8cmck/13.gif" alt="13" width="70">
    <h2> Welcome to my code lab</h1>
</div>

---

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
