/*```php
<?php

namespace Alifilho;

class About extends Me {
    public function getCurrentWorkplace() {
        return [
            'workplace' => [
                'company' => 'Retornar',
                'position' => 'Front-end Developer'         
            ]
        ];
    }

    public function getDailyKnowledge() {
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

    public function getFutureGoal() {
        return 'To contribute to better world.';
    }
}
```*/

```ts
namespace Alifilho;

Class About extends Me {
    const getCurrentWorkplace = () : Workspace => {
        return {
            company: 'Retornar',
            position: 'Front-end Developer'
        };
    }

    const getDailyKnowledge = () : string[] => {
        return [
            'TypeScript',
            'JavaScript',
            'NodeJS',
            'ReactJS',
            'ReactNative',
            'PHP',
            'Laravel'
        ];
    }

    const getFutureGoal = () => {
        return 'To contribute to better world.';
    }
}
```
