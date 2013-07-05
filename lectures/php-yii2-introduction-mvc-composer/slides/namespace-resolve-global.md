### Resolving global namespace

```php
namespace System;

class Worker
{
    public function fire($power) {
        if ($power <= 0) {
            throw new \LogicException("Need more power");
        }
    }
}

```
