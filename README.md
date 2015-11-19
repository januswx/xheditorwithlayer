# using xheditor with layer

```javascript
layer.open({
	type: 1,
	title:"add some text",
	area: ['801px', '405px'], //宽高
	content: $('#xh'),
	end: function(){
		$('#content').xheditor(false);
	}
});
$('#content').xheditor({tools:'Pastetext,FontSize,FontColor,BackColor,|,Bold,Italic,Align,List,Outdent,Indent,Hr,Table,Source',skin:'nostyle'});
```