class Person {
  constructor({ firstName, lastName, age, gender, interests }) {
    this.firstName = firstName;
    this.lastName = lastName;
    this.age = age;
    this.gender = gender;
    this.interests = interests;
    this.bio = `${this.firstName} ${this.lastName} is ${this.age} years old. They like ${this.interests}`;
  }

  bio() {
    return this.bio;
  }

  greeting() {
    return `Hi! I'm ${this.firstName} ${this.lastName}!`;
  }
}

class Teacher extends Person {
  constructor({ firstName, lastName, age, gender, interests, subject }) {
    super({ firstName, lastName, age, gender, interests });
    this.subject = subject;
  }

  bio() {
    super.bio();
  }

  greeting() {
    return `Hello. My name is ${this.lastName}, and I teach ${this.subject}.`;
  }
}

class Student extends Person {
  constructor({ firstName, lastName, age, gender, interests }) {
    super({ firstName, lastName, age, gender, interests });
  }

  greeting() {
    return `Yo! My name is ${this.firstName} ${this.lastName}.`;
  }
}
