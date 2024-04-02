<img src="https://alpha-centauri-production.s3.amazonaws.com/uploads/content/174/header_image/header.jpg" />

```php
<?php

namespace JohnathanRadojevich;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Terracon',
                'position' => 'Application Developer'         
            ]
        ];
    }

    public function getKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getGoal(): string
    {
        return 'to contribute to open source';
    }
}
```

# Hello! 
