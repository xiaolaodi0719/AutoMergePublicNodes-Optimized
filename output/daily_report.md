# AutoNodes 每日报告

生成时间：2026-09-08 16:35:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90488 |
| 去重后节点数 | 25026 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25026 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 93.1 |
| geo | 1.4 |
| probe | 283.5 |
| real_test | 329.2 |
| tcp | 42.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 38 | 21 | 17 | 55.3% |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 149 | 135 | 14 | 90.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 18 | 14 | 4 | 77.8% |
| vless | 368 | 242 | 126 | 65.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 41 |
| cn-block:ClientOSError | 32 |
| 204:TimeoutError | 31 |
| 204:ProxyError | 21 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| speed:TimeoutError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5788 |
| ConnectionRefusedError | 968 |
| gaierror | 373 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | prefer | 289 | 0.92 | 1658 |
| Surfboard-tg-mixed | 0.759 | prefer | 135 | 0.681 | 7484 |
| ermaozi | 0.611 | observe | 35 | 0.6 | 409 |
| mheidari-all | 0.48 | observe | 133 | 0.398 | 21582 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 212 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6097 |
| Epodonios-all | 0.255 | observe | 0 | None | 7932 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8703 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.398 | 53 | 80 | 133 |
| ermaozi | 0.6 | 21 | 14 | 35 |
| Surfboard-tg-mixed | 0.681 | 92 | 43 | 135 |
| Au1rxx-base64 | 0.92 | 266 | 23 | 289 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21582 | yes | 5.02 | 0 |
| SoliSpirit-all | 8703 | yes | 3.7 | 0 |
| Epodonios-all | 7932 | yes | 3.13 | 0 |
| Surfboard-tg-mixed | 7484 | yes | 3.42 | 0 |
| barry-far-vless | 6501 | yes | 2.92 | 0 |
| Surfboard-tg-vless | 6283 | yes | 4.08 | 0 |
| DeltaKronecker-all | 6097 | yes | 4.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 3.09 | 0 |
| mahdibland-V2RayAggregator | 4209 | yes | 1.77 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 58 |
| cn-block | 51 |
| geo | 47 |
| speed | 9 |
