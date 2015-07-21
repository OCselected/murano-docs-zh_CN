# murano-docs-zh_CN
OpenStack murano documents for Chinese, just po files.

# HowTo

 git clone http://github.com/openstack/murano
 
 cd murano/doc/source
 
 添加下面两行内容到conf.py
 
 locale_dirs = ['murano-docs-zh_CN/']   # path is example but recommended.
 
 gettext_compact = False     # optional.

 执行 $sphinx-intl build
 
 编译：
 
 make -e SPHINXOPTS="-D language='zh_CN'" html

注：Makefile 你可以参考fuel-docs，或者是sphinx-quickstart生成的。

Enjoy it! 
