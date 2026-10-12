# AutoNodes 每日报告

生成时间：2026-10-12 15:10:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 100392 |
| 去重后节点数 | 27824 |
| TCP 可达数 | 3000 |
| 真测通过数 | 407 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27824 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 86.1 |
| geo | 1.7 |
| probe | 291.1 |
| real_test | 361.2 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 52 | 25 | 27 | 48.1% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 127 | 110 | 17 | 86.6% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 153 | 126 | 27 | 82.4% |
| vless | 170 | 132 | 38 | 77.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 26 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 12 |
| 204:ProxyConnectionError | 7 |
| geo:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| speed:ClientOSError | 6 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38306: bind: address already in use | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6400 |
| ConnectionRefusedError | 1060 |
| gaierror | 383 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 318 | 0.912 | 1816 |
| mheidari-all | 0.788 | prefer | 22 | 0.727 | 24027 |
| Surfboard-tg-mixed | 0.747 | prefer | 70 | 0.671 | 7166 |
| DeltaKronecker-all | 0.571 | observe | 51 | 0.49 | 5701 |
| ermaozi | 0.518 | observe | 51 | 0.49 | 675 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4314 |
| ermaozi-get_subscribe | 0.333 | observe | 2 | 1.0 | 532 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5028 |
| Epodonios-all | 0.255 | observe | 0 | None | 7671 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.49 | 25 | 26 | 51 |
| DeltaKronecker-all | 0.49 | 25 | 26 | 51 |
| Surfboard-tg-mixed | 0.671 | 47 | 23 | 70 |
| mheidari-all | 0.727 | 16 | 6 | 22 |
| Au1rxx-base64 | 0.912 | 290 | 28 | 318 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24027 | yes | 6.91 | 0 |
| SoliSpirit-all | 9940 | yes | 2.69 | 0 |
| Epodonios-all | 7671 | yes | 5.71 | 0 |
| Surfboard-tg-mixed | 7166 | yes | 4.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.02 | 0 |
| barry-far-vless | 6031 | yes | 1.23 | 0 |
| Surfboard-tg-vless | 5781 | yes | 4.0 | 0 |
| DeltaKronecker-all | 5701 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5028 | yes | 0.76 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 3.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 54 |
| cn-block | 23 |
| speed | 18 |
| geo | 15 |
| sing-box exited 1 | 1 |
