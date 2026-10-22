# AutoNodes 每日报告

生成时间：2026-10-22 17:03:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96380 |
| 去重后节点数 | 26691 |
| TCP 可达数 | 3000 |
| 真测通过数 | 193 |
| verified 输出数 | 193 |
| global 输出数 | 207 |
| all 输出数 | 26691 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 94.4 |
| geo | 1.5 |
| probe | 178.9 |
| real_test | 118.8 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 40 | 17 | 23 | 42.5% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 66 | 60 | 6 | 90.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 36 | 30 | 6 | 83.3% |
| vless | 111 | 72 | 39 | 64.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 26 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| geo:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6294 |
| ConnectionRefusedError | 1060 |
| gaierror | 375 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.898 | prefer | 53 | 0.83 | 7066 |
| mheidari-all | 0.895 | prefer | 52 | 0.827 | 24062 |
| Au1rxx-base64 | 0.803 | prefer | 114 | 0.746 | 1529 |
| ermaozi | 0.451 | observe | 40 | 0.425 | 573 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 3641 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7538 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10202 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.425 | 17 | 23 | 40 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| Au1rxx-base64 | 0.746 | 85 | 29 | 114 |
| mheidari-all | 0.827 | 43 | 9 | 52 |
| Surfboard-tg-mixed | 0.83 | 44 | 9 | 53 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24062 | yes | 6.18 | 0 |
| SoliSpirit-all | 10202 | yes | 4.4 | 0 |
| Epodonios-all | 7538 | yes | 5.46 | 0 |
| Surfboard-tg-mixed | 7066 | yes | 3.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.3 | 0 |
| barry-far-vless | 5601 | yes | 2.05 | 0 |
| Surfboard-tg-vless | 5426 | yes | 4.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.59 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 1.06 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 20 |
| speed | 14 |
| geo | 5 |
| sing-box exited 1 | 1 |
