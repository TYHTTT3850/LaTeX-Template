LaTeX自制模板。

文档格式为ctexart，可更改为ctexrp和或ctexbook。

常用命令行指令

```
# —— 版本与环境查看 ——
tex --version            # TeX 发行版
latex --version          # LaTeX 内核
tlmgr --version          # TeX Live 管理器

# —— 宏包管理（TeX Live） ——
tlmgr search <pkg>       # 搜索宏包
tlmgr info <pkg>         # 查看宏包信息/是否安装
tlmgr install <pkg>      # 安装宏包
tlmgr remove <pkg>       # 卸载宏包

# —— 更新（TeX Live，强烈建议） ——
tlmgr update --self
tlmgr update --all
tlmgr update <pkg>       # 只更新指定宏包

# 切换清华镜像
tlmgr option repository https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/tlnet
tlmgr update --self --all
```

