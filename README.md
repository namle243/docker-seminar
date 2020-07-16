<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Install steps


### Docker install
- Mac: https://docs.docker.com/docker-for-mac/install/
- Windows: https://docs.docker.com/docker-for-windows/install/
- Linux: 
    - Centos: https://docs.docker.com/install/linux/docker-ce/centos/
    - Debian: https://docs.docker.com/install/linux/docker-ce/debian/
    - Fedora: https://docs.docker.com/install/linux/docker-ce/fedora/
    - Ubuntu: https://docs.docker.com/install/linux/docker-ce/ubuntu/
    
### Clone repository
    git clone git@github.com:namle243/docker-seminar.git

### In root project, start docker compose to run project
    docker-compose up
    docker-compose up -d  (project run in background mode)

### In the first time running project

##### Install dependency and 3party library.

    docker exec -it app composer install
    
##### Generate encryption key

    docker exec -it app php artisan key:generate

### Check site
Goto: `http://localhost:80` or `http://127.0.0.1:80`

##
<p style="text-align:center">From <b>DOTMARK</b> with :heart:</p>