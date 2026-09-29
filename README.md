# 平衡车 BLE 遥控网页

用 Web Bluetooth 连接 ECB02 透传模块（服务 FFF0，写 FFF2），每 50 ms 发送 `move <转向> <速度>
`。

- iPhone：用 Bluefy 浏览器打开 https://tthc8t6.github.io/blance_car_rc/
- 电脑：Chrome / Edge 打开，支持 WASD / 方向键，空格停止
