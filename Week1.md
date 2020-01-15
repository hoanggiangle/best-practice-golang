
## Sync Database and Redis

  Xây dựng cơ chế kiểm tra đồng bộ database và redis cache
  Input: Kiểm tra *redisKey*
1. Tạo cache từ Database: **temp_**+ redisKey
2. Lấy dữ liệu từ Cache: redisKey
3. Gọi hàm kiểm tra có conflic data hay không
4. Xem log trên kibana



## Tham khảo:

[RedisFullCheck](https://github.com/alibaba/RedisFullCheck)

[channel-in-golang](https://www.geeksforgeeks.org/channel-in-golang/)
