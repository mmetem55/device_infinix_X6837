# Device tree for the Infinix HOT 40 Pro (X6837)

### Original Project: https://github.com/mt6789-transsion/device_infinix_X6837

İlk maddeyi **“compatibility was achieved”** anlamını verecek şekilde güncelledim:

### Changes Made

* Achieved **LineageOS 23.2 compatibility**.
* Fixed the **PN557 NFC vendor driver** issue.
* Fixed issues with **Wi-Fi Hotspot, USB Tethering, and Bluetooth Tethering**.
* Added the **stock Transsion Camera** application with unnecessary telemetry and data-collection features removed.
* Replaced the incorrect battery values displayed in the Android interface with the correct values from the **Transsion debug interface** using a custom kernel-level battery proxy driver.
* Added a new **Bypass Charging** option to the Battery section of the Android Settings app, with **kernel-level bypass charging support**.

Türkçesi:

### Yapılan Değişiklikler

* **LineageOS 23.2 uyumluluğu sağlandı.**
* **PN557 NFC vendor sürücüsü** sorunu düzeltildi.
* **Wi-Fi Hotspot, USB Tethering ve Bluetooth Tethering** sorunları düzeltildi.
* Gereksiz telemetri ve veri toplama özellikleri kaldırılmış **stok Transsion Camera** uygulaması eklendi.
* Android arayüzünde gösterilen hatalı pil değerleri, özel bir **kernel seviyesinde battery proxy sürücüsü** kullanılarak **Transsion debug arayüzündeki doğru değerlerle** değiştirildi.
* Android Ayarlar uygulamasının Pil bölümüne yeni bir **Bypass Charging** seçeneği eklendi ve **kernel seviyesinde bypass şarj desteği** sağlandı.



## Device specifications

| Basic                   | Spec                                                        |
| ----------------------- | :---------------------------------------------------------- |
| SoC                     | MediaTek Helio G99 (6nm)                                    |
| CPU                     | Octa-core (2x2.2 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)     |
| GPU                     | Mali-G57 MC2                                                |
| Memory                  | 8GB / 12GB                                                  |
| Shipped Android version | 13                                                          |
| Storage                 | 128GB / 256GB                                               |
| MicroSD                 | MicroSDXC                                                   |
| Battery                 | Non-removable Li-Po 5000 mAh                                |
| Dimensions              | 168.6 x 76.6 x 8.3 mm                                       |
| Display                 | 1080 x 2460 pixels, 6.78 inches                             |
| Rear Camera 1           | 108 MP, f/1.8, (wide), 0.64µm, AF                           |
| Rear Camera 2           | 2 MP, f/2.4, (macro)                                        |
| Rear Camera 3           | QVGA                                                        |
| Front Camera            | 32 MP, f/2.2, (wide)                                        |


## Device Picture

![Infinix HOT 40 Pro](https://fdn2.gsmarena.com/vv/pics/infinix/infinix-hot-40-pro-1.jpg)
