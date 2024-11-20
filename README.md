```php
<?php

namespace sorecauadrian;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'aiconomy AG',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getWorkspaceTechnologies(): array
    {
        return [
            PHP::class,
            Laravel::class,
            FilamentPHP::class,
            AlpineJS::class,
            Javascript::class,
            VueJS::class
        ];
    }
}
```
