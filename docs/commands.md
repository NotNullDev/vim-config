# navigation

`ctrl + o` - go back to previous line (jumplist)
`ctrl + t` - open in new tab
`f + <character` -  next occurance of the coooharatter

if (a == 5) {
	print("hello world!");
}

`ctrl {` jump by paragraph
ctrl + u / ctrl + d ( jump for half of the page ) # most usefull for navigation

`] + m` - jump to the next braket ({)

`%` - jump between brackets	

`shift + v` - enter visual mode and hilight whole line

`shift + d` - delete till the end of the line

f + <any> - next occurence
F + <any> - previous occurence

`d + i + }` # i - inside ( `d + i + }` - delete all inside {} )
`<any> + i + }` - select all inside curly brackets
> replace i with a to remove brackets as well

visual + selected: press o to jump between selections


diw - delete inside of the word ( not matter where you are in it )
yiw - copy inside of the word ( not matter where you are in it )

viw

viW - hilgiht everything between words
example:
std::vector<int> a = {2,3,4,5};

hahah hahh huhu hehe
hah
hahh
hahaha

# Search and replace

:s/haha/hehe

:%s/bbba/hehe - global replace

you can select fragment of code, then :s/<search term>/<replace term> will replace all occurences in the selection


you can replace all occurences in quickfixes using grep
