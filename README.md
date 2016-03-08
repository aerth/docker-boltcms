![](screenshot.png?raw=true "Bolt CMS")

## Run it

`docker run -it -d --name mybolt -p 8080:80 aerth/boltcms:latest`

####################

Or you may want to customize and tag your own image.

## Build

`docker build -t username/mybolt .`

## Serve

`docker run -it -d --name hello -p 8080:80 username/mybolt:latest`

## Hack

`$ docker exec -it mybolt bash`
`bash-4.3# apk update && apk add nano vim`
`exit`

## Save Changes

`$ docker commit hello username/mybolt:latest`

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

