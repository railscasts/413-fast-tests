# RailsCasts Episode #413: Fast Tests

http://railscasts.com/episodes/413-fast-tests

Requires Ruby 1.9.2 or higher.


### Commands used in this episode

```
time bundle exec rake spec:models
time bundle exec rspec spec/models
bundle binstubs rspec-core
time bin/rspec spec/models
zeus start
time zeus test spec/models
SLOW_SPECS=true rspec spec/models
rspec -p spec
rake parallel:create
rake parallel:prepare
zeus-parallel_tests init
zeus parallel_rspec spec
guard
bin/rspec spec/lib
```
