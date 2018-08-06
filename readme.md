# Liferay and MySQL with docker-compose

Run mysql with command
`docker run -p 3306:3306 --name mysql57 -e MYSQL_ROOT_PASSWORD=salakala -d mysql:5.7`

Run export commands

`export LIFERAY_JDBC_46_DEFAULT_46_DRIVER_67_LASS_78_AME=com.mysql.jdbc.Driver`

`export LIFERAY_JDBC_46_DEFAULT_46_PASSWORD=salakala`

`export LIFERAY_JDBC_46_DEFAULT_46_URL='jdbc:mysql://localhost/lportal?characterEncoding=UTF-8&dontT'…`

`export LIFERAY_JDBC_46_DEFAULT_46_USERNAME=root`

Run liferay with command
`docker-compose up`
