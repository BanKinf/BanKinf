```php

<?php

namespace BanKinf;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'FreeLancer',
                'position' => 'BacKend Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Languages: {
             Php::class,
             Javascript::class,
             NodeJs::class,
             Python::class,
             Golang::class,
             Rust::class
            },
            
            Frameworks: {
             React::class,
             Laravel::class,
             Django::class,
             NextJs::class
            },
            
            Tools: {
             Git::class,
             SQL::class,
             
            }
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
