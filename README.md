```typescript
import { Author } from '@fizasayyed';
import { Learner } from '@KevinWeekley';

// Designer 
class Stolen extends Author {
  printCredit() {
    console.log("Thank You @fizasayyed! 🙏");
  }
}

// Basic Bio Information
class Bio extends Learner {
  name      = 'Kevin Weekley';
  title     = 'Git Beginner';
  location  = 'Screen_Me_Wall';
  uptime    = '28 revolutions around the 🌍';
}

// Currently Learning
class CurrentlyLearning extends Learner {
  current = ['Rust', 'Python', 'C++'];
}

// Skills in Progress
class Skills extends Learner {
  languages = ['JavaScript', 'Python', 'HTML']; // (I swear I’m learning)
  frontend  = ['CSS', 'HTML', 'React'];
  tools     = ['Git', 'VS Code', 'Zed'];
}

// Projects
class Projects extends Learner {
  projects = [
    {
      name: 'Poorly Designed Website', // (in progress, 95% procrastination)
      description: 'Trying to build a portfolio website. Currently it’s just a blank page.',
      link: 'http://www.ummmmmm' // now where did i put the link...
    },
    {
      name: 'click click click',
      description: 'It’s a button that does something... hopefully.',
      link: 'in a directory somewhere',
    },
  ];
}

// Learning Goals
class LearningGoals extends Learner {
  goals = [
    'Stop copy-pasting code from ChatGPT',
    'Learn what the heck a closure is',
    'Make my first fully functional app (and not just “hello world”)',
  ];
}

// Achievements (Personal Milestones)
class Achievements extends Learner {
  achievements = [
    'Successfully Googled “how to open VS Code”',
    'Built a website with HTML (it was just a heading, but still counts)',
    'Got through one whole tutorial without quitting halfway',
  ];
}

// Personal Interests
class Interests extends Learner {
  hobbies = ['Exploring rabbit holes', 'Pretending to be productive', 'Eating pizza (while coding, of course)'];
  areasOfInterest = ['Rust (mostly because it sounds cool)', 'Application Development (also sounds cool)', 'Automation (Love not doing it)'];
}
