
### [Convert A Hex String To RGB 5kyu ](https://www.codewars.com/kata/5282b48bb70058e4c4000fa7/train/javascript)

.toString() can take a "radix" as a parameter. "radix" must be between 2 and 36. Returns a value that represents a numeric value. 

Can be used to convert hex value to rgb values. See below. 

    function hexColour(c) {
    if (c < 256) {
        return Math.abs(c).toString(16);
    }
    return 0;
    }

    console.log(hexColour(10));
    // expected output: "e9"

    console.log(hexColour('11'));
    // expected output: "b"

    Source: [Stack Overflow](https://stackoverflow.com/questions/5623838/rgb-to-hex-and-hex-to-rgb)

    Source: [MDN toString() with Parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toString)
