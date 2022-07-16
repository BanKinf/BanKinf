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
                'position' => 'BackEnd Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Languages: {
             Php::class,
             Javascript::class,
             TypeScript::class,
             NodeJs::class,
             Python::class,
             Golang::class,
             Rust::class,
             Sql::class
            },
            
            Frameworks: {
             Laravel::class,
             Django::class,
             NextJs::class
            },
            
            Libs: {
             React::class,
             Jwt::class,
            }
            
            Tools: {
             VSCode::class,
             Figma::class,
             Git::class,
             Postman::class,
             Insomnia::class,
            }
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
