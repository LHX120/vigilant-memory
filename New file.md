#### 12 June, Friday
Import  random\
teather = ['a','b','c','d','e','f','g','h'] \
offices = [[ ],[ ],[ ] ]\

for name in teather:\
    # 列表追加数据的方法 --append(选中,追加整体) extend（拆开的） insert（指定追加）\
    # xx[0] --不指定是具体某个下标 --随机\
    num = random.randint(0,2)\
    offices[num].append(name)\

for office in offices:\
    # 打印办公室人数 -- 子列表数据的个数 len()\
    print(f'办公室的人数{len(office)}',老师分别是:)\
    for name in office:\
        print\
