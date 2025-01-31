# NUIST_HealthyReport_CAPTCHA
## NUIST健康打卡带验证码版

**由于政策调整，本项目已完成其历史使命，不再具有任何实际用途，感谢大家的Commits和Stars**

基于GitHub项目：https://github.com/dsus4wang/NUIST_AutoDailyHealthReport 大量修改而来，支持验证码识别，无需手动抓包修改FormData，操作更简单。

### 2022-3-16更新

系统更换本版本失效，如需新版请移步：https://github.com/InfinityWei/NUIST_HealthyReport_NEW

### 2021-10-4更新

利用muggle_ocr初步解决了近期学校统一认证添加强制验证码的逻辑，现可正常登陆填报

验证码识别基于南京大学校园网登陆脚本项目：https://github.com/cubiccm/NJU-Network-Authenticate

### 特别提醒

这里仅实现了健康日报的单次自动提交，一定程度上可以节约**身体健康的同学**填报健康日报的时间，但**请不要隐瞒自己的健康状况！**

**因隐瞒自身健康状况导致的一切后果，本项目一概不负责！**

### 使用前

请将83行和84行的username和password分别修改为自己的学号和信息门户密码

```python
username = '请修改此处为学号'
password = '请修改此处为密码'
```

### Windows系统

系统需安装好Python3.8以上，pip

CMD或者PowerShell进入目录

```powershell
cd E:\Desktop\DailyHealthReport
```

安装Python依赖，需要的依赖都已经列在requirements.txt里

```powershell
pip install -r requirements.txt
```

py运行run.py文件

```powershell
python run.py
```

### Linux系统

Linux系统比较类似，注意Python版本需要3.8以上，否则可能无法正常使用tensorflow，造成验证码无法解决。



**因隐瞒自身健康状况导致的一切后果，本项目一概不负责！**

