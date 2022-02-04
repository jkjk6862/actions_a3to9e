# Actions A3TO9E
 
**如何使用a3to9e转换a3包成cc9e可用的刷机包**

* 登录你的github,fork这个项目到你的github

* 创建 token
  # 进入settings -- Developer settings -- Personal access tokens -- Generate new token -- note填写RELEASE -- Expiration改为No expiration -- Select scopes全部勾选 -- 点击Generate token创建token -- 复制得到的token令牌

* 创建 secret
  # 进入你的Actions_a3to9e,项目 -- settings -- Secrets --  Actions -- New repository secret -- Name填写RELEASE -- Value填写刚刚复制的token

* 使用actions_a3to9e
  # 进入你的Actions_a3to9e项目 -- Actions -- Select workflow -- 选择a3to9e -- 右边点击Run workflow -- ROM LINK填写需要转化的a3包直链 -- 点击Run workflow -- Actions执行完成后会把包上传到Release页面，去那里下载就行
