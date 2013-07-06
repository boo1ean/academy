##  Internal routing

```php
'urlManager' => array(
    'enablePrettyUrl' => true,
    'rules' => array(
        '/' => 'site/index',
    )
),
```

<h4 class="text-transform-none">site/about &nbsp; <span class="red">calls</span> &nbsp; SiteController&#10137;aboutAction</h4>
<h4 class="text-transform-none">site &nbsp; <span class="red">calls</span> &nbsp; SiteController&#10137;indexAction</h4>
