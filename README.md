# MathMLBundle

## Usage

```php
$factory = $container->get('mercurysolutions.mathml');
$mathml = $factory->create('<mathml><apply><sum/><ci>x</ci><cn>2</cn></apply></mathml>');
$result = $mathml->calculate(['x' => 4]); // $result === 6
```