1. docker-compose build
2. docker-compose up -d
3. docker-run -it jorge07/redis-trib sh -c "echo 'yes' | ./redis-trib.rb create --replicas 1 localhost:7001 localhost:7002 localhost:7003 localhost:7004 localhost:7005 localhost:7006"