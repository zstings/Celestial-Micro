# 开局天道：这次我要微操
eu5 MOD

c:[国家TAG] eg: c:MNG // 指定国家大明
effect set_global_variable = { name = test_var value = 100 }
effect set_global_variable = { name = show_pinyin_window value = yes }
effect remove_global_variable = show_pinyin_window

刷新本地化文件
reload localization

控制台，输入 explorer
在弹出的 Object Explorer 窗口中，在 Providers 选择 data Types 选项。
找到Character, 能看到角色相关的所有函数，eg: GetName