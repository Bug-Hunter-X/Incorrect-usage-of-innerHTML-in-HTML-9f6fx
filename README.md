# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates a subtle bug related to the incorrect usage of the `innerHTML` property in HTML.  The intended behavior is to replace the text content of a div element, but due to an error, this is not happening. The solution showcases the correct usage of `innerHTML`.

## Bug Description:
The bug lies in how the `innerHTML` property is used to modify the content of a div. A common mistake is to improperly assign a value resulting in no visual changes. This example highlights this issue.

## Solution:
The solution demonstrates the correct and expected way of using `innerHTML` to modify the content of the div element.

## How to Reproduce:
1. Clone this repository.
2. Open `bug.html` in a web browser. You'll notice the text does not update. 
3. Open `bugSolution.html` to see the corrected code and the desired behavior.