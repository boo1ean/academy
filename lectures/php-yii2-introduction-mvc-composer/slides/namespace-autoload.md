###  Easy as shit autoloading

```php
function __autoload($class) {
    require_once str_replace('\\', DIRECTORY_SEPARATOR, $class) . '.php';
}

// Invokes __autoload with string = "System\IO\Input\Stream"
$istream = new System\IO\Input\Stream;
```

<h4 class="text-transform-none">
System\IO\Input\Stream &#10137; System/IO/Input/Stream
</h4>
