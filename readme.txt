集成以下插件
- LazyIDA
    移除不常用功能、与其他插件冲突功能
- patching
    移除内置 keystone，因为看它不顺眼，自己想办法安装吧
- ida-pro-mcp
    自己安装
    pip uninstall ida-pro-mcp
    pip install https://github.com/mrexodia/ida-pro-mcp/archive/refs/heads/main.zip
    ida-pro-mcp --install
- findcrypt-yara
    添加 sm4 支持...
- diaphora
    二进制 diff 工具，需要自己修改 diaphora_plugin.cfg
    适配 IDA Pro 9.2+