### Bareboned PHP 7 with Composer set-up
Want to quickly test a new feature, practise a new design pattern or just create a new project for yourself?
Well this probably means you'll have to set-up your project with the most basic packages available: PHPUnit & Composer.

And don't forget that you'll have to set-up _yet another_ docker config.. It's the same thing over and over again.

This repository tries to get you started with just 2 commands - just run:

- `git pull git@github.com:KakaCarrotCake/barebone-php-composer.git`
- `composer install`

And BAM, A new - bareboned - PHP instance is ready for you to be played with!

You can also run a docker environment in an instant by running the following command in the `/docker` directory:

- `docker-compose up`

### Additional instructions
Be sure to set the right permissions on the `storage/cache` directory. Your webuser needs to be able to write files into it for Blade template caching.

### Included in this repository are the following packages/software:
- PHPUnit
- Composer
- Docker
- Blade Template Engine (https://github.com/jenssegers/blade)

#### Docker includes:
- PHP 7
- MySQL
- Nginx

### Suggestions?
Got any suggestions that would be a good fit for the project? Just post a ticket in the issues section :-).
