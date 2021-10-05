# stm32f405_lvgl_example
针对STM32F405RG的LVGL移植例程


引脚资源请自行配置，打开st7735.h文件，自行更改，默认使用资源如下  
![](https://github.com/Hotakus/stm32f405_lvgl_example/blob/master/Assets/LVGLV8/Snipaste_2021-10-06_04-45-20.png)

### 注意！请勿用STM32CubeMX直接配置，因为会导致我的某些针对FreeRTOCS的更改发送改变，会导致项目编译错误，推荐方法是：备份\Middlewares\Third_Party\FreeRTOS文件夹，进行配置后再还原。
