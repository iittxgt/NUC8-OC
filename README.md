# NUC8-OC

* NUC8i5BEH/NUC8i7BEH 最新完美OC EFI，补丁、驱动都已更新到最新：

* intel wifi、Bluetooth、雷电3、读卡器均已驱动。

* OC1.0.0-EFI-NUC8-intel-wifi-BT-CardReader-Sonoma：包含自带读卡器、intel wifi和蓝牙驱动，适用于未做任何改动，使用自带读卡器、wifi和蓝牙的机型。

* 默认config.plist 适配4k显示器，OC分辨率配置修改已经变更到UEFI-->Output-->UIScale, 默认该值为0，如果OC分辨率显示不正常可以根据情况，修改为1 或2 尝试，每次修改完最好重置nvram。

* 三码已清，自行更换三码。

* --240514:  无痛升级14.5。
* --240510:  OC更新到1.0.0。
* --240426:  修复了一个因读卡器超时导致重启或者睡眠后系统崩溃的问题[#9](https://github.com/lxopencv/NUC8-OC/issues/9#issue-2263096100)。
* --240326:  无痛升级14.4.1，支持Mac单向隔空投送。
* --240312:  OC更新到0.9.9，支持14.4。
* --240206:  OC更新到0.9.8。
* --231220:  更新IntelBluetoothFirmware等至2.4.0；更新AirportBrcmFixup至2.1.9，支持更新到14.2.1。
* --231213:  OC更新到0.9.7，支持更新到14.2。
* --231201: 修复3.5mm音频声音不正常问题，支持更新到14.1.2。
* --231109: 更新NUC8（Macmini8,1）引导以支持系统增量更新。
* --231108: OC更新到0.9.6，支持更新到14.1.1。
