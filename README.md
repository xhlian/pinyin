pinyin
======

汉字转拼音Javascript工具类

 usecase: 
 	全拼：Pronunciation.getFullChars("拼音") or Pinyin.getFullChars("拼音");
 	首字母：Pronunciation.getCamelChars("拼音") or Pinyin.getCamelChars("拼音");
 
 description:
	   在原代码上做了以下修改：
	 1. 去掉对Mooltools的依赖;
	 2. 存在AMD加载器时，自动注册为符合AMD规范的模块;
	 3. Pronunciation(Pinyin)从函数改为对象, 可直接调用;
	 4. getFullChars(), getCamelChars()添加第二个参数checkPolyphone，检查是否多音字;

 date: 2014/8/3 15:02
