# AutoNodes 每日报告

生成时间：2026-10-03 20:59:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99458 |
| 去重后节点数 | 27317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 437 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 78.3 |
| geo | 0.8 |
| probe | 239.8 |
| real_test | 168.4 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 22 | 2 | 91.7% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 151 | 134 | 17 | 88.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 48 | 44 | 4 | 91.7% |
| vless | 265 | 220 | 45 | 83.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| 204:TimeoutError | 14 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 7 |
| speed:ClientOSError | 4 |
| geo:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38387: bind: address already in use | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6839 |
| ConnectionRefusedError | 1146 |
| gaierror | 340 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 323 | 0.901 | 1802 |
| Surfboard-tg-mixed | 0.928 | prefer | 44 | 0.864 | 7340 |
| ermaozi | 0.878 | prefer | 25 | 0.88 | 656 |
| mheidari-all | 0.832 | prefer | 111 | 0.757 | 23599 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 5207 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7819 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9376 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5938 |

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
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| mheidari-all | 0.757 | 84 | 27 | 111 |
| Surfboard-tg-mixed | 0.864 | 38 | 6 | 44 |
| ermaozi | 0.88 | 22 | 3 | 25 |
| Au1rxx-base64 | 0.901 | 291 | 32 | 323 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23599 | yes | 3.55 | 0 |
| SoliSpirit-all | 9376 | yes | 2.71 | 0 |
| Epodonios-all | 7819 | yes | 1.87 | 0 |
| Surfboard-tg-mixed | 7340 | yes | 2.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.49 | 0 |
| barry-far-vless | 6176 | yes | 1.72 | 0 |
| Surfboard-tg-vless | 5938 | yes | 2.78 | 0 |
| DeltaKronecker-all | 5207 | yes | 3.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 1.77 | 0 |
| mahdibland-V2RayAggregator | 4285 | yes | 0.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 28 |
| 204 | 26 |
| speed | 11 |
| geo | 6 |
| sing-box exited 1 | 1 |
