# Hmmm
One lightning code to track, guard and protect. 

⚡ **`(faith == true && honesty == true) { check_your _intention(); }`**

Example:
```php
try {
   do_something();

} catch (\Throwable $th) {
   echo "Whoops, something went wrong. Please check your intention, faith and honesty are required.";
}
```

## Time Range
If you catch some whoops, you can track using time_range. 

Function: **`time_range($var, 'year');`**

Example:

```php
$var = [
    'Name' => ['name 1', 'name 2', 'name 3'],
    'Date' => ['date 1', 'date 2', 'date 3'],
    'family_tree' => ['parents', 'grandparents', 'great grandparents']
    // ... etc
];

case 'something': 
      time_range($var, '100'); 
      break;
```

How it work: **`Past << {time_range} >> Now`**

## Hi
In 2026, i found something and that's why whoops becomes Hi.

```php
Hi, please check your intention. faith and honesty are required.
```
