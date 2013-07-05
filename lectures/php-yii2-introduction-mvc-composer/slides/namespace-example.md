<h3 class="text-transform-none">System/Stream.php</h3>
```php
<?php namespace System; // Namespace definition

const DEFAULT_STREAM_ADDRESS = 'ssl://default.stream';
class Stream
{
    public function open($address) {
        // ...
    }
}
```

<h3 class="text-transform-none">index.php</h3>
```php
$stream  = new System\Stream;
$address = System\DEFAULT_STREAM_ADDRESS;

$stream->open($address);
```
