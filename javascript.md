JavaScript
==========

JavaScript = ECMAScript + DOM + BOM

Script无需指定type="text/javascript"，浏览器默认值即是这个值。

在script标签内部，不能出现</script>，不然浏览器认为是结束标签。需要通
过转义解决这个问题

defer 延迟脚本执行， IE4, Firefox 3.5, Safari 5, Chrome

async 异步，不能保证脚本执行顺序 Firefox 3.5, Safari 5, Chrome

noscript

