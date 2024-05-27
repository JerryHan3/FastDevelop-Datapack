# 使用指南

## 主要功能
- 快速修改实体名称 - `fd:name`
- 快速控制实体名称是否永久显示 - `fd:holo`&`fd:holo_off`

## 用法

### 修改实体名称
```
execute as <entity> run function fd:as_name {jtxt:<JsonText>}
```

### 控制悬浮文本
```
execute as <entity> run function fd:as_holo
execute as <entity> run function fd:as_holo_off
```