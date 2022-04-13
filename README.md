### Hello you

```jsx
import React, {Component} from 'react';

export default class LonelyDrakkar extends Component{
  constructor(){
    super();
    this.state = {
      studying: true,
      looking-for-a-job: true,
      working-hours: 'Full time',
      ready-to-learn-more: true,
    }
    
    render(){
      return(
        <article>
          <header>
            <h2>About me:</h2>
          </header>
          <p>Hi! I'm Mario and I'm a full-stack web developer. I'm currently finishing my Aircraft Maintenance Technician degree at UTFSM University.</p>
          <h3>I'm working on</h3>
          <ul>
            <li>Taking online courses about new web development technologies</li>
            <li>Get a job to gain more experiencie as a web developer</li>
            <li>Create my own web portfolio</li>
          </ul>
          <h3>I'm challenging myself with:</h3>
          <ul>
            <li>Create several web projects to add on my web portfolio (Coming soon)</li>
            <li>Exercising 5 days a week</li>
            <li>Imrpoving my CV with some education apart from university</li>
            <li>Waking up earlier to make good use of my day</li>
          </ul>
          <h3>Programming languages:</h3>
          <ul>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>Python</li>
            <li>C++</li>
            <li>C#</li>
            <li>Lua</li>
          </ul>
          <h4>Other languages:</h4>
          <ul>
            <li>HTML5</li>
            <li>CSS3</li>
          </ul>
          <h3>Frameworks:</h3>
          <ul>
            <li>React</li>
            <li>Laravel</li>
          </ul>
        </article>
      );
    }
}
```
