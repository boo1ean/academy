<h4 class="text-transform-none">controllers/SiteController.php</h4>
```php
namespace app\controllers;

use yii\web\Controller;

class SiteController extends Controller
{
    public function actionIndex() {
        $items = Item::find()->all();
        return $this->render('index', array(
            'items' => $items
        ));
    }
}
```

<h4 class="text-transform-none">view/site/index.php</h4>
```php
<ul>
    <?php foreach ($items as $item): ?>
    <li>
        <?php echo $item->name; ?>
    </li>
    <?php endforeach; ?>
</ul>
```
