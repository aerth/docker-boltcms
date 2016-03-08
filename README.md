![](https://raw.githubusercontent.com/aerth/docker-boltcms/master/screenshot.png?raw=true "Bolt CMS")

## Run it

```
docker pull aerth/boltcms:latest
docker run -it -d --name mybolt -p 8080:80 aerth/boltcms:latest

```

## Hack it

```
$ docker exec -it mybolt bash
bash-4.3# apk update && apk add nano vim
bash-4.3# cd /var/www && ls
bash-4.3# exit
```

## Save Changes

`$ docker commit mybolt username/mybolt:latest`

## Launch your new thang

`$ docker run -it -d -p 8081:80 username/mybolt:latest`







About Bolt
====

Sophisticated, lightweight & simple CMS. Homepage: [Bolt.cm](https://bolt.cm)

Bolt is a tool for Content Management, which strives to be as simple and
straightforward as possible. It is quick to set up, easy to configure, uses
elegant templates, and above all: It's a joy to use. Bolt is created using
modern open source libraries, and is best suited to build sites in HTML5 with
modern markup.

From a technical perspective: Bolt is written in PHP, and uses either SQLite,
MySQL or PostgreSQL as a database. It's built upon the [Silex framework](http://silex.sensiolabs.org)
together with a number of [Symfony](http://symfony.com/) [components](http://symfony.com/components)
and [other libraries](http://docs.bolt.cm/credits). Bolt is released under the
open source [MIT-license](http://opensource.org/licenses/mit-license.php).

