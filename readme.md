Run mysql with command
`docker run -p 3306:3306 --name mysql57 -e MYSQL_ROOT_PASSWORD=salakala -d mysql:5.7`

Run sql command in mysql cli (is this actually needed?)
`create database lportal character set utf8;`

Run export commands
`export LIFERAY_JDBC_46_DEFAULT_46_DRIVER_67_LASS_78_AME=com.mysql.jdbc.Driver`
`export LIFERAY_JDBC_46_DEFAULT_46_PASSWORD=salakala`
`export LIFERAY_JDBC_46_DEFAULT_46_URL='jdbc:mysql://localhost/lportal?characterEncoding=UTF-8&dontT'…`
`export LIFERAY_JDBC_46_DEFAULT_46_USERNAME=root`

Have to also include the "portal-setup-wizard.properties"

Run liferay with command
`./startup.sh`


