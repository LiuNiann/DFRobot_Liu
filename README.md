# DFRobot_LiuNian

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

#include <DFRobot_liunian.h>
DFRobot_liunian sut1;
void setup(){
  Serial.begin(9600);
  sut1.WriteName("二牛");
  sut1.WriteAge(23);
  sut1.WriteScore(81);
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

- Data 2020-7-8
- Version V0.1


## Credits

Written by(Nian.Liu@dfrobot.com), 2020. (Welcome to our [website](https://www.dfrobot.com/))





# DFRobot_LiuNian

