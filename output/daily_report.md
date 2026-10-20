# AutoNodes 每日报告

生成时间：2026-10-20 11:22:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94099 |
| 去重后节点数 | 26435 |
| TCP 可达数 | 3000 |
| 真测通过数 | 399 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26435 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 86.5 |
| geo | 1.6 |
| probe | 222.5 |
| real_test | 219.8 |
| tcp | 45.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 46 | 32 | 14 | 69.6% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 147 | 135 | 12 | 91.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 36 | 27 | 9 | 75.0% |
| vless | 257 | 193 | 64 | 75.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 21 |
| 204:TimeoutError | 16 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 13 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6637 |
| ConnectionRefusedError | 1034 |
| OSError | 235 |
| gaierror | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.957 | prefer | 55 | 0.891 | 23400 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 27 |
| Au1rxx-base64 | 0.901 | prefer | 304 | 0.855 | 1192 |
| Surfboard-tg-mixed | 0.72 | prefer | 87 | 0.644 | 6911 |
| ermaozi-get_subscribe | 0.469 | observe | 27 | 0.444 | 510 |
| DeltaKronecker-all | 0.272 | observe | 7 | 0.286 | 3519 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7377 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9884 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.286 | 2 | 5 | 7 |
| ermaozi-get_subscribe | 0.444 | 12 | 15 | 27 |
| Surfboard-tg-mixed | 0.644 | 56 | 31 | 87 |
| Au1rxx-base64 | 0.855 | 260 | 44 | 304 |
| mheidari-all | 0.891 | 49 | 6 | 55 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23400 | yes | 6.56 | 0 |
| SoliSpirit-all | 9884 | yes | 4.75 | 0 |
| Epodonios-all | 7377 | yes | 5.98 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 3.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.42 | 0 |
| barry-far-vless | 5733 | yes | 1.71 | 0 |
| Surfboard-tg-vless | 5515 | yes | 4.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 2.87 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 2.67 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 40 |
| speed | 24 |
| geo | 19 |
| cn-block | 18 |
