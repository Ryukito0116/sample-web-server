# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
ここに書く
Last login: Fri Jun 14 09:24:11 on ttys000
You have new mail.
matayoshiryukito-no-MacBook-Pro:~ Ryukito_PC$ cd fujiwara
matayoshiryukito-no-MacBook-Pro:fujiwara Ryukito_PC$ git clone git@github.com:Ryukito0116/sample-web-server.git
Cloning into 'sample-web-server'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 7 (delta 1), reused 5 (delta 1), pack-reused 0
Receiving objects: 100% (7/7), done.
Resolving deltas: 100% (1/1), done.
matayoshiryukito-no-MacBook-Pro:fujiwara Ryukito_PC$ cd sample-web-server/
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ code .
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[],"id":"aal","url":"https://cdn2.thecatapi.com/images/aal.jpg","width":640,"height":427}]matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_Pquest GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"9qi","url":"https://cdn2.thecatapi.com/images/9qi.jpg","width":894,"height":894},{"breeds":[],"id":"a8i","url":"https://cdn2.thecatapi.com/images/a8i.jpg","width":400,"height":560},{"breeds":[],"id":"c1b","url":"https://cdn2.thecatapi.com/images/c1b.jpg","width":900,"height":600}]matayoshiryukito-noquest GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"4gu","url":"https://cdn2.thecatapi.com/images/4gu.gif","width":228,"height":182},{"breeds":[],"id":"9l6","url":"https://cdn2.thecatapi.com/images/9l6.jpg","width":720,"height":960},{"breeds":[],"id":"e8t","url":"https://cdn2.thecatapi.com/images/e8t.jpg","width":500,"height":416}]matayoshiryukito-noquest GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"5n3","url":"https://cdn2.thecatapi.com/images/5n3.jpg","width":640,"height":588},{"breeds":[],"id":"e36","url":"https://cdn2.thecatapi.com/images/e36.jpg","width":500,"height":654},{"breeds":[],"id":"vkwoyqZsR","url":"https://cdn2.thecatapi.com/images/vkwoyqZsR.jpg","width":5184,"heurl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=4'
[{"breeds":[],"categories":[{"id":15,"name":"clothes"}],"id":"8ve","url":"https://cdn2.thecatapi.com/images/8ve.jpg","width":535,"height":720},{"breeds":[],"id":"e83","url":"https://cdn2.thecatapi.com/images/e83.jpg","width":401,"height":179},{"breeds":[],"id":"e9d","url":"https://cdn2.thecatapi.com/images/e9d.jpg","width":500,"height":401},{"breeds":[{"weight":{"imperial":"10 - 12","metric":"5 - 6"},"id":"dons","name":"Donskoy","temperament":"Playful, affectionate, loyal, social","origin":"Russia","country_codes":"RU","country_code":"RU","description":"Donskoy are affectionate, intelligent, and easy-going. They demand lots of attention and interaction. The Donskoy also gets along well with other pets. It is now thought the same gene that causes degrees of hairlessness in the Donskoy also causes alterations in cat personality, making them calmer the less hair they have.","life_span":"12 - 15","indoor":0,"adaptability":4,"affection_level":4,"child_friendly":3,"cat_friendly":3,"dog_friendly":3,"energy_level":4,"grooming":2,"health_issues":3,"intelligence":3,"shedding_level":1,"social_needs":5,"stranger_friendly":5,"vocalisation":2,"experimental":0,"hairless":1,"natural":0,"rare":1,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Donskoy_(cat)","hypoallergenic":0}],"id":"3KG57GfMW","url":"https://cdn2.thecatapi.com/images/3KG57GfMW.jpg","width":750,"height":750}]matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3
> 
> 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3
> 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ brew install jp
Updating Homebrew...
==> Auto-updated Homebrew!
Updated 1 tap (homebrew/core).
==> New Formulae
swig@3
==> Updated Formulae
aws-sdk-cpp         glib                mighttpd2           scons
braid               glooctl             minio               scrcpy
calicoctl           gmic                minio-mc            ship
certbot             graph-tool          nomad               sops
chakra              gst-plugins-good    opa                 telegraf
circleci            hlint               paket               terraform
envconsul           imagemagick         phpunit             topgrade
exiftool            jdupes              procs               vultr
firebase-cli        jfrog-cli-go        pulumi              webpack
flow                joplin              pybind11            whois
fluxctl             knot                pyenv               wildfly-as
folly               libev               rbspy               wtf
gibo                lmod                scalariform         yelp-tools
==> Deleted Formulae
swig@3.04

Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ brew install jp
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ sudo brew install jp
Password:
Sorry, try again.
Password:
Error: Running Homebrew as root is extremely dangerous and no longer supported.
As Homebrew does not drop privileges on installation you would be giving all
build scripts full access to your system.
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
-bash: jq: command not found
(23) Failed writing body
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"c8d","url":"https://cdn2.thecatapi.com/images/c8d.jpg","width":897,"height":599},{"breeds":[],"id":"e10","url":"https://cdn2.thecatapi.com/images/e10.jpg","width":345,"height":500},{"breeds":[],"id":"MTgzNDkwNA","url":"https://cdn2.thecatapi.com/images/MTgzNDkwNA.jpg","width":1760,"height":2640}]matquest GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq--re 
-bash: jq: command not found
(23) Failed writing body
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ brew install jp
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ sudo chown -R $(whoami) /usr/local/lib/pkgconfig
Password:
Sorry, try again.
Password:
Sorry, try again.
Password:
sudo: 3 incorrect password attempts
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ sudo chown -R $(whoami) /usr/local/lib/pkgconfig
Password:
Sorry, try again.
Password:
Sorry, try again.
Password:
sudo: 3 incorrect password attempts
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ su -i
su: illegal option -- i
usage: su [-] [-flm] [login [args]]
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ sudo -i
Password:
Sorry, try again.
Password:
Sorry, try again.
Password:
sudo: 3 incorrect password attempts
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ su -i
su: illegal option -- i
usage: su [-] [-flm] [login [args]]
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ pwd
/Users/Ryukito_PC/fujiwara/sample-web-server
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ cd /
matayoshiryukito-no-MacBook-Pro:/ Ryukito_PC$ su -i
su: illegal option -- i
usage: su [-] [-flm] [login [args]]
matayoshiryukito-no-MacBook-Pro:/ Ryukito_PC$ su -
Password:
su: Sorry
matayoshiryukito-no-MacBook-Pro:/ Ryukito_PC$ su -
Password:
su: Sorry
matayoshiryukito-no-MacBook-Pro:/ Ryukito_PC$ sudo chown -R $(whoami) /usr/local/lib/pkgconfig
Password:
matayoshiryukito-no-MacBook-Pro:/ Ryukito_PC$ ls
Applications			etc
Library				home
Network				installer.failurerequests
System				net
Users				private
Volumes				sbin
bin				tmp
cores				usr
dev				var
matayoshiryukito-no-MacBook-Pro:/ Ryukito_PC$ cd etc
matayoshiryukito-no-MacBook-Pro:etc Ryukito_PC$ ls
afpovertcp.cfg				newsyslog.conf
afpovertcp.cfg~orig			newsyslog.d
aliases					nfs.conf
aliases.db				nfs.conf~orig
apache2					notify.conf
asl					ntp.conf
asl.conf				ntp_opendirectory.conf
auto_home				openldap
auto_master				pam.d
auto_master~orig			passwd
autofs.conf				paths
bashrc					paths.d
bashrc_Apple_Terminal			paths~orig
bashrc~previous				periodic
com.apple.screensharing.agent.launchd	pf.anchors
csh.cshrc				pf.conf
csh.cshrc~orig				pf.os
csh.login				php-fpm.conf.default
csh.login~orig				php-fpm.d
csh.logout				php.ini.default
csh.logout~orig				php.ini.default-previous
cups					php.ini.default-previous~orig
defaults				postfix
dnsextd.conf				ppp
efax.rc~previous			profile
emond.d					profile~orig
find.codes				protocols
find.codes~orig				protocols~previous
fstab.hd				racoon
fstab.hd~previous			rc.common
ftpusers				rc.common~previous
ftpusers~orig				rc.netboot
gettytab				resolv.conf
gettytab~orig				rmtab
group					rpc
group~previous				rpc~previous
hosts					rtadvd.conf
hosts.equiv				rtadvd.conf~previous
hosts~orig				security
irbrc					services
kern_loader.conf			services~previous
kern_loader.conf~previous		shells
krb5.keytab				shells~orig
localtime				snmp
locate.rc				ssh
mach_init.d				ssl
mach_init_per_login_session.d		sudo_lecture
mach_init_per_user.d			sudoers
mail.rc					sudoers.d
mail.rc~orig				sudoers~orig
man.conf				syslog.conf
manpaths				syslog.conf~previous
manpaths.d				ttys
master.passwd				ttys~previous
master.passwd~orig			wfs
moduli~previous				xtab
nanorc					zprofile
networks				zshrc
networks~orig
matayoshiryukito-no-MacBook-Pro:etc Ryukito_PC$ cd ~/fujiwara
matayoshiryukito-no-MacBook-Pro:fujiwara Ryukito_PC$ ls
hello-git		sample-web-server
learning-http-message	simple-web-site
matayoshiryukito-no-MacBook-Pro:fujiwara Ryukito_PC$ cd sample-web-server/
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ brew install jp
==> Downloading https://homebrew.bintray.com/bottles/jp-1.1.12.mojave.bottle.tar
==> Downloading from https://akamai.bintray.com/53/53127a663b20c7c0ac893d991330c
######################################################################## 100.0%
==> Pouring jp-1.1.12.mojave.bottle.tar.gz
🍺  /usr/local/Cellar/jp/1.1.12: 3 files, 3MB
==> `brew cleanup` has not been run in 30 days, running now...
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
-bash: jq: command not found
(23) Failed writing body
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ brew install jp
Warning: jp 1.1.12 is already installed and up-to-date
To reinstall 1.1.12, run `brew reinstall jp`
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[],"categories":[{"id":2,"name":"space"}],"id":"5hs","url":"https://cdn2.thecatapi.com/images/5hs.jpg","width":640,"height":441}]matayoshiryukito-no-ght":441}]matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
> curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
> 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ ","width":640,"height":441}]matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
> 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[],"id":"9lj","url":"https://cdn2.thecatapi.com/images/9lj.jpg","width":612,"height":612}]matayoshiryukito-no-MacBook-Pro:sample-wecurl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ cat ~/.bash_profile
cat: /Users/Ryukito_PC/.bash_profile: No such file or directory
matayoshiryukito-no-MacBook-Pro:sample-web-server Ryukito_PC$ 

```
