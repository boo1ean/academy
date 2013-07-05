##  Simple controller

```php
namespace app\controllers;

use yii\web\Controller;

class SiteController extends Controller
{
    public function actionIndex()
    {
        // will render view from "views/site/index.php"
        return $this->render('index');
    }

    public function actionTest()
    {
        return 'test'; // will just print "test" to the browser
    }
}
```
