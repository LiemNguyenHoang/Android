# Android
# Chạy máy thật qua Wifi
  - Lấy link SDK trong Android Studio: Tools/SDK Manager
  - Trong cmd: 
     cd link_sdk\platform-tools;
     Kết nối smart phone với laptop qua USB port;
     adb tcpip 5555;
     Ngắt caple;
     adb connect ip_smart_phone:5555;
