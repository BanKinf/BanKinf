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
            },
            
            Frameworks: {
            
            },
            
            Tools: {
            
            }
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
