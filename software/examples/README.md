# Examples for CH32V203G6

These examples are tested for FlappyBoard, and shall work for other CH32V203G6 boards.

> Note: WCHISPTool requires hex file to use CRLF as EOL.

*EVT* refers to [CH32V20xEVT.zip](https://www.wch.cn/downloads/CH32V20xEVT_ZIP.html), which contains source code of the most examples. [MounRiver Studio](http://www.mounriver.com/) or its toolchains can be used to compile source code.

> Note: These examples use *USART1* (*PA9*) as debug port with 115200n8 by default.

## CH372Device_D_FS

Compiled directly from `EVT/EXAM/USB/USBD/CH372Device`.

## CompositeKM

Modified from `EVT/EXAM/USB/USBD/CompositeKM`, use *PA2/PA3* as USART2 TX/RX.

## LED_Toggle

Modified from `EVT/EXAM/GPIO/GPIO_Toggle`, use PB8 LED and blink per 1 second.

## TinyMaix

TinyMaix demo for CH32V203G6. Please refer [CH32V203-TinyMaix](https://github.com/metro94/CH32V203-TinyMaix) or [TinyMaix](https://github.com/sipeed/TinyMaix) to get more information.
