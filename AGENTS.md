# AGENTS.md

本项目为 [Starship](https://github.com/starship/starship) 的配置文件，双行风格，提供以下四种配置

- [Default](default.toml)：默认风格，使用 Nerd Font图标，因 Nerd Font 占用多格的特性需要在图标之后添加一个空格
- [Mono](mono.toml)：用于图标也是等宽的等宽字体，不需要空格
- [Emoji](emoji.toml)：使用 Emoji 图标
- [ASCII](ascii.toml)：仅使用 ASCII 编码支持的字符，用于兼容性环境

因布局与图标选择严重依赖人类审美，修改时除非某项已有明确的图标，不然禁止直接写入图标，添加新项目时应使用占位并提示用户选择图标
