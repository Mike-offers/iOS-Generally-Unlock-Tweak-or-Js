# Satella Jailed
*在iOS系统为12-16的未越狱的设备上免费应用内购买*

Satella Jailed只用作教育用途， 我不会对任何因使用此工具而引致的非法行为负责。 此仓库上不分发任何版权材料.拥有数字版权法的律师可以见鬼去了.

# 安装
目前有三种安装Satella Jailed的官方方法，但它应该与其他补丁工具一起使用。

## 脚本 (需要电脑)
1. 在终端运行
     `git clone https://github.com/Paisseon/SatellaJailed.git && cd SatellaJailed`
2. 将IPA文件移动到生成的SatellaJailed文件夹中
3. 在macOS上用`sh patch-mac.sh`或在Linux和WSL上用`sh patch-linux.sh`
4. 在你未越狱的设备上侧载装上打过补丁的IPA

## Azula (Mac 或 设备上)
如果您使用TrollStore，请确保启用了URL scheme，并启用code signature slicing。或者只是用多巴胺越狱并使用调整版本 🙃

1. 从这个仓库下载SatellaJailed.dylib
2. 将SatellaJailed.dylib和目标IPA移动到文件应用程序中的Azula文件夹中
3. 在Azula中选择它们
4. 点击Patch按钮

## 轻松签 (设备上)
1. 从这个仓库下载SatellaJailed.dylib
2. 在签名->更多设置中，导入SatellaJailed.dylib
3. 确保使用“@executable\_path”和“Frameworks”
4. 签署并安装补丁后的IPA

# 使用方法
只需尝试购买，然后取消确认弹出窗口（上面有你的Apple ID），这样你就不用付款了。

默认情况下，核心功能是启用的。如果它不起作用，并且您使用的是iOS 15+，您可以尝试通过点击紫色星星来尝试启用高级功能。

请注意，Satella Jailed并非适用于所有应用。如果各种设置组合都无法破解购买，那你就倒霉了。
