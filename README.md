## 适用于 NUC11BTMi7, MacOS ventura


## 配置信息

- 计算卡：NUC11BTMI7 i7-11700B
- 有线网卡：i225-LM
- 无线网卡：AX210
- 声卡：计算卡前置面板USB声卡
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
- [x] 板载Intel无线网卡
- [x] 板载蓝牙正常
- [x] 有线网卡驱动正常
- [ ] 读卡器无SD卡测试，但读卡器走的USB3.2hub，理论上可以使用
- [ ] 但是无雷电硬件测试

参考EFI链接：https://github.com/xiao-chenxi/NUC11BTMi9-hackintosh，感谢 xiao-chenxi，EFI已经很完美了，在此基础上重新定制了USB，升级OpenCore，做了部分适配性的修改。



![61FADA55BAC270C04100F9FBEF7504C6](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/5fb87b03-180c-4282-9a94-9becb5e2d37b)

![B4CD1F2B3E4BFFF1240FF5109B366665](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/e54ca566-122b-400f-bf82-d69cd2ede8c6)

![697F2FC60C44D5846F2BFF4A4899F355](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/17566f32-6ef0-46df-aa46-cc69ab9e141c)

![C7B577EF0FF9EB0376FDB5B032252CC9](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/76eb1bfd-f41d-41ab-ad7d-246379f57b2a)

![9A7CB91E98497699A56F359EF6360F6B](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/ef93e0e8-4563-429f-ac7e-67735053fc40)
