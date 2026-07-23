# AutoNodes 每日报告

生成时间：2026-07-23 08:44:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83067 |
| 去重后节点数 | 22726 |
| TCP 可达数 | 3000 |
| 真测通过数 | 861 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22726 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 42.3 |
| geo | 1.5 |
| probe | 75.6 |
| real_test | 227.9 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 134 | 107 | 27 | 79.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 675 | 578 | 97 | 85.6% |
| vless | 574 | 133 | 441 | 23.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 215 |
| speed:ClientOSError | 124 |
| cn-block:TimeoutError | 85 |
| geo:ClientOSError | 50 |
| 204:ProxyError | 24 |
| 204:TimeoutError | 23 |
| speed:TimeoutError | 22 |
| cn-block:ClientOSError | 6 |
| speed:ProxyError | 6 |
| geo:ProxyError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4174 |
| ConnectionRefusedError | 687 |
| gaierror | 359 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.917 | prefer | 84 | 0.845 | 5330 |
| mheidari-all | 0.877 | prefer | 398 | 0.799 | 19639 |
| Au1rxx-base64 | 0.654 | observe | 188 | 0.638 | 432 |
| DeltaKronecker-all | 0.515 | observe | 717 | 0.435 | 5572 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4399 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4757 |
| Epodonios-all | 0.255 | observe | 0 | None | 6489 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.435 | 312 | 405 | 717 |
| Au1rxx-base64 | 0.638 | 120 | 68 | 188 |
| mheidari-all | 0.799 | 318 | 80 | 398 |
| Surfboard-tg-mixed | 0.845 | 71 | 13 | 84 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19639 | yes | 4.07 | 0 |
| SoliSpirit-all | 6912 | yes | 2.42 | 0 |
| Epodonios-all | 6489 | yes | 1.93 | 0 |
| DeltaKronecker-all | 5572 | yes | 3.99 | 0 |
| Surfboard-tg-mixed | 5330 | yes | 2.61 | 0 |
| mahdibland-V2RayAggregator | 4954 | yes | 2.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4757 | yes | 1.99 | 0 |
| barry-far-vless | 4690 | yes | 1.17 | 0 |
| xiaoji235-airport-v2ray-all | 4399 | yes | 1.37 | 0 |
| Surfboard-tg-vless | 4154 | yes | 2.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 270 |
| speed | 152 |
| cn-block | 94 |
| 204 | 51 |
