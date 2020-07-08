# DFRobot_huyujie

................
   
## Table of Contents
* [URL](#url)
* [Summary](#summary)
* [Installation](#installation)
* [Methods](#methods)
* [Compatibility](#compatibility)
* [History](#history)
* [Credits](#credits)

## URL
* ……………………………………

* ……………………………………

* ……………………………………

## Summary

1. …………………………………… <br>
2. …………………………………… <br>
3. …………………………………… <br>
4. …………………………………… <br>
5. …………………………………… <br>

## Installation

……………………………………………………………………………………………………………………………………………………

## Methods

```C++

  #include <DFRobot_huyujie.h>
DFRobot_huyujie sut1;
void setup(){
  Serial.begin(9600);
  sut1.WriteName(-123);
  sut1.WriteAge(10);
  sut1.WriteScore(1.23);
  Serial.print("name= ");Serial.println(sut1.getName());
  Serial.print("age= ");Serial.println(sut1.getAge());
  Serial.print("score= ");Serial.println(sut1.getScore());
}

void loop(){
  
}
```

## Compatibility

MCU                | Work Well    | Work Wrong   | Untested    | Remarks
------------------ | :----------: | :----------: | :---------: | -----
Arduino uno        |      √       |              |             | 
Mega2560        |             |              |             | 
Leonardo        |             |              |             | 
ESP32        |             |              |             | 
micro:bit        |             |              |             | 


## History

- Data 2019-7-19
- Version V0.1


## Credits

Written by(yujie.hu@dfrobot.com), 2019. (Welcome to our [website](https://www.dfrobot.com/))





# DFRobot_huyujie

