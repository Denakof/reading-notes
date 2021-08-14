## The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

map calls a provided callbackFn function once for each element in an array, in order, and constructs a new array from the results. callbackFn is invoked only for indexes of the array which have assigned values (including undefined).

## The reduce() method executes a reducer function (that you provide) on each element of the array, resulting in a single output value.

The reduce() method executes the callbackFn once for each assigned value present in the array, taking four arguments:

accumulator
currentValue
currentIndex
array

The first time the callback is called, accumulator and currentValue can be one of two values. If initialValue is provided in the call to reduce(), then accumulator will be equal to initialValue, and currentValue will be equal to the first value in the array. If no initialValue is provided, then accumulator will be equal to the first value in the array, and currentValue will be equal to the second.

superagent
 ```
  .get(URL)
  .then((res) => {
      console.log(res);
    // res.body , res.headers , res.status
  })
  .catch((err) => {
    // console.log(err);
  });
  ```


using async/await syntax :

```
async function getResponse(){
    try{
    const response = await superagent.get(URL);
    console.log(response);
    // res.body , res.headers , res.status

    } catch (err){
        console.log(err);
    }

}
```