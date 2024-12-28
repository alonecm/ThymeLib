# ThymeLib：一个百度Algodoo吧官方Thyme脚本库集合，免费使用！
### 只可转载不得买卖，转载记得写明出处！如果你是以收费方式取得的，请立即向出售方申请退款！！

### ExCore库使用说明:

#### 1.扩展型for：extendFor(exeBlolowerk,upper,lower)

exeBlolowerk：执行块,
upper：循环次数上限,
lower：循环次数下限

#### 2.窄xFor循环：sFor(lower, upper, code) 

说明：取不到上限且不会多执行一次的循环

code：执行块,
upper：循环次数上限,
lower：循环次数下限

#### 3.二分循环：xFor(lower, upper, code) 

说明：一定能执行一次且能取到上限

code：执行块,
upper：循环次数上限,
lower：循环次数下限

#### 4.宽xFor循环：wFor(lower, upper, code) 

说明：取得到上限且不会多执行一次

code：执行块,
upper：循环次数上限,
lower：循环次数下限

#### 5.可中断xFor循环：bFor(lower, upper, code) 

说明：取不到上限且不会多执行一次,允许带有条件退出,条件语句在写的时候要写到code块内的结尾,若需要使用索引中断则索引应该+1后进行比较,不建议使用索引中断

code：执行块,
upper：循环次数上限,
lower：循环次数下限


### SimplePID库使用说明:

#### 1.PI控制：PIcontrol(targetValue,targetObject)

targetValue：表示目标值

targetObject：表示需要控制的值

函数返回值：返回一个经过PI调整过的值

#### 2.PD控制：PDcontrol(targetValue,targetObject)

targetValue：表示目标值

targetObject：表示需要控制的值

函数返回值：返回一个经过PD调整过的值

#### 3.PID控制：PIDcontrol(targetValue,targetObject)

targetValue：表示目标值

targetObject：表示需要控制的值

函数返回值：返回一个经过PID调整过的值

#### 4.内置参数调整模板函数：template(mode)

mode：表示模式的编号，这里的编号分别是0、1、2三个数字，每个数字对应的使用情况不同，应该在使用时根据情况更改

#### 控制器对象参数介绍：
ki:积分控制系数,
kd:微分控制系数,
kp:比例控制系数


