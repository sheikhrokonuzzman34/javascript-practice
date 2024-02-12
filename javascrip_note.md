## Using if, else if & else: 

```javascript
var marks = 100;

    if (marks >= 80 && marks <= 100) {
        document.write('A+');
    }
    else if (marks >= 70) {
        document.write('A');
    }
    else if (marks >= 60) {
        document.write('A-');
    }
    else if (marks >= 33) {
        document.write('Pass');
    } 

    else{
        document.write('F');
    }
```



## Using a switch case:

```javascript
var marks = 32;
    var grade;

    switch (true) {
        case (marks >= 80 && marks <= 100):
            grade = 'A+';
            break;
        case (marks >= 70):
            grade = 'A';
            break;
        case (marks >= 60):
            grade = 'A-';
            break;
        case (marks >= 33):
            grade = 'Pass';
            break;
        default:
            grade = 'F';
    }

    document.write(grade); 
```


## Using a for loop:

```javascript

    var i;
    for(i=0; i<10; i= i+1 ){
        document.write( i+ "<button>submit</button> <br/>");
    }
```
## using a for loop Break Continue:

```javascript
    var i;
    for(i=0; i<10; i= i+1 ){
                                                                   
        if(i==3 || i==5){
            continue
        }
        else if (i==9){
            break;
        }
        document.write( i+ "<button>submit</button> <br/>");
    }
```
## for loop vs while loop

```javascript
        var i;
        for (i = 0; i < 4; i++) {
            document.write(i + "<button>For Loop</button> <br/>");
        }


        ________________________________________________________________________________

        var i = 0;
        while (i < 3) {
            document.write(i + "<button>While Loop</button> <br/>");
            i++;
        }

    _______________________________________________________________________________________
        var i = 0;
        do{
            document.write(i + "<button>Do while Loop</button> <br/>");
            i++;
        }while(i<3)
``` 

## Here (===) is equal because checks for  value and data type
## Here (==) is equal  checks for only value 
```javascript
if(i==5){
    continue
    }  

if(i===5){
    continue
    }  
```


## Using function 

```javascript
 function addNumber() {
    var x = 10;
    var y = 10;
    var z = 10;
  
    var sum = x + y + z;
    document.write(sum); 
  }
  
  // Call the function once:
  addNumber();
```


## Using function parameter 

```javascript

function addNumber(x, y,z) {
  
    var sum = x + y + z;
    document.write(sum); 
  }
  
  // Call the function once:
  addNumber(10,15,7);

```

## Using Returen function

```javascript

function addNumber(x, y, z) {
    return x + y + z;
    }
    
    var result = addNumber(10, 15, 7) + 100;  
    document.write(result);
```


## Using JavaScript Object

## Dictionaries data type in Python programming language and object data type in JavaScript are same

```javascript

const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};

document.write(person ["firstName"]);
// or
document.write(person.lastName);


```

## Using JavaScript Array
## javascript array type in Python  list type same 

```javascript
    var myArray = [10, "hello", true, { name: "Alice" }, [1, 2, 3]];
     // Access the name property directly within the object   
    document.write(myArray[3].name);

```

## Using JavaScript Array  in for looping

```javascript
        var myArray = [10, "hello", true, [1, 2, 3]];
         
        var i;
        for (i = 0; i <myArray.length; i++) {
            document.write(myArray[i]+"<br/>");
        }
```

## Using JavaScript Array in foring loop

```javascript
        var myArray = [10, "hello", true, [1, 2, 3]];
         
        for(var item in myArray) {
            document.write(myArray[item] + "<br/>");
        }
```
## python list and javascript arrays for looping & foring loop same only send text different
```python
mylist = [10, "hello", True, [1, 2, 3]]

for item in mylist:
    print(item)

```

## Using JavaScript Object in foring loop

```javascript
        var person = {
                    firstName: "John",
                    lastName: "Doe",
                    age: 30,
                };
          
          for (const key in person) {
            var value = person[key];
            document.write(person[key] + '<br>');
          }
```
## python dict and javascript object for looping & foring loop same only send text different


```py
fruits = {"apple": 1, "banana": 2, "orange": 3}

for key in fruits:
  value = fruits[key]
  print(f"{key}: {value}")
```

