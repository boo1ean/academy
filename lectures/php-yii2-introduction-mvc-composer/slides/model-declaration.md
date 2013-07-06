### Declaring ActiveRecord Classes

```php
use yii\db\ActiveRecord;
class Customer extends ActiveRecord
{
    public static function tableName() {
        return 'customer';
    }
}
```
