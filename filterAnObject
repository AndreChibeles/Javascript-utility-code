const newObject = {name: "", age: 4, city: "NYC", number: undefined};

console.log(newObject);

const objectKeysToArray = Object.keys(newObject);

console.log(objectKeysToArray);

let filteredKeys = objectKeysToArray.filter(key => newObject[key] !== "");
filteredKeys = filteredKeys.filter(key => newObject[key] !== undefined);

console.log(filteredKeys)

let updatedObject = {};

filteredKeys.forEach((value, index, array) => {
  console.log(value)
  updatedObject = {...updatedObject, [value]: newObject[value]}
  console.log(updatedObject);
})

console.log(updatedObject)
