# Valid Brackets

In this activity, you will write code to create a function that takes in a string and returns `true` if the string contains a valid, matching set or sets of brackets, and `false` if not.

## Instructions

* Open [Unsolved/valid-brackets.js](Unsolved/valid-brackets.js) in your code editor; this is the only file you will modify in this activity.

  * In this file, you will write code in the body of the `validBrackets` function to achieve the following:

    * Return `true` if the string contains a valid set or sets of brackets, else return `false`.

    * For example, given the following string:

      ```js
      var str = "( )";
      ```

    * The following should be returned:

      ```js
      true;
      ```

    * Given the following string:

      ```js
      var str = "{ } [ ( [] ) ]";
      ```

    * The following should be returned:

      ```js
      true;
      ```

    * Given the following string:

      ```js
      var str = "( [ ) ]";
      ```

    * The following should be returned:

      ```js
      false;
      ```

    * Because the brackets -- [ and ) -- are mismatched.

* You can check to see if your function works properly by opening [Unsolved/test.html](Unsolved/test.html) in your web browser.

  * Functions that pass the tests will be denoted with a green check mark.

  * Functions that fail the tests will be denoted with a red x and an error message.

---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
