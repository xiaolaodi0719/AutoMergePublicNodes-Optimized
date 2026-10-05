# AutoNodes 每日报告

生成时间：2026-10-05 14:18:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98609 |
| 去重后节点数 | 27263 |
| TCP 可达数 | 3000 |
| 真测通过数 | 413 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27263 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 146.4 |
| geo | 1.4 |
| probe | 224.6 |
| real_test | 165.7 |
| tcp | 46.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 0 | 2 | 0.0% |
| http | 66 | 32 | 34 | 48.5% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 145 | 135 | 10 | 93.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 92 | 78 | 14 | 84.8% |
| vless | 188 | 147 | 41 | 78.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 32 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 17 |
| 204:ProxyConnectionError | 8 |
| speed:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| speed:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:41949: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6228 |
| ConnectionRefusedError | 1040 |
| gaierror | 447 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | prefer | 275 | 0.909 | 1816 |
| mheidari-all | 0.955 | prefer | 54 | 0.889 | 23423 |
| Surfboard-tg-mixed | 0.818 | prefer | 105 | 0.743 | 7151 |
| ermaozi | 0.535 | observe | 69 | 0.507 | 701 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 172 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5111 |
| Epodonios-all | 0.255 | observe | 0 | None | 7645 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9203 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5695 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.197 | 9 | 0.111 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.111 | 1 | 8 | 9 |
| ermaozi | 0.507 | 35 | 34 | 69 |
| Surfboard-tg-mixed | 0.743 | 78 | 27 | 105 |
| mheidari-all | 0.889 | 48 | 6 | 54 |
| Au1rxx-base64 | 0.909 | 250 | 25 | 275 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23423 | yes | 6.41 | 0 |
| SoliSpirit-all | 9203 | yes | 3.48 | 0 |
| Epodonios-all | 7645 | yes | 6.62 | 0 |
| Surfboard-tg-mixed | 7151 | yes | 3.95 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.17 | 0 |
| barry-far-vless | 5930 | yes | 2.42 | 0 |
| Surfboard-tg-vless | 5695 | yes | 4.14 | 0 |
| DeltaKronecker-all | 5300 | yes | 6.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 2.21 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 2.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 61 |
| cn-block | 22 |
| geo | 10 |
| speed | 9 |
| sing-box exited 1 | 1 |
