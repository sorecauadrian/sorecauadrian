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
                'position' => 'Intern'         
            ]
        ];
    }

    public function getProgrammingKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            C++::class,
            Python::class,
            ReactJS::class,
            NodeJS::class,
            ExpressJS::class
        ];
    }
}
```
