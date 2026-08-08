# AutoNodes 每日报告

生成时间：2026-08-08 02:01:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82250 |
| 去重后节点数 | 23592 |
| TCP 可达数 | 3000 |
| 真测通过数 | 581 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23592 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 36.2 |
| geo | 1.0 |
| probe | 52.4 |
| real_test | 123.7 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 167 | 159 | 8 | 95.2% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 163 | 147 | 16 | 90.2% |
| vless | 405 | 227 | 178 | 56.0% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 80 |
| speed:TimeoutError | 37 |
| geo:ClientOSError | 26 |
| speed:ClientOSError | 19 |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 12 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32762: bind: address already in use | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4639 |
| ConnectionRefusedError | 828 |
| gaierror | 342 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 440 | 0.955 | 1365 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.663 | observe | 34 | 0.588 | 6471 |
| mheidari-all | 0.568 | observe | 211 | 0.488 | 17687 |
| DeltaKronecker-all | 0.311 | observe | 76 | 0.224 | 5326 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7081 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7469 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5179 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.224 | 17 | 59 | 76 |
| mheidari-all | 0.488 | 103 | 108 | 211 |
| Surfboard-tg-mixed | 0.588 | 20 | 14 | 34 |
| Au1rxx-base64 | 0.955 | 420 | 20 | 440 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17687 | yes | 3.65 | 0 |
| SoliSpirit-all | 7469 | yes | 2.35 | 0 |
| Epodonios-all | 7081 | yes | 4.25 | 0 |
| Surfboard-tg-mixed | 6471 | yes | 2.73 | 0 |
| barry-far-vless | 5509 | yes | 1.01 | 0 |
| DeltaKronecker-all | 5326 | yes | 4.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 1.83 | 0 |
| Surfboard-tg-vless | 5179 | yes | 2.97 | 0 |
| mahdibland-V2RayAggregator | 5175 | yes | 2.34 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 107 |
| speed | 57 |
| 204 | 21 |
| cn-block | 17 |
| sing-box exited 1 | 1 |
