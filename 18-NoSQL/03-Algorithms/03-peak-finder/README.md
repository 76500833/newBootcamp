# Peak Finder

In this activity, you will write code to create a function that takes in an array of numbers and returns the peak of the array.

## Instructions

* Open [Unsolved/peak-finder.js](Unsolved/peak-finder.js) in your code editor; this is the only file you will modify in this activity.

  * In this file, you will write code in the body of the `peakFinder` function to achieve the following:

    * Return the peak of the array. A peak is defined as the element in the array that is greater than all of the elements to its right and left.

    * For example, given the following array:

        ```js
        var arr = [1, 3, 7, 4, 3, 2, 1];
        ```

    * The following should be returned:

        ```js
        7;
        ```

    * Assume that the array contains exactly one peak.

    * It is possible for the peak to be the first or last element in the array if it is greater than all the other elements. For example, given the following array:

        ```js
        var arr = [2, 4, 6, 8, 10];
        ```

    * The following number should be returned:

        ```js
        10;
        ```

    * Assume that the array will contain at least one number. If the array contains only one number, that number is the peak.

* You can check to see if your function works properly by opening [Unsolved/test.html](Unsolved/test.html) in your web browser.

  * Functions that pass the tests will be denoted with a green check mark.

  * Functions that fail the tests will be denoted with a red x and an error message.

### Bonus

* Can you implement this algorithm without checking every number in the array?

---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
