# git-alias
```bash
[alias]
	o = checkout
	c = commit
	m = merge
	l = pull
	p = push
	s = status
	b = branch
	a = add
	g = log
	w = switch
	f = format-patch # 生成补丁
	y = apply # 打入补丁
	c-super = commit --amend # 更新最近的commit
	c-no-super = commit --no-verify # 绕过检查提交
	r-super = reset --soft # 回滚版本
	p-super = push --force-with-lease # 强制推送
