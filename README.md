#pry+awesome_print+faker 사용하기 + Beta버전입니다.

##젬 설치

###/Gemfile
```
gem "pry-rails"
gem "awesome_print"
gem "faker"
```

###/.pryrc
```
# .pryrc
require "awesome_print"
AwesomePrint.pry!
```

###terminal
```
rails c
```
