###  QUERIES

```php
// to retrieve all *active* customers and order them by their ID:
$customers = Customer::find()
    ->where(array('status' => $active))
    ->orderBy('id')
    ->all();

// or use the following shortcut approach:
$customer = Customer::find(1);

// to retrieve customers using a raw SQL statement:
$sql = 'SELECT * FROM customer';
$customers = Customer::findBySql($sql)->all();

// to return the number of *active* customers:
$count = Customer::find()
    ->where(array('status' => $active))
    ->count();
```
