##  ActiveRecord workflow

```php
// Create
$a = new Customer;
$a->name = 'Jacke';
$a->age  = 10;
$a->save();

// Update
$customer = Customer::find()->first();
$customer->age = 20;
$customer->save();
```
