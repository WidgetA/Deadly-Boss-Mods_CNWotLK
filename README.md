# Deadly-Boss-Mods_CNWotLK
Personal modified version

Start From [Deadly Boss Mods 11.1.10](https://www.curseforge.com/wow/addons/deadly-boss-mods)

# 修改原因
国服怀旧服目前插件接口的版本和海外插件接口版本不一致，导致海外 WLK 可用的插件无法在国服使用，或者有各种报错。

## Change Log
### 2025/3/31
- DBM-Core 中，国服调用变量中缺失`isWrath`的判定值，手工以猴子补丁的方式添加，并且检测为国服时，对 `GetTalentTabInfo` 方法的返回值进行修改。
