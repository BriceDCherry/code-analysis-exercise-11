# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (actualAge){
  if (actualAge == 1){
    return {
      humanYears: actualAge,
      catYears: 15,
      dogYears: 15,
    }
  }

  if (actualAge == 2){
    return {
      humanYears: actualAge,
      catYears: 24,
      dogYears: 24,
    }
  }

  return {
    humanYears: actualAge,
    catYears: (actualAge - 2) * 4 + 24,
    dogYears: (actualAge - 2) * 5 + 24,
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|   5   | {humanYears: 5, catYears: 36, dogYears: 39}  | 
|   7   | {humanYears: 7, catYears: 44, dogYears: 49}  | 
|  10   | {humanYears: 10, catYears: 56, dogYears: 64} | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes human age and converts it into cat and dog years.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
