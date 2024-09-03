## 1. Write short notes on Array methods with code example

## push() -

Ans : Adds an element to the end of the array

```js

let arr=[1,2,3,4,5]
let newArr =arr.push("six")
console.log(newArr);

```


## pop() -

Ans : Remove the last element of the array

```js

let arr=[1,2,3,4,5]
arr.pop()
console.log(arr);

```


## shift() -

Ans : Remove the first element from the array

```js

let arr=["apple","cherry","grapes","guva","mango","orange"]
arr.shift()
console.log(arr);

```


## unshift() -

Ans :  Add an element to the begin of an array

```js

 let arr=[1,2,3,4,5]
 arr.unshift("six")
 console.log(arr);

```

## includes() -

Ans : check if a particular element included in the array

```js

   let arr=[1,2,3,4,5]
   console.log(arr.includes(7));

```



## toString() -

Ans : return a string with array values sepparated by coma

```js

let arr=["apple","orange","grapes"]
let str=arr.toString()
console.log(typeof (str));

```



## reverse() -

Ans : Revesed all of the elements in the array

```js

let arr=["apple","orange","mamgo"]
console.log(arr.reverse());


```


## join() -

Ans :  converts an array to string,any sepparater can be specified

```js 

let arr=["apple","orange","guva"]
console.log(arr.join("+"));

```




## concat() -

Ans :  converts an array to string,any sepparater can be specified

```js

let arr=["apple","orange","mango"]
console.log(arr.join("+"));

```

## concat() -

Ans : Concatinates multiple arrays


```js

let arr1=["apple","orange","guva",]

let arr2 =["car","bike","bus"]

let arr3 =[1,2,3]
console.log(arr1.concat(arr2,arr3));

```


## flat() -

Ans :  flat method concatinates sub array elements

```js

let arr =[1,2,[3,4],[5,6,7]]
let newArr=arr.flat ()
console.log(newArr);

```


## slice() -

Ans : slice method returns selected elements in a new elament


```js

let arr=["apple","guva","mango","orange"]
let newArr=arr.slice(0,2)
console.log(newArr);

```


## splice() -

Ans : Splice method adds or removes array elements

```js

let arr=[1,2,3,4]
arr.splice(2,1,"five")
console.log(arr);

```

![Scrnshot](./Scrnshort%20JS-6.jpeg)



## 3. Write a JavaScript function to check whether an `input` is an array.

Ans :

```js

function isArr(arr){
    return Array.isAray(arr)
}
console(isArr([1,2,3]));

```

## 4. Write a JavaScript function that takes an array as an argument and returns the first element of the array.

```js

let FirstElement=(arr)=>{
    return arr.slice(0,1)
}
console.log(FirstElement([1,2,3]));

```

## 5. Write a JavaScript function that takes an array as an argument and returns the last element of the array.

```js

let arr=[1,2,3,]
arr.pop()
console.log(arr);

```


## 6. Write a simple JavaScript function to join all elements of the following array into a string.
## Sample array : myColor = ["Red", "Green", "White", "Black"];

```js

let arr=["red","green","white","black"]
console.log(arr.join(""));

```

## 7. Write a JavaScript program that accepts a number as input and inserts dashes (-) between each. For example, if you accept 025468 the output should be 0-2-5-4-6-8

```js

let num=025468
let str=num.toString().split("").join("-")

console.log(str)

```

## 8. Write a JavaScript function that checks if the given number is even or odd then returns a Boolean value (use: arrow function, return keyword, ternary operator)

```js

let input=90
let evenOrOdd=(num)=> {
let result =num%2===0?console.log("Even"):console.log("Odd");
return result

}
evenOrOdd(input)

```


## 9. Create an array of guestlist. Write a javascript function that takes the user’s name as an argument and checks whether it is in the guestlist. If yes, return the string “Welcome” else, return “Sorry, good luck next time”.

```js
let list=["Anand","Sohan","Nandhu","Abhi"]
let check=(name)=> {
    if(list.includes(name)) {

        console.log("Welcome");
        
    }else{
        console.log("Sorry");
        
    }
}
check("Nandhu")

```

## 10. Write a javascript function that reverses a given number example: 123456789 => 987654321 (split(), reverse (), join())

```js


let num=123456789
let str=num.toString().split("").reverse().join("")

console.log(str);

```



## 11. Write a JavaScript function that accepts a string as a parameter and converts the first letter into upper case.
## Example: “javascript” => “Javascript”

```js

let name ="javascript"
let firstLetter =name.slice(0,1).toUpperCase()
let SecondLetter=name.slice(1,name.length).toLowerCase()

console.log(firstLetter+SecondLetter);

```


