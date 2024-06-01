# 使用指南

## 主要功能
- 快速修改实体名称 - `fd:name`
- 快速控制实体名称是否永久显示 - `fd:holo`&`fd:holo_off`
- 快速生成盔甲架实现的悬浮文本 - `fd:new_holo`

## 用法

### 修改实体名称
```
execute as <entity> run function fd:name {jtxt:<JsonText>}
```

### 控制悬浮文本显示
```
execute as <entity> run function fd:holo
execute as <entity> run function fd:holo_off
```

### 生成悬浮文本
会在你当前所在位置生成隐形盔甲架，该盔甲架无敌、不可见、不受重力影响。
```
function fd:new_holo {jtxt:<JsonText>}
```