<p dir='rtl' align='right'><a href="">index <-</a></p>

## status

### Lv.0

命令：`git status`

效果：知道当前什么改动被 staged 了，什么改动没有（staged 就是将要被包含在下一个 commit 里的）
	
示例：![[Pasted image 20210926113815.png]]
	
### Lv.1
	
可选扩展
	
- -s / --short
	简化版 可好看了
	![[Pasted image 20210926115032.png]]
- 
	
status 和 log 的区别
	
![status 和 log 的区别](https://wac-cdn.atlassian.com/dam/jcr:52d530ce-7f51-48e3-920b-a18f776048d3/01.svg?cdnVersion=1819)
	
status 并不能知道已经 commit 的事儿，只能知道本地还未 commit 的修改
	
#### 相关链接
[Git Status: Inspecting a repository](https://www.atlassian.com/git/tutorials/inspecting-a-repository#:~:text=The%20git%20status%20command%20displays,regarding%20the%20committed%20project%20history.)
