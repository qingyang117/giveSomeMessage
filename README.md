# giveSomeMessage
浏览器中常用的一些消息提示
基于JQuery重新定义

/**confirm方法
 * @param arg1 {Object/String/Number} 可以为object，也可以为string/number,为string/number时title、ico为默认值，非必传参数
 * @param arg1.title {String} 提示框标题，可为空默认值为"系统提示"
 * @param arg1.mess {String/Number} 提示的信息，可为空默认值为"确定要执行操作吗？"
 * @param arg1.ico {String} 提示图标，warn：蓝色感叹号，ask：橙色问号，succeed，绿色对号，可为空默认值为ask
 * @param arg2 {Function}	确认回调函数，非必传参数
 * @param arg3 {Function}	取消回调函数，非必传参数
  */
  
  
  /**alert方法
 * @param arg1 {Object/String/Number} 可以为object，也可以为string/number,为string/number时title、ico为默认值，非必传参数
 * @param arg1.title {String} 提示框标题，可为空默认值为"系统提示"
 * @param arg1.mess {String/Number} 提示的信息，可为空默认值为"请确认您的操作！"
 * @param arg1.ico {String} 提示图标，warn：蓝色感叹号，ask：橙色问号，succeed，绿色对号，可为空默认值为warn
 * @param arg2 {Function}	确认回调函数，非必传参数
 */
 
 
 /**prompt方法
 * @param arg1 {Object/String/Number} 可以为object，也可以为string/number,为string/number时title、init为默认值，非必传参数
 * @param arg1.title {String} 提示框标题，可为空默认值为"系统提示"
 * @param arg1.mess {String/Number} 提示的信息，可为空默认值为"请输入信息！"
 * @param arg1.init {String} 输入框初始值，默认为空，若有值时为选中状态
 * @param arg2(txt){} {Function}	确认回调函数，非必传参数
 * @param txt {String} 确认时回调函数传回的输入值
 */
 
 
 /**cue方法,用于某些操作成功后给予用户提示，一秒后渐隐并在DOM中移除
 * @param mess {String/Number} 提示信息，可为空默认值为"操作成功"
 * @param ico {String} 提示图标，warn：蓝色感叹号，ask：橙色问号，succeed:绿色对号，可为空默认值为succed
 */
 
