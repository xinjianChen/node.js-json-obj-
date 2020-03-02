# node.js-json-obj-
# node.js在json/obj中获取属性，除了用点，其实用["pro"]的方法更稳
* 今天在华为返回的https报文头部中获得token时，发现token的key值为X-subject-token时通过headers.X-subject-token获取不到，在-处会发生截断
* 本来想要改为更麻烦的方法，后来突然想起js中内部真正获得属性的方法是obj["key"]的方式，点方法也会内部转化成改形式，于是更改之后发现很好用
