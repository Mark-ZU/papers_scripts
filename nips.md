https://papers.nips.cc/
```
var str = ""
$("ul").children().children().not(".author").each(function(index){
	if(index == 0) return;
	str += ("https://papers.nips.cc" + $(this).attr("href") + ".pdf\n")
})
console.log(str)
```
