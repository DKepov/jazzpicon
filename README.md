# jazzpicon

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

Say goodbye to boring blocky identicons that look like they came out of the 70s, and replace them with jazzy, colorful collages that more likely came out of the 80's. =)

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practises by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require dkepov/jazzpicon
```

## Usage

``` php
$skeleton = new dkepov\jazzpicon();
echo $skeleton->echoPhrase('Hello, League!');
```

## Examples

```
php -S localhost:8000 -t examples/
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email dkepov@mail.ru instead of using the issue tracker.

## Credits

- [dkepov][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/dkepov/jazzpicon.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/dkepov/jazzpicon/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/dkepov/jazzpicon.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/dkepov/jazzpicon.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/dkepov/jazzpicon.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/dkepov/jazzpicon
[link-travis]: https://travis-ci.org/dkepov/jazzpicon
[link-scrutinizer]: https://scrutinizer-ci.com/g/dkepov/jazzpicon/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/dkepov/jazzpicon
[link-downloads]: https://packagist.org/packages/dkepov/jazzpicon
[link-author]: https://github.com/dkepov
[link-contributors]: ../../contributors
