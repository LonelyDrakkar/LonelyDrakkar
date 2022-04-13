### Hello you! 🌎

## This is Mario Jaque. ✈️

```js
class LonelyDrakkar extends Human{
  constructor(){
    super();
    this.name = 'Mario Jaque';
    this.age = 20;
    this.pronouns = 'he' | 'him';
    this.higherEducation = 'Aircraft Maintenance Technician - Last year';
    this.currentOccupation: 'Last year student open for job opportunities',
    this.lookingForJob = true;
    this.workingHours = 'Full time';
  }
  
  getCurrentGoals(){
    return [
      'Finish my Aircraft Maintenance Technician Degree',
      'Create my own web portfolio',
      'Get a job to gain more experience as a Web Developer',
    ];
  }
  
  getCurrentChallenges(){
    return [
      'Improving my CV with some education apart from my University',
      'Coding or study everyday',
      'Waking up earlier to make good use of my day',
      'Create several projects for my web portfolio (Coming Soon)',
    ];
  }
  
  getKnowledges(){
    return {
      technologies: {
        frontEnd: {
          languages: ['JavaScript', 'HTML5', 'CSS3'],
          frameworks: ['React', 'Vue.js'],
        },
        backEnd: {
          languages: ['PHP'],
          frameworks: ['Laravel'],
        },
        databases: ['mySQL', 'mariaDB'],
        IDEs: ['VS Code', 'PhpStorm', 'Sublime Text', 'Notepad++'],
        os: ['Ubuntu', 'Windows'],
        other: ['Git', 'GitHub'],
      },
      englishLevel: 'C1',
    };
  }
}

const AboutMe = new LonelyDrakkar();
```
