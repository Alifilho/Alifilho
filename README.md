```php
<?php

namespace Alifilho;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Retornar',
                'position' => 'Front-end Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Typescipt::class
            Javascript::class,
            NodeJS::class,
            ReactJS::class,
            ReactNative::class,
            Php::class,
            Laravel::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to better world.';
    }
}
```
