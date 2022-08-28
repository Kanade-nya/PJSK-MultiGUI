# PJSK-MultiGUI
**更快、更简单的进行语音合成**  v1.0.0
## 下载地址
### 本体
- github的release版本
- [本体下载（Google云端硬盘）](https://drive.google.com/file/d/1xmlsc0oAdO6BWBPJG_0sPfRyeNWS9P7h/view?usp=sharing)
### 预训练模型
[ichika](https://drive.google.com/file/d/1_P_2U0TC1U_T3lxxxVW3TuKJ45l2w4Cm/view?usp=sharing)
[saki](https://drive.google.com/file/d/1zB09x-7qSe-abyxH8NIUZ7lCSYQ4UfEp/view?usp=sharing)
[airi](https://drive.google.com/file/d/1uWeixKe5PEz4mGhjS9K8Z8d1AJpv2izO/view?usp=sharing)
[mizuki](https://drive.google.com/file/d/1e43kk2SWAeh3EPMAsW-bDdVROsW7VVa8/view?usp=sharing)
[ena](https://drive.google.com/file/d/1sL9VjWAjPWAS2ilACqcR5WHLCjcF1u4k/view?usp=sharing)
[mafuyu](https://drive.google.com/file/d/1it_vKoFDVryxzjRbglYvMy6vi2tXTKoO/view?usp=sharing)
[kanade](https://drive.google.com/file/d/16K_R_AWC5tELDpRYaA6DLYucYqfcoho2/view?usp=sharing)
[mmj](https://drive.google.com/file/d/1dp1BFS0MHt6_8ZaKkMOPiU2P8yYsKJwY/view?usp=sharing)
## 关于授权（重要）
- 欢迎同人二创作品，不需要授权，但是请勿将语音合成结果直接用于商业目的。
- 二创作品请**注明基于语音合成，并标注语音合成出处**->（B站源视频），并且**禁止**制作会造成对角色产生不良影响的作品。避免造成不必要的误会。

## 使用方法
- clone当前项目到本地，获得config文件
- 按顺序选择config，pth文件
- 选择角色点击确定（只有mmj是四目标）
- 输入文本，生成后点击播放。可以多次生成选择较好的结果保存

## 常见问题
- **第一次生成时被卡住？**
第一次使用的时候需要从github上下载大约22M左右的压缩包，推荐第一次生成时挂上梯子，不然会很慢。之后就不用了
- 闪退？
可能出现的问题见下方，如果不能解决您的问题，可以留下Issues，我会尝试解决

## 注意
- 黑白mfy效果时好时坏，谨慎使用
- 播放**点一次就行！**
- 语速调节值**越大**语速**越慢**
- 虽然理论上config文件可以复用，但是config是获取当前角色的手段，所以请一一对应
- 根目录下的playSounds文件夹是为了解决一个小问题而生成的文件夹，打开有可能卡顿，在程序使用结束后可以直接删除
- 保存的音频文件在results文件夹中

## 闪退问题解决方案
- 请按顺序选择config与pth文件
- 不同的模型可以使用的标点符号不太相同，查看是否使用了未设定的标点（主要原因）
	**——同时尝试不同的标点符号也是改变语气的好方法**
	- saki,airi,mzk,knd:!"&*,-.?{}~
	- mmj,ena:_,.!?-~…
	- ick,mfy:_,.!?-
- 输入新的语句
	
## 致谢
ick,mfy模型提供者：没人理 [-Bilibili空间-](https://space.bilibili.com/618272)
knd模型提供者： 鲤鱼L1yuu [-Bilibili空间-](https://space.bilibili.com/436749613)
数据集提供者：涼风_青叶 [-Bilibili空间-](https://space.bilibili.com/5437778)
原vits-japanese项目提供者：[CjangCjengh](https://github.com/CjangCjengh) [-Bilibili空间-](https://space.bilibili.com/35285881)
vits原项目：[vits](https://github.com/jaywalnut310/vits)