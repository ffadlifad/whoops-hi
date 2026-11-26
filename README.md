# whoops-hi
Just one lightning code to track, guard and protect. 

Code: **`(faith == true && honesty == true) { check_your _intention(); }`**

Example:
```php
try {
   // do_something();

} catch (\Throwable $th) {
    // echo "Whoops, something went wrong. Please check your intention, faith and honesty are required.";

    // 2026
    echo "Hi. Please check your intention, faith and honesty are required.";
}
```

## Time Range
If you catch some whoops, you can track using time_range.

Function: **`time_range(“Year”);`**

Example:

```php
// Complex case
Case 'fadli': 
      time_range(“100”); 
      break;
```

How it work:

**Past <- {time_range} -> Now**
