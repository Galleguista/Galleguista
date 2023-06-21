```javascript
class SoftwareEngineer {
  constructor() {
    this.name = "Juan David Gallego";
    this.role = "Software Engineer";
    this.language_spoken = ["es_CO"];
    this.code = [
      "Python",
      "JavaScript",
      "TypeScript",
      "Frontend",
      "Others"
    ];
    this.tools = ["Angular", "AWS", "NestJS", "Others"]
    this.interests = [
      "Learning",
      "Programming",
      "Tech",
      "Startups",
      "Best Practices",
      "AWS"
    ];
    this.challenge = "Learn advanced backend";
  }

  sayHi() {
    console.log("Thank you for visiting my profile");
  }
}

const me = new SoftwareEngineer();
me.sayHi();
```
