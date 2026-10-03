# AutoNodes 每日报告

生成时间：2026-10-03 16:09:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99539 |
| 去重后节点数 | 27335 |
| TCP 可达数 | 3000 |
| 真测通过数 | 350 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27335 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 101.7 |
| geo | 0.9 |
| probe | 211.8 |
| real_test | 148.2 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 23 | 16 | 7 | 69.6% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 126 | 109 | 17 | 86.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 26 | 19 | 7 | 73.1% |
| vless | 238 | 189 | 49 | 79.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 20 |
| 204:ProxyConnectionError | 11 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| geo:ClientOSError | 2 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6640 |
| ConnectionRefusedError | 1146 |
| gaierror | 435 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | prefer | 261 | 0.866 | 1778 |
| mheidari-all | 0.868 | prefer | 50 | 0.8 | 23342 |
| Surfboard-tg-mixed | 0.781 | prefer | 95 | 0.705 | 7404 |
| ermaozi | 0.706 | prefer | 23 | 0.696 | 656 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 478 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5207 |
| Epodonios-all | 0.255 | observe | 0 | None | 7883 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9374 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.696 | 16 | 7 | 23 |
| Surfboard-tg-mixed | 0.705 | 67 | 28 | 95 |
| mheidari-all | 0.8 | 40 | 10 | 50 |
| Au1rxx-base64 | 0.866 | 226 | 35 | 261 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23342 | yes | 7.07 | 0 |
| SoliSpirit-all | 9374 | yes | 2.87 | 0 |
| Epodonios-all | 7883 | yes | 4.1 | 0 |
| Surfboard-tg-mixed | 7404 | yes | 3.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.24 | 0 |
| barry-far-vless | 6273 | yes | 1.59 | 0 |
| Surfboard-tg-vless | 6035 | yes | 4.66 | 0 |
| DeltaKronecker-all | 5207 | yes | 5.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 1.08 | 0 |
| mahdibland-V2RayAggregator | 4335 | yes | 3.42 | 0 |

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
| 204 | 40 |
| cn-block | 26 |
| speed | 10 |
| geo | 6 |
