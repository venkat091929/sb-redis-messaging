# sb-redis-messaging
pub sub messaging with redis

1. Redis installation with brew
  $ brew install redis
  # verify installation  
  $ brew doctor
  # Start redis server 
  $ ./redis/4.0.2/bin/redis-server
  # CLI client  
  $ ./redis/4.0.2/redis-cli
   $ > set hello-key 'welcome to redis'
   OK
   $ > get hello-key
   "welcome to redis"
   
  
References:http://projects.spring.io/spring-data-redis/
