# Composer for WordPress
Example composer.json files for using composer with WordPress. Suitable for shared hosting (ftp access only) and own dedicated servers (with ssh access).

### Get composer
Install Composer globally. [Instructions](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

### Using composer
First run: `composer install`

For ftp-access-only hosting: would you like to download wp's core files too using composer?. Then run: `composer run-script wpcore`

For updating plugins and themes (and WordPress on ssh-access composer example) anytime: run `composer update`

For ftp-access-only hosting: update wp's core using `composer run-script wpcore`

Upload the files to your server as you like.

Recommendation for ftp-access-only hosting: use git and [dandelion](https://github.com/scttnlsn/dandelion).

### License
All source code is released under the [MIT license](https://opensource.org/licenses/MIT).
