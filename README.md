# mybatis-sample
This application issues a SELECT statement using MyBatis and displays the result on the console.
There is no need to prepare clients such as MySQL and Oracle, because the database (H2) used this time is used in memory.

## Requirements
```
- Java 8+
```

## Table
```
+----+-------+---------+
| id | name  | country |
+----+-------+---------+
|  1 | Osaka | Japan   |
+----+-------+---------+
```

## Usage
```
$ ./gradlew bootRun
...
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.1.4.RELEASE)
...
1,Osaka,Japan
...
```

For details, please refer to the following link.

[Spring BootでMyBatisを使ってみる - Reasonable Code](https://reasonable-code.com/spring-boot-mybatis/)

## License
This software is released under the MIT License.