## javascript string teke array conbart

```javascript
        var title = 'lorem ipsum dolor sit am'
        var titlearray = Array.from(title);

        document.write(titlearray[6])
```

## javascript array filter used

```javascript
        var numberarry = [10,20,30,40,50,60,70,80,100,]

       var result = numberarry.filter(function(item){
          return item > 50
        });

        document.write(result);
```

## javascript array find method used
## find method jader sathe match kore teder mode sorbo nimno index print kore
## findIndex method jader sathe match kore teder mode sorbo nimno index print kore

```javascript

    var numberarry = [10,20,30,40,50,60,70,80,100,]

       var result1 = numberarry.find(function(item){
          return item > 50
        });
       var result2 = numberarry.findIndex(function(item){
          return item < 50
        });

        document.write(result1);
        document.write(result2);

```

## javscript forEach method for loop ar moti kaj kore

```javascript

    var numberarry = [10,20,30,40,50,60,70,80,100,]

    numberarry.forEach(function(item){
       document.write(item + '<br/>');
         
       });

```

## javscript include method array vitor oi velo ache ki na check kore
## javscript indexOf method array vitor oi velo thakle tar index return kor be na pele -1 returen kore

```javascript
    var numberarry = [10,20,30,40,50,60,70,80,100,]

      result=numberarry.includes(60);
       document.write(result);

    var numberarry = [10,20,30,40,50,60,70,80,100,]

      result=numberarry.indexOf(60);
       document.write(result);   
```
## Array Pop Push Reverse
```javascript

var numberarry = [10,20,30,40,50,60,70,80,100,]

      result=numberarry.Pop(60);
       document.write(result);

```
## Array slice,sort  method used
```javascript

    var numberarry = [10,20,30,40,50,60,70,80,100,]

      result=numberarry.slice(0,5);
      result1=numberarry.slice().reverse();
       document.write(result,'<br>');
       document.write(result1);

```

## Array splice method used

```javascript

    var numberarry = [10, 20, 30, 40, 50, 60, 70, 80, 100]; 
      // numberarry.splice (index,removecount,item)
      numberarry.splice(2, 1, 59); 
      document.write(numberarry); 
```

## using window methods

```html
    <button onclick="objectalert()" >alert</button>
    <button onclick="objectonfirm()" >confirm</button>
    <button onclick="objectonfirm()" >prompt</button>
    <button onclick="objectopen()" >open</button>
    <button onclick="objectclose()" >close</button>
```

```javascript

    <script>
      function objectalert() {
        alert(" Save Success ");
      }
      // confirm method true or false returns kore
      function objectonfirm() {
       let result = confirm(" Do you want to Delete");
       document.write(result);
      }

      // prompt method user input nite pare
      function objectonfirm() {
       let result = prompt("Write Your Name");
       document.write(result);
      }

      function objectopen() {
        open()
      }
      // current tap close hoye jabe close method 
      function objectclose() {
        close()
      }
     
  
    </script>
```


## used natively methods

```javascript

    var appcodename = navigator.appCodeName;
     var appname = navigator.appName;
     var appversion = navigator.appVersion;
     var cookieEnabled = navigator.cookieEnabled;
     var language = navigator.language;
     var userAgent = navigator.userAgent;
     var platform = navigator.platform;

     document.write(appcodename + '<br/>')
     document.write(appname + '<br/>')
     document.write(appversion + '<br/>')
     document.write(cookieEnabled + '<br/>')
     document.write(language + '<br/>')
     document.write(userAgent + '<br/>')
     document.write(platform + '<br/>')

```

## Used window methods

```html
<button onclick="myFunction('click hoyce')" >onclick</button>
    <button onmouseover="myFunction('onclick')" >onmouseover</button>
    <button onmouseout="myFunction('onmouseout')" >onmouseout</button> <br> <br>


    <input onchange="myFunction('onchange')" >onchange <br/>
    <input onkeydown="myFunction('onkeydown')" >onkeydown <br/>
    <input onkeyup="myFunction('onkeyup')" >onkeyup <br/>




    
    <script>
      
     function myFunction(msg) {
        console.log(msg);}
    </script>
```




