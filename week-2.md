## Week challenges (Tuesday) 💻
1. 
```javascript
function multiply(a, b){
  return a * b
}
```
2. 
```javascript
function uniTotal(str) {
  var count = 0;
  for (var i = 0; i < str.length; i++) {
    count += str.charCodeAt(i);
  }
  return count;
}
```
3. 
```javascript
function getChar(c){
return c = String.fromCharCode(c);
```
4. 
```javascript
function addBinary(a,b) {
  sum = a + b
  return sum.toString(2);
}
```
5. 
```javascript
function finalGrade (exam, projects) {
  if (exam > 90 || projects > 10){
    return 100;
  }
  else if (exam > 75 && projects >= 5){
    return 90;
  }
  else if (exam > 50 && projects >= 2){
    return 75;
  }
  else {
    return 0
  }
}
```