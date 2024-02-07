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




