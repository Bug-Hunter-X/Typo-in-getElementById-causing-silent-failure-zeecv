# Uncommon HTML Bug: getElementById Typo

This repository demonstrates a subtle bug in HTML/JavaScript that can be easily missed.  The bug involves a simple typo in the `getElementById` method, leading to unexpected behavior.  The solution provides the correct implementation. 

## Bug Description

The provided HTML file attempts to access a div element using `document.getElementByIdx` (note the 'x'). This typo causes the method to return `null`, and the subsequent manipulation of `innerHTML` fails without throwing an error.  This silent failure makes debugging more challenging.

## Solution

The solution corrects the typo in the JavaScript code by replacing `getElementByIdx` with the correct `getElementById`. This ensures that the script correctly targets the intended element and updates its content as expected.