Response to [Home · HeRaNO/xcpc-team-reg Wiki (github.com)](https://github.com/HeRaNO/xcpc-team-reg/wiki)

---

### login.html

网页入口，无需鉴权，处理用户登录请求

### register.html

无需鉴权，处理用户注册

### reset.html

无需鉴权，处理用户忘记密码的重置密码请求

### contestinfo.html

权限：已登录用户

显示个人信息、已加入的队伍信息，加入、退出队伍、changeinfo, modifyteam, createteam, 只能从该页面登出

account 和 password 一开始默认为 (Waiting for admin)，直到管理员分配

### changeinfo.html

权限：已登录用户

修改个人信息

### modifyteam.html

权限：已登录用户 & 用户加入了 team

更改当前队伍名称

### createteam.html

权限：已登录用户 & 未加入任何 team

创建新的队伍

### jointeam.html

权限：已登录用户 & 未加入任何 team

加入队伍