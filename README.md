# learnRegExp

## example

https://huzhengen.github.io/learnRegExp/example.html

## copy

`< img data-v-7d470f9e="" alt="" width="100%" height="100%" src="img/test02.c6b87be6.jpg">`.replace(/(?<=(width|height)\=)\"(.*?)\"/g, `"200%"`)

`< img data-v-7d470f9e="" alt="" width='100%' HEIGHT="100%" src="img/test02.c6b87be6.jpg">`.replace(/(?<=(width|height|WIDTH|HEIGHT)\=)("|')(.*?)\2/g, `"200%"`)

## website

https://juejin.im/post/5b5db5b8e51d4519155720d2

https://github.com/ziishaned/learn-regex/blob/master/translations/README-cn.md

https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test

https://regex101.com/