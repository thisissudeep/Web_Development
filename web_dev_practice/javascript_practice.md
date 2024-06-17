# JavaScript Practice:

- Number Mirror

Write a program that takes a number NN as the input, and prints it to the output.

Input Format :
The only line of input contains a single integer.

Output Format :
Output the answer in a single line.

Constraints: 0≤N≤10<sup>5</sup>

Sample 1:

Input: 123

Output: 123
``` javascript
function numberMirror(n)
{
    console.log(n);
    
}

process.stdin.setEncoding('utf-8');
process.stdin.on('data',function(input){
    const n=parseInt(input.trim());
    numberMirror(n);
});
```

- Chef and Instant Noodles

Chef has invented 11-minute Instant Noodles. As the name suggests, each packet takes exactly 11 minute to cook.Chef's restaurant has XX stoves and only 11 packet can be cooked in a single stove at any minute.How many customers can Chef serve in YY minutes if each customer orders exactly 11 packet of noodles?

Input Format:

The first and only line of input contains two space-separated integers XX and YY — the number of stoves and the number of minutes, respectively.

Output Format:

Print a single integer, the maximum number of customers Chef can serve in YY minutes

Sample 1:

Input : 3 7

Output : 21

``` javascript
function maxCustomers(a,b)
{
    return a*b;
}

process.stdin.setEncoding('utf-8');
process.stdin.on('data',function(input)
{
    const nums=input.split(" ");
    const a=parseInt(nums[0])
    const b=parseInt(nums[1]);
    console.log(maxCustomers(a,b))  
})
```

- CodeChef Learn Problem Solving

Input Format: The only line of input will contain a single integer NN, denoting the number of languages for which there are courses.

Output Format: Output on a single line the total number of courses in the section.

Sample Input: 4

Your Output: 8
``` javascript
function totalCourses(n){
    return n*2;
}

process.stdin.setEncoding('utf8');
process.stdin.on('data', function(input) {
   const n = parseInt(input.trim()); 
   console.log(totalCourses(n));
});
```

- Learning SQL

Input Format

The only line in the input contains three space-separated integers RR, CC, and EE — the number of initial rows, the number of columns, and the number of extra rows added, respectively.

Output Format

Output on a new line, a single integer, which should be the final total number of cells in the table.

Sample Input

5 2 1

Your Output

12
``` javascript
function totalCells(r, c, e){
   console.log((r+e)*c);
}

process.stdin.setEncoding('utf8');
process.stdin.on('data', function(input) {
  const nums = input.trim().split(' ');
  const r = parseInt(nums[0]); 
  const c = parseInt(nums[1]); 
  const e = parseInt(nums[2]); 
  totalCells(r, c, e);
});
```

- Parking Charges

Input Format

The only line of the input will contain three space separated integers - XX, YY, and HH.

Output Format

Output a single integer, which should be the total amount that Chef pays as parking charge.

Sample Input

10 1 5

Your Output

14

``` javascript
function totalAmount(x, y, h){
    console.log(x+((h-1)*y))
}

process.stdin.setEncoding('utf8');
process.stdin.on('data', function(input) {
  const nums = input.trim().split(' ');
  const x = parseInt(nums[0]); 
  const y = parseInt(nums[1]); 
  const h = parseInt(nums[2]); 
  totalAmount(x, y, h);
});
```
