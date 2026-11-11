# Centuries End Exorcist / 世纪末驱魔人 — Alpha5

A supernatural action shooter set in an indoor playground. Take an exorcism assignment, combine firearms with Thunder Arts, choose treasure-room talismans, investigate evidence, and defeat a two-phase Boss.

接下儿童乐园的驱魔委托，组合枪械与雷法，探索宝箱房、选择法宝路线，收集证物并挑战两个阶段的 Boss。

**Downloadable desktop demo / 需下载到电脑试玩。English and Chinese included / 内含中英文。**

## Download / 下载

Choose your platform and download **all three files listed for it** into one folder. Do not rename the numbered parts. GitHub's automatic “Source code” downloads do not contain the game.

选择对应平台，将下面列出的 **三个文件全部下载到同一个文件夹**，不要修改分卷名称。页面自动提供的 “Source code” 不是游戏。

### Windows 64-bit

- [Alpha5-Windows-StartHere.zip](https://github.com/WetlandWitch/centuries-end-exorcist-demo/releases/download/v0.1.0-alpha.5/Alpha5-Windows-StartHere.zip)
- [Alpha5-Windows.zip.001](https://github.com/WetlandWitch/centuries-end-exorcist-demo/releases/download/v0.1.0-alpha.5/Alpha5-Windows.zip.001)
- [Alpha5-Windows.zip.002](https://github.com/WetlandWitch/centuries-end-exorcist-demo/releases/download/v0.1.0-alpha.5/Alpha5-Windows.zip.002)

### macOS — Apple Silicon / Intel

- [Alpha5-Mac-StartHere.zip](https://github.com/WetlandWitch/centuries-end-exorcist-demo/releases/download/v0.1.0-alpha.5/Alpha5-Mac-StartHere.zip)
- [Alpha5-Mac.zip.001](https://github.com/WetlandWitch/centuries-end-exorcist-demo/releases/download/v0.1.0-alpha.5/Alpha5-Mac.zip.001)
- [Alpha5-Mac.zip.002](https://github.com/WetlandWitch/centuries-end-exorcist-demo/releases/download/v0.1.0-alpha.5/Alpha5-Mac.zip.002)

## Install and play / 还原与启动

1. Extract the small **StartHere.zip**. Keep the numbered parts beside it, outside the extracted StartHere folder.
2. **Windows:** open `Assemble-Windows.cmd` in the extracted folder. It joins and verifies the files, then opens the assembled ZIP. Choose **Extract All** and launch the game from the extracted Windows folder.
3. **Mac:** open `Assemble-Mac.command` in the extracted folder. If it will not open, open Terminal, type `bash` and a space, drag that command file onto Terminal, and press Return. After assembly and verification, extract the ZIP, enter the Mac folder, and open the game ZIP inside it to extract the application.
4. Read `README_EN.txt` or `试玩说明.txt` for first-launch instructions and gameplay. Keep the complete game folder together.

先解压 StartHere 小压缩包，分卷放在它旁边。Windows 双击里面的 `Assemble-Windows.cmd`，合并成功后选择“全部解压”；Mac 打开 `Assemble-Mac.command`，若无法打开，可在终端输入 `bash` 和空格后拖入该文件并回车。Mac 解压合并包后，还需解压 Mac 文件夹里的游戏 ZIP。还原工具只合并本地文件并核对 SHA-256，不联网、不安装软件、不改系统设置。

During setup, allow about **18 GB free on Windows / 25 GB on Mac**. Use a local drive that supports large files, not FAT32. After extraction succeeds, you may remove the downloaded parts and intermediate ZIPs, keeping the complete extracted game folder.

## Before your first fight / 开局先看

- **I — Skill points:** start with 12 points. Each node needs **3/3** to work. Recommended: Performance Protocol plus the three first-tier active Thunder Arts, 3 points each.
- **C / X / Z:** assisted aim, stop enemies and their projectiles, and defensive counterattack. Unlock them first; their active effects cannot overlap.
- **Treasure rooms:** aim at both floating phones to compare rewards, then **shoot one** to choose. The other disappears. Talismans alter your gunfire and can be upgraded along different branches.
- **F10 — Playtester Menu:** optional invincibility, ammunition, equipment and exploration assists. Some keyboards and Macs require **Fn + F10**. Closing the menu does not disable enabled assists.

**I 加点：每个节点点满 3/3 才生效。** 推荐 12 点分给“绩效协议”和三个一阶主动雷法。C/X/Z 分别用于辅助瞄准、暂停敌人及投射物、防御反击。宝箱房瞄准两部手机查看奖励，再射击一部二选一。**F10 打开隐藏测试者菜单**，可辅助探索与体验装备；关闭菜单不会关闭已启用的辅助。

## Requirements / 运行环境

- Windows 10/11 64-bit, Intel/AMD with SSE4.2, DirectX 12 feature level 12_0 graphics.
- macOS 13 or later, Apple Silicon or a supported Intel Mac with suitable Metal 3 graphics.
- Suggested: 16 GB RAM, SSD, keyboard and mouse. No Godot installation or account needed. This demo is not playable in a web browser.
- Windows is unsigned; macOS is not Apple-notarized. Follow the included first-launch guide for trusted downloads. macOS has not yet been tested on a physical Mac.

Windows 10/11 64 位；Mac 需 macOS 13 或更新版本及兼容图形硬件。建议 16 GB 内存、SSD、键盘鼠标。无需安装 Godot 或注册账号。本版未做 Windows 发行者签名及 Apple 公证，首次启动请阅读说明。Mac 尚未完成实机试玩验证。

Credits and license links are included in **CREDITS.txt**. Original game content is not released under a blanket open-source license; third-party components retain their own terms.

For feedback, include Alpha5, your operating system, hardware, what happened, and which Playtester Menu assists were enabled.
