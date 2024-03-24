## free-neurosecurity-quotes

A curated list of historic quotes on free human neurosecurity.

## Usage examples

1. Getting a random quote in PHP 8 using the local fs: 

    <?php
    $randomizer = new Random\Randomizer();
    $url = '/home/www/static/freethinking.md'; # avoid making useless dns queries
    $data = $randomizer->shuffleArray(file($url));
    $int = $randomizer->getInt(1, count($data) - 1);
    $q = $data[$int];
    ?>

## License

GPL version 3 or later

## Maintainer 

Etienne Robillard <smart@open-neurosecurity.org>
