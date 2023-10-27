# My-IndexOf-assignment
Recreate the array.indexOf() method. Test if the provided item is in the provided array and determine the index position of the provided item using myIndexOf function.

function myIndexOd(array,item) {
  for(i = 0; i < array.length; i++) {
    if(array[i] === item) {
      return i;
    }
  }
  return -1;
}
