# X2522 网卡 / Onload 软件包

用于 X2522 网卡相关安装与配置的软件包。

## 支持环境

- CentOS 7.9
- Ubuntu 22.04 Server

## 目录结构

```text
software-x2522/
├── README.md
├── Onload/
│   ├── RPM/
│   │   ├── onload-8.1.3.40-1.el7.x86_64.rpm
│   │   └── onload-kmod-3.10.0-1160.el7-8.1.3.40-1.el7.x86_64.rpm
│   └── DEB/
│       ├── onload-dkms_9.1.1.66-1_all.deb
│       └── onload-user_9.1.1.66-1_amd64.deb
└── SFUtils/
    ├── RPM/
    │   └── sfutils-8.3.3.1000-1.x86_64.rpm
    └── DEB/
        └── sfutils_8.3.3.1000-2_amd64.deb
```

## 使用建议

- CentOS 7.9：优先查看 `Onload/RPM/`
- Ubuntu 22.04 Server：优先查看 `Onload/DEB/`
- `SFUtils/` 存放对应的 SFUtils 工具包
