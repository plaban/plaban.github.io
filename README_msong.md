

Sudo gem install bundler jekyll


Ref
--
~ $ sudo gem install bundler jekyll # 확인 필요?
~ $ jekyll new my-awesome-site # 확인 필요?
~ $ cd my-awesome-site
~/my-awesome-site $ sudo bundle exec jekyll serve # 필요!!

방법
1. minseoksong_source.github.org에서 홈페이지 수정 및 build
~/my-awesome-site $ sudo bundle exec jekyll build # 필요!! ==> server 반영을 위해서 필요

2. minseoksong_source.github.org의 _site에서 수정된 파일을 minseoksong.github.org에 copy

3. minseoksong.github.org을 commit

--
색상 변경

https://visme.co/blog/website-color-schemes/
46. Corporate and Serious


bootstrap.scss 변경

backgroud
#222 ==> #265077

Table
#303030 ==> #022140

A (link)
#00bc8c ==> #12C998


Hover
#007053 ==> #14A098

Red
#e74c3c ==> #C34271
#e12e1c ==> #CB2D6F

--


Make pages
sudo bundle exec jekyll serve


Bundle problem: 
bundle config build.thin --with-cflags="-Wno-error=implicit-function-declaration"

Update publications

>>CV>>ref.bib
>>papers>> put pdf files

