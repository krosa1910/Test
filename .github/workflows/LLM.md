# LLM Usage Log (minimum requirements)
 ## Question 1 (date/time)
3 - Goal:帮我检查jpynb文件内的问题，比如是否有命名，格式等错误
4 - Prompt summary:给它一段代码让它检查，或者给它报错信息
5 - Model/version (if known) and settings (temperature/top_p if applicable): Gemini3.0Pro
6 - Output used (what parts): （a）-（c）
7 - Verification steps (tests, derivations, sanity checks): 简单的把它的一些结论Ctrl+C Ctrl+V到，然后观察运行结果（是否报错，是否符合预期（
8 - What was corrected ｜ rejected and why:

9它成功发现了我好几处出现的数据结尾问题（最近经常写从1开始的语言，会忽视python从0开始）｜它的代码一般不考虑可复现性，seed都是我自己制定的
 ## Question 2 
3 - Goal:（c）部分梳理架构
4 - Prompt summary:告诉它一张（c）的截屏和它一起头脑风暴然后看哪些好写
5 - Model/version (if known) and settings (temperature/top_p if applicable): Gemini3.0Pro
6 - Output used (what parts): （c）
7 - Verification steps (tests, derivations, sanity checks): 也不知道说什么，它的很多输出直接有引用书上的内容，这点挺好的
8 - What was corrected ｜ rejected and why:

9  大部分都接受了，小部分感觉它写复杂了，我自己写的简单点
 ## Question 3
3 - Goal:（d）设计伪代码
4 - Prompt summary:多次尝试将我自身写的伪代码给（d），让LLM改进其格式一致性，并减少不必要的变量定义等
5 - Model/version (if known) and settings (temperature/top_p if applicable): Gemini3.0Pro
6 - Output used (what parts): （c）
7 - Verification steps (tests, derivations, sanity checks): 这个就只能自己判断了，没什么很好的办法
8 - What was corrected ｜ rejected and why:

9  整体是它和我都反复修改最终给出结果吧
 ## Question 4
3 - Goal:（d）部分设计框架
4 - Prompt summary:完整建设一个LLM模型的原型还是有点太难了，我承认这是我最依赖LLM的一道题，毕竟解铃还需西陵人
5 - Model/version (if known) and settings (temperature/top_p if applicable): Gemini3.0Pro
6 - Output used (what parts): （c）
7 - Verification steps (tests, derivations, sanity checks): 没办法，真看不懂只能信
8 - What was corrected ｜ rejected and why:

9  基本完全采纳它的说法了
