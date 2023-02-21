#### 脚本功能：

```
1、通过Github Action自动定时运行[checkin.py](https://github.com/hbstarjason/glados-checkin/blob/master/checkin.py)脚本。

2、通过cookies自动登录（[https://glados.rocks/console/checkin](https://glados.rocks/console/checkin))，脚本会自动进行checkin，可实现多个账号签到。

3、然后通过“pushplus”（[https://www.pushplus.plus/](https://www.pushplus.plus/))，自动发通知到微信上。
```

#### 使用方法：

```
1. *在自己的仓库`Settings`里创建3个`Secrets`，分别是：（不开启通知，只需要创建COOKIES即可）*

2. *COOKIES（**必填**）*

3. *SERVE（推送开关，off关闭通知，填on的话，会同时开启cookie失效通知和签到成功通知）*

4. *SCKEY（填写pushplus的token，不开启则不用填）*
```





##### PS：有多个glados账号时，在变量COOKIES里使用`&&`分割不同的账号的cookie，不需要空格换行等。
