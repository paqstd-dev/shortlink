# ShortLink Service

## About
ShortLink is a simple service to shorten your links and keep them! 
Paste the long url into the box on the home page and press `Enter`. 
Magic ... and you have a short link that you can copy and use in the future! 
To use the short link, just follow it!

## Tech Stack
Docker, Nginx, VueJS, Django. For design used uikit [Tabler](https://github.com/tabler/tabler).

## Deploy
To start using the service, you need to make a couple of commands:       

> git clone ...  
> cp .env.dist .env  
> make deploy  
> make migrate  

It is build client, build server and make migrations for db.
