# hello-world
此存储库用于练习 GitHub 流
#创建一个列表，其中包含一些你喜欢的游戏
games = ['王者荣耀','qq飞车','和平精英','穿越火线','地下城与勇士']
print(games)
#访问列表元素
print(games[0])
print(games[1].title())
print(games[-1])
#使用列表中的值
message = f"I like playing {games[1].title()}"
print(message)
#修改列表元素
games[2] = '英雄联盟'
print(games)
#在列表添加元素
games.append('qq炫舞')
print(games)
#在列表中插入元素
games.insert(2,'逆战')
print(games)
#从列表中删除元素
del games[5]
print(games)
#使用pop（）删除元素
popped_game = games.pop()
print(games)
print(f"I used to play {popped_game}")
#根据值删除元素
games.remove('穿越火线')
print(games)
#使用sorted（）对列表进行临时性排序
print(sorted(games))
#使用sort（）对列表进行永久性排序
games.sort()
print(games)
#倒着打印列表
games.reverse()
print(games)
#确定列表长度
print(len(games))
