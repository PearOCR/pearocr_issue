# pearocr_issue
This repository is currently only used for issue tracking for https://pearocr.com
此仓库仅用于为pearocr提供BUG反馈和建议


## V2.0
1. 优化界面，适配小屏幕，在小窗口和移动端浏览器下有更好的体验
2. 修正功能改为小窗模式，点击对应文本可弹出小窗对照修改
3. 增加日文韩文的识别
4. 修复无法识别透明背景图片的问题
5. 批量导入图片的顺序改为按文件名排序
6. 增加导出为TXT文件功能
7. 优化纯文本的排版效果
> 由于PWA缓存机制，更新后第一次打开还是上一版本，等缓存完毕再次刷新即可使用最新版

## v1.2
增加批量导出，可以导出所有图片到一个PDF文件（感谢cmldyu的建议）
修复长图无法识别的问题（感谢313069365提出的issue）
修复Firefox无法从剪贴板读取图像的问题，由于Firefox限制，只能主动使用粘贴键来加入图片（感谢Landius提出的issue）
增加忽略置信度低的字符设置（感谢Borber提出的建议）
增加识别语言[繁体中文，英文]，虽然其他语言也能识别英文，但在纯英文图像的场景下使用英文识别更准确。
增加显示语言[繁体中文，英文]
增加重新识别的按钮，切换识别语言后，已识别过的图片需要主动重新识别才能以新的语言识别

## v1.1
增加PWA机制
增加文本背景色和颜色设置
