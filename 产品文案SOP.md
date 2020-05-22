## 文案创建
1. #### 客户端/后端文案以Google Spreadsheet不同Tab的形式单独管理。
2. #### 不再使用的key及时移除到Archive Tab。
3. #### 添加新key时先全局搜索有无相同文案，如果有则复用。
4. #### 英文文案确认完毕第一时间同步到Spreadsheet上。
## 文案修改
1. #### 控制Google Spreadsheet权限，让尽可能少的人拥有修改权限。
2. #### 任何人修改完文案请查看修改记录，防止误操作。
3. #### 任何人对文案进行任何改动，请在群里@相应的人员（开发/产品/UI）。
4. #### 产品在PRD里同步文案改动，UI在Zeplin上同步文案改动。
## 命名规范
1. #### 言简意赅，一目了然，使用 **模块_功能_描述** 的结构
    >chat_header_title **✓**
    
    >chat_header_des **✓**
2. #### key中不能出现大写
    >string_Campro **✗**
    
    >string_campro **✓**
3. #### key不宜过长
    >login_sent_code_invalid_number **✗**
    
    >login_invalid_number **✓**
4. #### 通用文案使用通用key
    >notification_entrance_title = Notification **✗**
    
    >string_notification = Notification **✓**
5. #### 区分中文标点和英文标点
    >modalités d’utilisation **✗**
    
    >modalités d'utilisation **✓** 
