# LINUXDO ReadBoost

[LINUXDO ReadBoost](https://greasyfork.org/scripts/519843-linuxdo-readboost)，一款润物细无声的脚本，解放双手，自动化刷取LINUXDO论坛的已读帖数  
开源、温和，支持自定义参数，理论支持所有使用Discourse程序的论坛  
⚠️：使用第三方脚本，存在失效、封号等潜在的风险，作为一款完全开源的脚本，支持使用者自行审核，请勿将脚本用于商业用途，开发者不对造成的后果负责 ，

---

## 如何使用

安装脚本后，只随意打开一个LINUXDO论坛的帖子，并在弹窗中同意使用许可，即可在右上角找到ReadBoost的设置菜单和指示栏

在默认情况下，脚本设置为`手动`模式，建议在设置菜单中勾选自动运行选项，并保持默认的设置参数，点击保存即可观察到脚本指示栏中出现运行状态

## 安全性

[LINUXDO ReadBoost](https://greasyfork.org/scripts/519843-linuxdo-readboost) 完全免费、开源，使用者可以自由查看并判断风险，开发者不对任何风险负责，也不对任何功能承诺，使用者需要自行承担使用该脚本的后果  
本脚本无意主动与论坛的检测机制对抗，可能存在一定潜在的的检测特征


## 高级选项

⚠️：除非你非常清楚的知道自己在做什么，否则不建议修改高级设置  
⚠️：建议保持默认设置，如果你希望提高速度，建议优先略微调整每次请求阅读量而非延迟，尽可能减少网络请求对服务器的影响  

- 基础延迟：每次请求发起的间隔，也可能会在别的地方生效  
- 随机延迟范围：为基础延迟添加一些波动
- 最小/大每次请求阅读量：每发起一个网络请求，会增加多少阅读数量的范围
- 最小/大阅读时间：每个回帖的阅读时间

## 待解决/待添加的功能

- [ ] 夜间模式下没有完全跟随论坛配色
- [ ] 菜单添加重试的细节参数
- [ ] 回帖ID和回帖总数不完全对应时，会导致整个帖子没有被100%刷完（猜测是存在删帖）

## 其他说明

开发不易，如果你想基于这个脚本二次开发，或者参考了其中比较多数量的代码，请添加一个来源声明，感谢使用！
