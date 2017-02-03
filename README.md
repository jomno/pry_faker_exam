#pry+awesome_print+faker 사용하기 + Beta버전입니다.

##젬 설치

### Gemfile
```ruby
gem "pry-rails"
gem "awesome_print"
gem "faker"
```

### .pryrc
```
# .pryrc
require "awesome_print"
AwesomePrint.pry!
```

### terminal
```bash
rails c
```
### Faker
[stympy/faker](https://github.com/stympy/faker)
```ruby
Faker::Internet.free_email   #=> "freddy@gmail.com"
Faker::Name.name             #=> "Tyshawn Johns Sr."
```
