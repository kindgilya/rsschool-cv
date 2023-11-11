# Elena Davydova

---

_Location:_ Yekaterinburg  
_Mobile phone:_ +79193986465  
_E-mail:_ ed41658@gmail.com  
_Github:_ https://github.com/kindgilya  
_Telegram:_ @kindgilya

## About me

A Front-End Developer with entry-level experience specializing in web development, user HTML, CSS and JavaScript. I want to get the job, where I'll improve my skills.

## Skills

- HTML & CSS
- JavaScript
- DashaScript
- Git
- SQL

## Education

**2017 - Ural Federal Univercity Ph.B.**  
**2023 - "JavaScript/DOM/Intarfaces course" javascript.info**  
**2023 - "Intensive of JS fundamentals" maths-h.com**

## Code examples

```javascript
const result = workers
  .filter(
    (worker) =>
      worker.age > 21 &&
      (worker.department === "programmer" ||
        worker.department === "designer") &&
      worker.role === "middle" &&
      worker.children
  )
  .map((worker) => {
    const sumSalary = worker.salary.reduce((acc, el) => acc + el, 0);
    return {
      ...worker,
      sumSalary: sumSalary < 300000 ? sumSalary + 5000 : sumSalary,
      modify: sumSalary < 300000,
    };
  })
  .reduce(
    (acc, worker) => {
      return {
        ...acc,
        names: [...acc.names, worker.name],
        workersCount: acc.workersCount + 1,
      };
    },
    { names: [], workersCount: 0 }
  );
console.log(result);
```

## Experience

**september 2023 - now "Sales Control Center", Moscow**  
 _junior developer_

- traine AI voice bots using DashaScript and Node.js;
- help the development department with their routine tasks;

