<!--
 * @Author: xiaolong.qiu
 * @Date: 2020-05-14 18:01:33
 -->
Usage: 
    1. yarn add cover-phone-num

    2. const coverPhone = require("cover-phone-num");

    3. coverPhone("151xxxxxxxx", [start], [length], [symbol], [rule])
    
    4. Default values:
        start: 3
        length: 4
        symbol: *
        rule: /^1([38][0-9]|4[579]|5[0-3,5-9]|6[6]|7[0135678]|9[89])\d{8}$/
        
    5. 除了第一个参数，后面的参数都是可选