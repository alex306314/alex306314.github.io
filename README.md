
AQRUN.com

My Blog

## Rvm install

* http://www.rvm.io/

## Ruby install

* `rvm list known`
* `rvm install 2.5`

## Set china gem sources

* `gem source -a https://gems.ruby-china.com`
* `gem sources --remove https://rubygems.org/`

## Install jekyll

* `gem instlal jekyll`
* `gem install jekyll-paginate-v2 route kramdown`

## Run server


```shell
jekyll serve -w --host=0.0.0.0
```

## publish

* jekyll build
* scp -r _site/* root@47.*.*.*:/var/www/aqrun/

