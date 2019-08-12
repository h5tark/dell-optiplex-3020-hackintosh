Hôm bữa có nghịch thử con Dell Optiplex 3020 (i5 4570 + RAM 2x8GB DDR3 bus 1600 + SSD Samsung EVO 256GB) ngon lành cành đào, nay share cho các bạn bộ EFI với Clover v2.5k r5037. Mọi thứ hoạt động tốt với Mojave 10.14.6.

Working:
- iGPU HD4600 
- Sleep/Wake
- NVRAM
- USB 2.0 + 3.0
- AppleHDA + Audio port trước + sau
- Gigabit Ethernet

Lưu ý các bạn nhớ mở config.plist và thay RtVariables và SMBIOS thành của bạn (dễ nhất là mở bằng Clover Configurator để generate, dùng SMBIOS của iMac 14,1 nhé). 

Ngoài ra để kích hoạt NVRAM, cần tải clover https://github.com/Dids/clover-builder/releases, lúc cài ấn tuỳ chọn **Install RC scripts on target volume** để kích hoạt NVRAM, sau đó ghi chép đè bộ EFI của mình là ok (với những bạn chưa biết gì, còn các bạn cao thủ thì biết chỉ dùng cái nào rồi nhé).  

Chạy ngon lành, đang kéo màn 2K, nên quyết định xoá macOS trên con i5 8400 để chuyển qua NVIDIA chơi game cho sướng do nhu cầu máy Hackintosh chỉ dùng để code và làm việc.