### 🤝 Connect with me:


<a href="https://www.linkedin.com/in/endrit-v-germizaj/"><img align="left" src="https://raw.githubusercontent.com/EndritG/EndritG/main/img/linkedin.svg" alt="EndritG | LinkedIn"                                                             width="45px"/></a>
<a href="https://www.facebook.com/endritgermizajj"><img align="left" src="https://raw.githubusercontent.com/EndritG/EndritG/main/img/facebook1.svg" alt="EndritG | Facebook" 
                                           width="45px"/>
</a>
                                           
<a href="https://twitter.com/EGermizaj"><img align="left" src="https://raw.githubusercontent.com/EndritG/EndritG/main/img/twitter.svg" alt="EndritG | Twitter" 
                                           width="45px"/></a>

</br>



```php
<?php
namespace EndritGermizaj;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'AlbiSmart',
                'position' => 'Backend Developer'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Nodejs::class,
            Expressjs::class,
            MySQL::class,
            MongoDB::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```






© 2022 Endrit Germizaj

