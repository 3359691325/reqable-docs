---
sidebar_position: 4
---

# 常见问题

**1. Mac系统无法打开软件安装包(dmg)或者应用本身**    
解决方案：这是开发者未认证导致的，执行以下命令解决
```
sudo spctl --master-disable
sudo xattr -r -d com.apple.quarantine xxx.dmg
# 拖入Applications文件夹后执行
sudo xattr -r -d com.apple.quarantine /Applications/Reqable.app
# 最后还原spctl
sudo spctl --master-enable
```