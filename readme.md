回程路由测试指令
# testrace
[![Build Status](https://github.com/nanqinlang/SVG/blob/master/build%20passing.svg)](https://github.com/nanqinlang-script/testrace)
[![language](https://github.com/nanqinlang/SVG/blob/master/language-shell-blue.svg)](https://github.com/nanqinlang-script/testrace)
[![author](https://github.com/nanqinlang/SVG/blob/master/author-nanqinlang-lightgrey.svg)](https://github.com/nanqinlang-script/testrace)
[![license](https://github.com/nanqinlang/SVG/blob/master/license-GPLv3-orange.svg)](https://github.com/nanqinlang-script/testrace)

A convenient script to test your server's speed that links to nodes in China

based on [bestrace](http://www.ipip.net)

## Usage
no much things to explain  
cuz it's a script with Chinese language

just one thing... you must run it with `bash`  
like
```bash
wget https://raw.githubusercontent.com/brozh85/testrace/master/testrace.sh
bash testrace.sh
```

it's the best to say nothing !

## according
https://github.com/nanqinlang-script/testrace/wiki

简介
这是一个用于在Linux上测试回程路由的脚本，这里的回程路由是指从你的机器出发到指定节点的路由。
在运行脚本后，会出现三个选项供以选择：

选择一个节点进行测试
四网路由快速测试
手动输入ip进行测试

选项说明：

1、选择一个节点进行测试
本脚本以内置移动/联通/电信/教育网四网的多个节点。
选择1回车后，会列出这些节点的列表。
选择其中一个测试完成后，可以继续选择节点测试。
2、四网路由快速测试
此模式会对以下几个节点进行回程路由测试。
此模式测试的节点包括：
电信
上海电信(天翼云)
厦门电信CN2
联通
浙江杭州联通
移动
浙江杭州移动
教育网
北京教育网
3、手动输入ip进行测试
此模式是由用户 手动输入要测试的目标ip
每次测试完成后，可选择继续测试其它ip

相关目录
脚本的安装目录位于/home/testrace。
测试完成并退出脚本后，会生成测试的记录文件于/home/testrace/testrace.log。
