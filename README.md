# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```

This function returns the maximum value in a list using recurision. 
It compares the the first value of the array to foo, which is the maximum of the rest of the list,
and then returns the greater of the two. -Noah Mulvaney
