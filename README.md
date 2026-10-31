compose stack to run a jekyll site so i can test my github pages site without having to install dependancies
> youll want to set SITE_DIR= under a .env in the clone to this repo before running docker compose up to host the jekyll site
> there is the option to set a STYLE_DIR, this is because of the work ive done to create [a collection of styles](https://github.com/BenHorleyOwen/StyleRepo)
compose.yml can create a server assuming a basic Gemfile is present
in the future i must make it so that it automatically creates the gem file for me, it can genereate the Gemlock

P.S
This would have initally been easier if i had simply just installed jekyll and bundler etc to my system, however in a fashion typical to myself i found a loose thread of curiosity in my mind and had to pull on it and see where it went. Right back to containers it seems. However this has been an interesting exercise in advancing my knowledge deeper.
