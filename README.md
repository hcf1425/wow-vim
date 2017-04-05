## a simple show
![show](./show.gif)
## layout
![vim](./vim.png)

## support keys (you can diy keys in ~/.vim/vim/key.vim)

|key|info|说明|
|---|---|---|
|,|leader key|前缀键|
|,ll|open nerd tree on left|打开文件浏览器|
|,rr|open tag bar on right|打开符号浏览器|
|,gd|jump to the definition(c/c++/go)|跳转到定义(c/c++/go)|
|,fs|cscope find symbols(c/c++/go)|查找符号(c/c++/go)|
|,fa|cscope find in interactive(c/c++)|交互查找(c/c++)|
|,ft|cscope find strings(c/c++/go)|查找字符串(c/c++/go)|
|\<shift-right\>|cscope jump to next result|跳转到下一结果|
|\<shift-left\>|cscope jump to previous result|跳转到前一结果|
|<|open/close cscope result list|打开/关闭查找结果列表|
|\<shift-down\>|jump to next error|跳转到下一错误|
|\<shift-up\>|jump to previous error|跳转到前一错误|
|>|open/close error list|打开/关闭错误列表|
|,zi|fold/unfold all code bolcks|整体折叠|
|,za(or blank)|fold/unfold current block|局部折叠|
|//|comment/uncomment code|注释/反注释|
|\<tab\>|switch to next buffer|切换下一缓存|
|\<shift-tab\>|switch to previous buffer|切换前一缓存|
|,ff|auto format code|自动格式化|
|,tt|add/update your code title|添加/更新文件说明|
|...|...|...|


## support languages and features (1★=2☆)

|language(语言)|highlight(高亮)|autocomplete(补全)|syntax(查错)|snips(补全块)|jump(跳转)|todo(待改进)|
|---|---|---|---|---|---|---|
|c|★★☆|★★☆|★★|★★☆|★★|☆|
|cpp|★★☆|★★☆|★★☆|★★☆|★★|☆|
|golang|★★☆|★★☆|★★|★★☆|★☆|☆|
|java|★★☆|★★☆|★★|★★☆|★|★|
|lua|★☆|★☆|☆|★★☆|☆|★☆|
|python|★★|★☆|★★|★★☆|☆|★★|
|javascript|★|★★|☆|★★☆|☆|★★|
|html|★|★|☆|★★☆|☆|★★|
|php|★|★|☆|★★☆|☆|★★|
|...|...|...|...|...|...|...|

## plugins and resources path

this is a simple and powerful configuration of vim, you can diy your own vim base on it.
you can share some good plugins with me.

|path|info|
|---|---|
|~/.vimrc|entrance configuration|
|~/.vim/base.vim|base configuration|
|~/.vim/plugin.vim|plugins configuration|
|~/.vim/func.vim|function configuration|
|~/.vim/key.vim|key configuration|
|~/.vim/bundle/|plugin installed dir|
|~/.vim/colors/|colorscheme installed dir|
|~/.vim/snips/|snips collected dir|
|~/.vim/ycm/|.ycm\_extra\_conf.py dir|
|~/.vim/dicts/|dictionary dir|

## install

	git clone https://github.com/adwpc/vim.git
	cd vim
	
	#install vimrc
	./install vimrc
	
    #if you need new vim or some deps, see ./install
    ./install
