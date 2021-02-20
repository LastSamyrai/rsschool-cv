# Ivan KOSIURA

* Contacts
    * Phone: +38 093 688 27 22
    * Email: last1samyrai@gmail.com
* Tech skills
    * HTML5
    * CSS
    * JavaScript
    * GIT
* Soft Skills
    * Teamwork
* Languages
    * Ukrainian and Russian – Native
    * English - Elementary

### About me    
My goal is to become a **Front-End Developer**!!!
*I will do my best to achieve my goal*.

### Code examples

Given an array of numbers. Find a product of all positive elements in this array and divide it by the sum of all positive elements.:

```
function exercise(arr){
  let positiveArr = [];
    arr.forEach(function(item) {
      if(item>0){
        positiveArr.push(item);
      }
    });
    let result1 = 0;
    for (let i = 0; i < positiveArr.length; i++) {
      result1 += positiveArr[i];
    };
    let result2 = 1;
    for (let i = 0; i < positiveArr.length; i++) {
      result2 *= positiveArr[i];
    };
    
  let result = result2/result1;
  return result;
};

console.log(exercise([1, 8, 9]));
4 

console.log(exercise([-1, 18, -10, 3]));
2,571428571428571
```

### Work Experience

In progress *my repositories* https://github.com/LastSamyrai?tab=repositories

### Education

National Technical University of Ukraine “Igor Sikorsky Kyiv Polytechnic Institute”

Faculty of Radio Engineering
Septermber 2008 - June 2013
