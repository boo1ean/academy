## controller example

```php
namespace app\controllers;

use yii\web\Controller;

class SiteController extends Controller
{
    public function actionIndex() {
        // will render view from "views/site/index.php"
        return $this->render('index');
    }

    public function actionJson() {
        return json_encode(array('status' => 'success'));
    }
}
```
