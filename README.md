# DTTOOL INFO

Danh mục mã SoC điện thoại và tên thương mại cho DT TOOL.

- `Chips/<hãng>/<mã>.txt` chứa một dòng tên thương mại, UTF-8. Ví dụ `Chips/qualcomm/SM8750.txt` chứa `Snapdragon 8 Elite`.
- Tên mã viết hoa, bỏ khoảng trắng và đổi dấu `/` trong mã biến thể thành `~`. Ví dụ `MT6993W/CZA` nằm trong `Chips/mediatek/MT6993W~CZA.txt`.
- Một mã có thể dùng cho nhiều tên thương mại. Các file mã gốc giữ các tên cùng dòng khi chưa thể xác định biến thể. Dùng mã đầy đủ để tra biến thể khi có.
- Danh mục gồm các dòng Qualcomm Snapdragon, MediaTek Dimensity/Helio, Samsung Exynos, Google Tensor, Apple A-series, HiSilicon Kirin, UNISOC và Xiaomi XRING. Không phải mọi mã nội bộ của các hãng đều được công bố.

## Nguồn đối chiếu

- [Qualcomm Snapdragon](https://www.qualcomm.com/smartphones/products/8-series) và [bảng mã SoC Qualcomm](https://docs.qualcomm.com/nav/home/QNN_general_overview.html?product=924033590759186372)
- [MediaTek Dimensity](https://www.mediatek.com/products/smartphones/dimensity-5g)
- [Samsung Exynos](https://semiconductor.samsung.com/processor/mobile-processor/)
- [Google Tensor](https://blog.google/products-and-platforms/devices/pixel/tensor-g5-pixel-10/) và [mã nền tảng trong AOSP](https://android.googlesource.com/device/)
- [Apple A-series](https://www.apple.com/iphone/compare/)
- [HiSilicon Kirin](https://www.hisilicon.com/cn/products/Kirin/Kirin-flagship-chips/Kirin-9000)
- [UNISOC](https://www.unisoc.com/en/product/SmartPhone)
- [Xiaomi XRING](https://www.mi.com/global/about/)

Các mã Qualcomm và MediaTek có sẵn trong bảng tương thích của DT TOOL được giữ để tra cứu các ROM cũ.
