### Connecting to Database

```php
return array(
    'components' => array(
        'db' => array(
            'class'    => 'yii\db\Connection',
            'dsn'      => 'mysql:host=localhost;dbname=testdb',
            'username' => 'root',
            'password' => 'root'
        )
    )
);
```
