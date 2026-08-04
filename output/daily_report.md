# AutoNodes 每日报告

生成时间：2026-08-04 19:47:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86001 |
| 去重后节点数 | 24515 |
| TCP 可达数 | 3000 |
| 真测通过数 | 490 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24515 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 28.6 |
| geo | 1.1 |
| probe | 54.3 |
| real_test | 110.6 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 51 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 115 | 98 | 17 | 85.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 163 | 154 | 9 | 94.5% |
| vless | 240 | 165 | 75 | 68.8% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 34 |
| geo:ClientOSError | 19 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 11 |
| speed:TimeoutError | 11 |
| 204:ProxyError | 7 |
| speed:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4999 |
| ConnectionRefusedError | 835 |
| gaierror | 288 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.984 | prefer | 51 | 1.0 | 72 |
| Au1rxx-base64 | 0.949 | prefer | 423 | 0.889 | 1560 |
| Surfboard-tg-mixed | 0.573 | observe | 15 | 0.6 | 5570 |
| mheidari-all | 0.57 | observe | 98 | 0.49 | 19967 |
| DeltaKronecker-all | 0.446 | observe | 5 | 0.8 | 5788 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 58 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 6154 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 177 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.49 | 48 | 50 | 98 |
| Surfboard-tg-mixed | 0.6 | 9 | 6 | 15 |
| DeltaKronecker-all | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.889 | 376 | 47 | 423 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 51 | 0 | 51 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19967 | yes | 4.5 | 0 |
| SoliSpirit-all | 6965 | yes | 4.84 | 0 |
| Epodonios-all | 6154 | yes | 3.28 | 0 |
| DeltaKronecker-all | 5788 | yes | 4.86 | 0 |
| Surfboard-tg-mixed | 5570 | yes | 3.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 1.65 | 0 |
| mahdibland-V2RayAggregator | 5141 | yes | 2.37 | 0 |
| barry-far-vless | 4787 | yes | 1.43 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 2.78 | 0 |
| Surfboard-tg-vless | 4451 | yes | 3.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 53 |
| 204 | 23 |
| speed | 16 |
| cn-block | 14 |
