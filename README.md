# College-Demo
This is my first git Repository
<br>
Author - Vishal Kumar
<br>
let arr = [1,4,2,7,2,99,6,34,2];
console.log(arr)
for(let i =0; i<arr.length; i++){
    for(let j = 0; j<arr.length; j++){
        if(arr[j] <  arr[j + 1]) {
         let temp = arr[j]
             arr[j] = arr[j+1];
             arr[j+1] = temp

        }
    }
}
console.log('The assending order of the given no is ',arr)

