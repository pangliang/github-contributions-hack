# contributions-hack

自己的github首页贡献图表是不是空空如也? 想象大神一样的有密密麻麻的提交吗? 往下看
![hack](https://raw.githubusercontent.com/liang8305/github-contributions-hack/master/hack.png)

Just for fun !!

##使用方法

1. fork这个项目
2. clone到本地, 进入目录运行:


		./contributions-hack.sh


3. push代码到github


##参数说明

	./contributions-hack.sh \
		--start=开始日期, 格式"YYYY-mm-dd", 默认从当前往前推365天
		--days=总天数, 默认365
		--commits=每天随机多少个提交, 默认5
		--author=提交者email, 默认当前git config user.email 配置值
		
##如何恢复

不像要了, 怎么办? 简单, 删掉这个fork的项目就可以了		
