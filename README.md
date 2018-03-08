ESPRSSIF MIT License

Copyright © 2017 <ESPRESSIF SYSTEMS (SHANGHAI) PTE LTD>

Permission is hereby granted for use on ESPRESSIF SYSTEMS ESP8266/ESP32 only, in which case, it is free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

乐鑫 MIT 许可证

版权 © 2017 <乐鑫信息科技（上海）有限公司>

该许可证授权仅限于乐鑫信息科技 ESP8266/ESP32 产品的应用开发。在此情况下，该许可证免费授权任何获得该软件及其相关文档（统称为“软件”）的人无限制地经营该软件，包括无限制 的使用、复制、修改、合并、出版发行、散布、再授权、及贩售软件及软件副本的权利。被授权人在享受这些权利的同时，需服从下面的条件：

在软件和软件的所有副本中都必须包含以上的版权声明和授权声明。

该软件按本来的样子提供，没有任何明确或暗含的担保，包括但不仅限于关于试销性、适合某一特定用途和非侵权的保证。作者和版权持有人在任何情况下均不就由软件或软件使用引起的以合同形式、民事侵权或其它方式提出的任何索赔、损害或其它责任负责。

//**************** V1.0.3 ************************//

This APP is demo for Blufi demo of ESP-IDF

1. add get wifi list around ESP32 command;
2. add send error report to phone when blufi has error;
3. add send/receive custom data command, The command is for user echange user-defined data;

//**************** V1.0.2 ************************//

此版本为 ESP-IDF 中 blufi Demo 配合使用的APP.
// This APP is demo for Blufi demo of ESP-IDF
1.设备蓝牙名称必须为 BLUFI开头才能被搜索到;
// APP can only search for devices whose ADV name has a "BLUFI_" prefix
2.支持蓝牙的连接,断开自动重连;
// support ble reconnect
3.支持配置成 softAP ,STA 或者 softAP&STA 模式;
// support softasoftAPmode and  STA mode

//************************************************//
