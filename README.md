```php
<?php
namespace AnilChudasama;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Mine',
                'position' => 'Founder'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            React::class,
            Shopify::class,
            TailwindCss::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return 'Learn to be best self version.';
    }
}
