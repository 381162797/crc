## Describe  
It is a simple way used to generate or check the CRC16 of Modbus Protocol;  
****
## install  
npm i modbuscrc -S  
****
## Usage  
const CRC = require(modbuscrc);  
 //if the Modbus-Message is '010301010001d436',so the CRC16 is 'd436';  
 // i want to check or generate the message ,so:  
const mes = '010301010001';  
const crc16 = CRC(mes);  
console.log(crc16,typeof crc16);  
 //d436 String
****
