# Linux Base Operations

### 1.Vi/Vim

[2]yy 			  ： 复制2行

[5]p 				：黏贴5行

dd				   ：删除该行

I/i O/o A/a     ：插入  Esc退出 

u					 ：撤销 

ctrl+r			   ：取消撤销

^						：行首 

$						：行尾

ctrl+f ctrl+b   ：快速前后翻页

[100]G			: 跳转到100行





### 2.尾行模式

:q(!) 					 ：退出（强制）

:set number	   ：设置行号 -> :set nonumber

:x(!) 					  ：（强制）保存退出

:s    					  ：保存

:50 					  ：跳转50行

?Hello /Hello 	 ：向下/上查找    n：查找下一个 N逆向查找下一个  \c:不区分大小写

:1,5s/old/new/g ：1-5行全局替换



### 3.常用命令

ls -l -a 										:显示目录及隐藏文件详细信息

ls -ltri				 						 :查看文件inode及其各种信息

du												:查看当前目录文件和目录大小

rm 					  						:删除文件

cat												:查看文件内容

ln[-s] [a.txt] [b.txt]					:创建a->b软/硬链接

chmod (u/g/o)+/-x file		  	 :给(user/group/other用户)操作文件加/减权

echo 	"	"	>		1.txt			:输出(重定向)

vim 1.txt									:新建/打开文件

cd  ../..  /  - /home/root			:切换目录

cp 源文件 目标文件 				  ：复制文件

cp -r 源目录 目标目录				：批量复制

mkdir	dir							  	:创建目录

mkdir -p /dir1/dir2					:创建多级目录

rmdir	dir									:删除目录

rm -r     dir									：批量删除

 

