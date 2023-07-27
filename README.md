# login-and-register-nest
使用 Nest + MySQL + TypeORM 实现的登录注册模块

- `jwt-mysql-typeorm`：使用 `jwt` 实现的登录注册
- `seesion-mysql-typeorm`：使用 `session + redis` 实现 `ACL` 权限控制
- `rbac`：使用 `jwt` 实现的 `rbac` 权限控制
- `refresh-token`：使用 `access-token` 和 `refresh-token` 实现**无感登录**
- `seesion-distributed-redis`：读取 `redis` 中 `session` 数据，实现分布式