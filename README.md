# esp32s3-sample

[![License](https://img.shields.io/badge/License-MIT-important.svg?style=flat&logo=github)](https://www.mit-license.org)
[![C++](https://img.shields.io/badge/C++-11-success.svg?style=flat&logo=cplusplus)](https://isocpp.org)
[![CMake](https://img.shields.io/badge/CMake-3.5-success.svg?style=flat&logo=cmake)](https://cmake.org/cmake/help/v3.5)
[![ESP-IDF](https://img.shields.io/badge/ESP_IDF-4.4-success.svg?style=flat&logo=espressif)](https://dl.espressif.com/dl/esp-idf/?idf=4.4)
[![ESP32](https://img.shields.io/badge/ESP32-S3-success.svg?style=flat&logo=espHome)](https://docs.espressif.com/projects/esp-idf/zh_CN/v4.4/esp32s3/get-started/index.html)
[![Release](https://img.shields.io/badge/Release-0.4.0-informational.svg)](https://github.com/aaric/esp32s3-sample/releases)

> [ESP32-S3-DevKitC-1](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32s3/hw-reference/esp32s3/user-guide-devkitc-1.html)

## 1 Command

```powershell
# Set target
idf.py set-target esp32s3

# Build project
idf.py build

# Flash device
idf.py -p (PORT) flash

# Monitor device
idf.py -p (PORT) monitor
```

## 2 Log

> *[SDKCONFIG - Log Level](https://docs.espressif.com/projects/esp-idf/zh_CN/v4.4/esp32s3/api-reference/system/log.html)*  
> *- INFO  -> `CONFIG_LOG_DEFAULT_LEVEL_INFO=y` Default*  
> *- DEBUG -> `CONFIG_LOG_DEFAULT_LEVEL_DEBUG=y` Now*

|No.|Name|Remark|
|:---:|:---:|-----|
|1|`ESP_LOGE`|*error (lowest)*|
|2|`ESP_LOGW`|*warn*|
|3|`ESP_LOGI`|*info*|
|4|`ESP_LOGD`|*debug*|
|5|`ESP_LOGV`|*verbose (highest)*|

## 3 GPIO

> *[GPIO & RTC GPIO](https://docs.espressif.com/projects/esp-idf/zh_CN/v4.4/esp32s3/api-reference/peripherals/gpio.html)*  
> *[Remote Control (RMT)](https://docs.espressif.com/projects/esp-idf/zh_CN/v4.4/esp32s3/api-reference/peripherals/rmt.html)*

## 4 Timer

> *[High Resolution Timer](https://docs.espressif.com/projects/esp-idf/zh_CN/v4.4/esp32s3/api-reference/system/esp_timer.html)*
