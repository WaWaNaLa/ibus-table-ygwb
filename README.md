阳光五笔:日志

文件素材来源

使用框架:ibus-table

文件规范:使用template.txt模版,改写为ygwb.txt

生成文件:ibus-table-createdb -s ygwb.txt -n ygwb.db

坑:rm .ibus/tables/*.db 一定要删除

初次使用centos7,五笔输入法移植只是试试,随便在template.txt添加了一些测试内容,测试成功后.没想到这些测试的东西全部以文件保存起来,怎么也删除不掉,最后看源码,发现在用户目录下.ibus/tables/ *.db文件 要手动删除.
