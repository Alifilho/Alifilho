```php
<?php

namespace Alifilho;

class About extends Me {
    public function getDailyKnowledge() {
        return [
            Typescipt::class
            Javascript::class,
            NodeJS::class,
            NestJS::class,
            ReactJS::class,
            ReactNative::class,
            Php::class,
            Laravel::class,
        ];
    }

    public function getFutureGoal() {
        return 'To contribute to better world.';
    }
}

?>

```
