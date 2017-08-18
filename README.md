
### 目的

使用jasmine测试订阅器脚本（js/app.js）是否正常使用。
包括：
- 订阅器的来源是否有效
- 顶部菜单是否能够正常使用（默认隐藏，点击切换状态）
- ajax的调用是否有效
- 内容切换是否有效

### 如何使用
- 下载jasmine
- 在html中引用

    ```
      <script src="lib/jasmine-2.2.0/jasmine.js"></script>
      <script src="lib/jasmine-2.2.0/jasmine-html.js"></script>
      <script src="lib/jasmine-2.2.0/boot.js"></script>
    ```

- 导入检测文件`<script src="jasmine/spec/feedreader.js"></script>`
- 保存，在本地浏览器打开
- 测试开始 Good Luck!

成功通过啦！
![成功样式][1]


  [1]: sample.png

