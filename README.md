# Database centric cloud solution on Alibaba Cloud

| Solution | Description | Related Cloud Services | Resources Links |
| :------: | :---------: | :--------------------: | :------------: |
| [Cloud Native WordPress on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-cloud-native-web-hosting) | Quick start with Wordpress on Alibaba Cloud with cloud native features such as high availability, auto-scaling, etc. | EIP, SLB, ECS, ESS, Redis, PolarDB MySQL | :custard: [Project](https://github.com/alibabacloud-howto/solution-cloud-native-web-hosting) <br> :clapper: [Video Tutorial Part 1](https://www.youtube.com/watch?v=TnWaGHBxPuw) <br> :clapper: [Video Tutorial Part 2](https://www.youtube.com/watch?v=POQ_nxjnIYM) <br> :beginner: [Solution page on Alibaba Cloud](https://www.alibabacloud.com/architecture/solution-implementation/building-auto-scaling-wordpress-website-on-alibaba-cloud) |
| [Scoreboard of Rose Bowl Games powdered by Redis & MySQL - Use Terraform To Provision All Resources](https://github.com/alibabacloud-howto/solution-mysql-redis-cache-simple) | The simplest solution for RDS MySQL database caching with Redis. This solution relies on the expiration time (TTL) of the key in Redis. Redis will not be updated proactively when MySQL is updated. This approach is simple to implement, but the inconsistency duration may be very long especially for the scenario that the read request is very frequent and the expiration time is relatively long, a lot of long-term dirty data will be generated. | ECS, Redis, RDS MySQL | [Project](https://github.com/alibabacloud-howto/solution-mysql-redis-cache-simple) <br> :clapper: [Video Tutorial](https://www.youtube.com/watch?v=POQ_nxjnIYM) <br> :beginner: [Solution page on Alibaba Cloud](https://www.alibabacloud.com/architecture/solution-mysql-redis-cache-simple) |
| [Redis Data Synchronization with RDS MySQL Using Canal & Kafka](https://github.com/alibabacloud-howto/solution-mysql-redis-canal-kafka-sync) | This solution uses Kafka and Canal to achieve data synchronization between RDS MySQL and Redis. | ECS, RDS MySQL, Redis, Kafka, Canal | :custard: [Project](https://github.com/alibabacloud-howto/solution-mysql-redis-canal-kafka-sync) <br> :clapper: [Video Tutorial](https://www.youtube.com/watch?v=O-GoA6182mI) <br> :beginner: [Solution page on Alibaba Cloud](https://www.alibabacloud.com/architecture/solution-mysql-redis-canal-kafka-sync) |
| [Deploy MongoDB Instances in Multiple Regions Automatically Using Terraform](https://github.com/alibabacloud-howto/solution-mongodb-multiregion-sync) | Using MongoShake deployed on ECS to one-way synchronize 2 MongoDB deployed in 2 regions respectively. | ECS, MongoDB, MongoShake | :custard: [Project](https://github.com/alibabacloud-howto/solution-mongodb-multiregion-sync) <br> :clapper: [Video Tutorial](https://www.youtube.com/watch?v=k6zUZcw6CU4) |
| [Create Online Game Leaderboard on Redis](https://github.com/alibabacloud-howto/solution-online-leaderboard-redis) | Leaderboard sample for Gaming on cloud. This sample contains the Terraform scripts to provision an ECS and a Redis instance on Alibaba Cloud region, also there is a sample for setting up Java development environment on ECS and running a Leaderboard. | ECS, Redis | :custard: [Project](https://github.com/alibabacloud-howto/solution-online-leaderboard-redis) <br> :clapper: [Video Tutorial](https://www.youtube.com/watch?v=LMsMqYz9ik8) |