# 360QVM_bypass

在攻防演练过程中，木马钓鱼是十分重要的一环，但钓鱼马易被提取hash进而失效，本脚本旨在减少重复性工作，批量生成钓鱼马

360会对不携带资源的可疑程序进行拦截，标签为`HEUR/QVM202.0.29xx.Malware.Gen`

![image](https://github.com/Pizz33/360QVM_bypass/assets/88339946/6b287357-bd77-436f-93b3-bc63d6475638)

直接提取图标添加至exe一样会进行拦截

![image](https://github.com/Pizz33/360QVM_bypass/assets/88339946/c803d4c9-ff89-4f6b-8760-198876e68d2d)

使用方法：

把免杀马命名为`test.exe` 运行脚本`python icon-exe.py -f ico_file`

（`ResourceHacker.exe`来源于互联网，不放心可自行替换）

![image](https://github.com/Pizz33/360QVM_bypass/assets/88339946/ba5c04a3-a1d4-4f20-a648-3495518d06ad)

脚本通过生成不同hash的ico并写入程序中，实现批量bypass360QVM

![image](https://github.com/Pizz33/360QVM_bypass/assets/88339946/2ea3a967-b845-435d-a806-85b28e838f7e)

实现效果

![image](https://github.com/Pizz33/360QVM_bypass/assets/88339946/6d3dcfac-7877-470b-b449-627ebc45554a)

