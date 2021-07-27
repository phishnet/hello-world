# We need your help! 

### The Mockingbird Foundation - who brings you Phish.net - needs your help.

We are seeking a Docker/LAMP (Linux/Apache/MySQL/PHP) rock star to help us bring our development environment forward. This is a paid, contract position, with clear goals. The ideal candidate will be able to help us complete a long-in-the-works project to build a containerized version of phish.net and several subdomains, running locally in Docker. Read on for the details. 

For over a decade, we've had a small team of volunteers assisting with occasional fixes to the site, but almost all of the security work, bug fixes, and new features being developed by a single individual, [@sethadam1](https://twitter.com/sethadam1). We are not only reaching a point where we need additional help, but also trying to build the next generation of phish.net developers and the next generation of phish.net development practices.  

Currently, "Phish.net" is built from two distinct git repositories, both hosted on Github. All of them contain PHP 7.x code running against data in MySQL via PDO and a database API framework. The sites all use a custom MVC framework and depend on mod_rewrite, .htaccess, Smarty for PHP templating, and Memcache. 

The project has two main goals: the first is to complete the mostly functional containerized installation of phish.net and sites within main repository; the second portion of the project is getting our forum, which is a separate repository, working in the same method. 

The following domains that will all need to be functional, presumably on different local TCP ports: 

Repository `phishnet5`: 
* phish.net
* [redacted].phish.net - the Phish.net admin panel
* api.phish.net - the phish.net API
* current.phish.net - phone optimized setlists
* phi.sh - short URL receiver  
* scripts.phish.net - static assets 
* docs.phish.net - documentation of Phish.net API 
* blog.phish.net - legacy redirector
* m.phish.net - legacy redirector
* [redacted].phish.net - testing
* [redacted].phish.net - testing 

Repository `forum`:
* forum.phish.net - The forum is a single repository and is self-contained, using its own repo. It uses Handlebars for templating, Sphinx for search, and several javascript libraries. It currently has no Docker support at all.  

Here is a screenshot of the root of the current `phishnet5` repo: 

![Git repo root](https://i.imgur.com/exDKQaa.jpg)

Currently, pulling the repo and running `docker-compose up` will result in a functional local site mirroring the main domain, but without any of the ancillary sites, such as the admin portal, the forum, or the API. Because some of the bugs we're currently experiencing are on those sites, we're in bit of a rut. 

Do you have the skills to step in and help the Phish community on the gold standard of Phish data? If so, please provide your resume; phish.net username; your github/bitbucket/gitlab username(s); your favorite Phish song; and an initial estimate of hours to `tech@phish.net`. We hope to use all of these factors to locate a qualified candidate and bring you the best phish.net experience possible. 

Got questions? Send them our way! 
