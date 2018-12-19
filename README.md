# Matlab-origin-talker

原作者没有写README.md,但是有详细的测试文件，我在学习过程中添加了中文版文档。

## Tips

1. 在运行TempProjectTest.m时运行到16行会报错：""。解决方法是将根目录下‘'.\Enumerations\'加入matlab的搜索目录即可。
2. 运行至23行 g1 = graph1.graphLayers(1);会返回错误信息："结构体内容引用自非结构体数组对象。
出错 TempProjectTest (line 23)
gl = graph1.graphLayers(1);"。分析结果是没有活动的页面，需要先创建图片。test past.
