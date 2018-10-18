# Arrays 
## PHP
```php
<?php
$array = array(
    "foo" => "bar",
    "bar" => "foo",
);

// as of PHP 5.4
$array = [
    "foo" => "bar",
    "bar" => "foo",
];
?>
```

## Hack 
`dict`, `vec`, and `keyset`
```php
<?hh

$vecArray = vec[1, 2, 3, 1];
$dictArray = dict['a' => \ord('a'), 'b' => \ord('b'), 'c' => \ord('c')];
$keysetArray = keyset[1, 2, 3, 1]; 
```

## ref 
- php Arrays : http://php.net/manual/en/language.types.array.php 
- hack Arrays : https://docs.hhvm.com/hack/collections/hack-arrays
