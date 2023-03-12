# simple_php_cache
simple php file-caching class.
### How to use
require cache class
```php
<?php
require("cache.php");
?>
```
get data from class
```php
Cache::get("data_name");
```
store data
```php
Cache::put("data_name",$data,60);
```
3rd varible above its time for how long you caching data in seconds.
