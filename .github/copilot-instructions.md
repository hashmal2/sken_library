# sken_library
STM32f4RE446対応のライブラリ．

System Workbench を使用する．

使用言語はC++．

## プログラムに使用する関数，モジュール
includeする関数は
- #include "stm32f4xx.h"
- #include "stm32f4xx_nucleo.h"
- #include "sken_library/include.h"<br>

の3種類である．

CANモジュールは
stm32f4xx.h\stm32f4xx_hal.h\stm32f4xx_hal_conf.h内にある
- #define HAL_CAN_LEGACY_MODULE_ENABLED

を使用する．

## 注意事項
- コメントは詳しく書く！書くとわかりやすくなる．ただし，プログラムを変えたときにコメントも同時に変えやすいように書くこと．
- 
