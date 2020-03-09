# calculator
#Copyright © Mike Talks 2020


Instructions
The following page is a very basic calculator - I know you have one on your phone, so why do you need another one?

The purpose of this page is to provide an object with basic functionality for you to try your first attempt to use a test tool on.

You can add/subtract/divide/multiply - all mathematical functions. When chosen, the page checks that you've entered numerical values. You can also toggle whether you want your answer as an integer value.

If you choose to concatonate, the system treats the inputs as strings, and won't check numerical values. You'll also not be able to select to get an integer value answer.

There are multiple builds available. Prototype works perfectly, whereas builds 1-8 have problems. A good set of tests should help identify what the problems are.

/*
       * BUILD DESCRIPTOR
       * 0 - all is good
       * 1 - doesn't check for valid numbers
       * 2 - add and concatonate are the wrong way around
       * 3 - always treats like a number
       * 4 - locked on integer
       * 5 - Clear button unavailable
       * 6 - Divide by zero not checked
       * 7 - Uses answer, not number 1 as first for operation
       * 8 - Switches numbers 1 and 2 around
       * 9 - Elements vanish
       */
