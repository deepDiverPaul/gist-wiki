* PHP >= 5.4 with PDO
* GIT
* MySQL or SQLite (PostgreSQL should work)
* Composer (php)
* NPM (nodejs)

### Git

Git can maybe be downloaded from your system's repositories.

    $ git config --global user.email "you@example.com"
    $ git config --global user.name "Your Name"

### Composer

Composer can maybe be downloaded from your system's repositories.
Else, follow the next instructions:

    # With cURL
    $ curl -sS https://getcomposer.org/installer | php

    # With Wget
    $ wget -O - -q https://getcomposer.org/installer | php

    $ chmod +x composer.phar

    # For a local installation and if the envvar PATH contains "$HOME/bin/"
    $ mv composer.phar ~/bin/composer

    # For a global installation
    $ sudo mv composer.phar /usr/local/bin/composer

### NPM

    $ sudo apt install npm