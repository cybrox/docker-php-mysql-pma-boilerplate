# Docker PHP, MySQL, PhpMyAdmin Boilerplate
Terribly simple boilerplate for dockerizing a typical customer webserver. I put this up mostly to use it as a base for working on my old projects, but feel free to use it however you like.

**Usage:**   
1. Clone this project    
2. Delete `.git` and paste in all your project content    
3. `docker-compose up` (optionally with `-d` flag)     
4. Exposed ports will be `:80` for nginx and `:8080` for PMA

**Credits**    
Honor where honor is due, aside from some minimal tweaks, this is an implementation as described in [this article](http://tech.osteel.me/posts/2015/12/18/from-vagrant-to-docker-how-to-use-docker-for-local-web-development.html). The only reason I tweaked this is, because I hate cluttering my project root with dev dependency folders. Either way, if you want to just get a dev env up really quick, clone and run this. If you want to learn more about `Dockerfile` and `docker-compose` Syntax and concepts, definitely read the article.
