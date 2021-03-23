### CMakeLists文件是十分重要的配置文件
* 及时修改，及时更新 Reload

### 学习如何调试程序
* 打开调试面板（小虫子）使用clion自带的evaluate expression功能，可以进行复杂的自定义调试。
  比如&main之类的。
  
* 点击GDB（linux）输入disassemble 即可查看汇编。
  *  可以设置汇编指令集
    set target.x86-disassembly-flavor intel
     
### C语言代码风格
* 变量命名清晰明了
* 注释可以有固定的语法格式
  /**
  * xxxxxx
  * xxxxxx
  * /
  
* 选择自己喜欢的命名风格
  settings --> Code Style --> C/C++ set from  --> naming convention