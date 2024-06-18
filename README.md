## 适用于 NUC11BTMi7, MacOS ventura


## 配置信息

- 计算卡：NUC11BTMI7 i7-11700B
- 有线网卡：i225-LM
- 无线网卡：BCM94360NG
- 声卡：机箱前面板USB声卡
- 显卡：惠普 6600 XT
- 内存：海盗船 DDR4 16G 3200MHz*2
- 硬盘：惠普 EX950 2T

### BIOS 设置

- Advanced
  - Advanced > `PCIE Resizable BAR Support: Disabled`
  - Advanced > Video > `Primary Display: PEG Slot`
- Security
  - Security Features > `Intel VT for Directed I/O(VT-d)：Disabled`
- Boot
  - Secure Boot > `Secure Boot: Disabled`
  - boot Priority > `Fast Boot: Unchecked`

## 硬件驱动情况
- [x] CPU正常睿频
- [ ] 11代CPU核心显卡无法驱动
- [x] 独立显卡HP 6600xt
- [x] USB接口已经定制，所有USB接口均可正常使用
- [x] 声卡驱动正常
- [x] 睡眠/唤醒正常
- [x] 免驱无线网卡WIFI、蓝牙正常
- [x] 有线网卡驱动正常
- [ ] 读卡器无SD卡测试，但读卡器走的USB3.2hub，理论上可以使用
- [ ] 无雷电硬件测试

参考EFI链接：https://github.com/xiao-chenxi/NUC11BTMi9-hackintosh  感谢 xiao-chenxi，EFI已经很完美了，在此基础上重新定制了USB、升级OpenCore，做了部分适配性的修改。


