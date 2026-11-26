# Hmmm
One lightning code to track, guard and protect. 

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

Function: **`time_range($var, 'year');`**

Example:

```php
$var = array(
            'Name' => 'name 1', 'name 2', 'name 3',
            'Date' => 'date 1', 'date 2', 'date 3',
            'family_tree' => 'parents', 'grandparents', 'great grandparents'  
            // ... etc.
        );

Case 'something': 
      time_range($var, '100'); 
      break;
```

How it work:

**Past <- {time_range} -> Now**
