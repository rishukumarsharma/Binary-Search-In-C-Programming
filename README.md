In this implementation, binarySearch function takes an array arr of size n and an element x to be searched for. The function returns the index of x if it is present in the array, otherwise it returns -1.

The function works by repeatedly dividing the search interval in half. At each step, the function compares the middle element of the interval with x. If x is equal to the middle element, the function returns the index of the middle element. If x is less than the middle element, the function searches in the left half of the interval. If x is greater than the middle element, the function searches in the right half of the interval.

The main function in this example initializes an array arr and searches for the element x = 10. If x is found in the array, the function prints the index at which it is found. If x is not found in the array, the function prints a message indicating that the element was not found.



