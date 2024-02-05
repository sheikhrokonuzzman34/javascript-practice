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


## Using a for lop:

```javascript

    var i;
    for(i=0; i<10; i= i+1 ){
        document.write( i+ "<button>submit</button> <br/>");
    }
```
## using a for lop Break Continue:

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

