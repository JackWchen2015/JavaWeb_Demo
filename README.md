# HelloJavaWeb

## MVCLoginDemo

### sql语句

```sql
DROP TABLE IF EXISTS user;
CREATE TABLE user(
userid VARCHAR(30) PRIMARY KEY,
name VARCHAR(30) NOT NULL,
password VARCHAR(32) NOT NULL);

INSERT INTO user(userid,name,password)VALUES('admin','administrator','admin');
```