# HƯỚNG DẪN THÊM THIẾT BỊ ESPHOME VÀO HOME ASSISTANT

## I. ESPHome là gì

* ESPHome là hệ thống điều khiển ESP8266 / ESP32, ESPHome nó sẽ giúp chúng ta đơn giản hơn trong việc cấu hình và thêm thiết bị, để có sở hữu thiết bị thông minh trong chính ngôi nhà của mình thì ta chỉ cần cấu hình các thông tin cần thiết vào API ESPHome cung cấp, hệ thống ESPHome sẽ tự động nạp code vào chip giúp chúng ta, như vậy thì chúng ta đã có thể sở hữu một thiết bị thông minh trong chính ngôi nhà của mình.

## II. Một số thiết bị trong ESPHome

* Sensor Components

![esphomedevice](../_static/images/esphome1.png)

![esphomedevice1](../_static/images/esphome2.png)

* Binary Sensor Components

![esphomedevice2](../_static/images/esphome3.png)

* Output Components

![esphomedevice3](../_static/images/esphome4.png)

* Light Components

![esphomedevice4](../_static/images/esphome5.png)

* Switch Components

![esphomedevice5](../_static/images/esphome6.png)

* Fan Components

![esphomedevice6](../_static/images/esphome7.png)

* Display Components

![esphomedevice7](../_static/images/esphome8.png)

* Misc Components

![esphomedevice8](../_static/images/esphome9.png)

* Cookbook

![esphomedevice9](../_static/images/esphome10.png)

Xem chi tiết thông tin thiết bị: https://esphome.io/#

## III. Hướng dẫn thêm thiết bị ESPHome vào Home Assistant

### 1. Cài đặt ESPHome

Cài đặt Python và cài đặt tập lệnh bảng điều khiển thông qua pip3.

```python
pip3 install esphome
```
### 2. Khởi tạo project 

#### Bước 1 : Tạo file chứa project

![esphometutorial1](../_static/images/esphometutorial1.png)

#### Bước 2 : Điền thông tin dòng vi điều khiển đang sử dụng 

![esphometutorial2](../_static/images/esphometutorial2.png)

#### Bước 3 : Chọn dòng board ( đọc ở trên mặt chip và tìm kiếm ở google )

![esphometutorial3](../_static/images/esphometutorial3.png)

#### Bước 4 : Thiết lập Wifi

![esphometutorial4](../_static/images/esphometutorial4.png)

#### Bước 5 : Thiết lập password để nạp code bằng OTA 

![esphometutorial5](../_static/images/esphometutorial5.png)

### 3. Khởi động và chạy project 

#### Bước 1 : Config project và chạy project 

![runesphome1](../_static/images/runesphome1.png)

#### Bước 2 : Chọn phương thức code xuống board ( chọn 1 )

![runesphome2](../_static/images/runesphome2.png)

#### Bước 3 : Copy địa chỉ IP, dùng để config với HASS

![runesphome3](../_static/images/runesphome3.png)

### 4. Thêm thiết bị vào Home Assitant

#### Bước 1 : Chọn configuration

![hassesphome1](../_static/images/hassesphome1.png)

#### Bước 2 : Ấn vào dấu cộng phía tay phải bên dưới màn hình

![hassesphome2](../_static/images/hassesphome2.png)

#### Bước 3 : Nhập địa chỉ IP đã copy ở phần 3 bước 3

![hassesphome3](../_static/images/hassesphome3.png)

#### Bước 4 : Submit yêu cầu ở bước 3, chúng ta sẽ có được ESPHome như trong hình

![hassesphome7](../_static/images/hassesphome4.png)

#### Bước 5 : Thêm thiết bị vào phòng 

![hassesphome4](../_static/images/hassesphome5.png)

![hassesphome5](../_static/images/hassesphome6.png)

![hassesphome6](../_static/images/hassesphome7.png)








