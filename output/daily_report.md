# AutoNodes 每日报告

生成时间：2026-09-12 04:18:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83274 |
| 去重后节点数 | 23407 |
| TCP 可达数 | 3000 |
| 真测通过数 | 600 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23407 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 156.1 |
| geo | 1.4 |
| probe | 351.9 |
| real_test | 590.6 |
| tcp | 40.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 24 | 8 | 75.0% |
| hysteria2 | 25 | 24 | 1 | 96.0% |
| shadowsocks | 184 | 168 | 16 | 91.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 60 | 32 | 28 | 53.3% |
| vless | 785 | 349 | 436 | 44.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 220 |
| geo:ClientOSError | 92 |
| speed:ClientOSError | 48 |
| speed:TimeoutError | 47 |
| 204:ProxyError | 24 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| cn-block:ClientOSError | 12 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5793 |
| ConnectionRefusedError | 897 |
| gaierror | 365 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.95 | prefer | 321 | 0.885 | 1681 |
| ermaozi | 0.776 | prefer | 27 | 0.778 | 434 |
| Surfboard-tg-mixed | 0.738 | prefer | 118 | 0.661 | 7263 |
| mheidari-all | 0.584 | observe | 115 | 0.504 | 15597 |
| DeltaKronecker-all | 0.391 | observe | 497 | 0.31 | 6070 |
| ermaozi-get_subscribe | 0.311 | observe | 5 | 0.6 | 459 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| Epodonios-all | 0.255 | observe | 0 | None | 7719 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8500 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.31 | 154 | 343 | 497 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.504 | 58 | 57 | 115 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.661 | 78 | 40 | 118 |
| ermaozi | 0.778 | 21 | 6 | 27 |
| Au1rxx-base64 | 0.885 | 284 | 37 | 321 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15597 | yes | 5.41 | 0 |
| SoliSpirit-all | 8500 | yes | 1.94 | 0 |
| Epodonios-all | 7719 | yes | 3.55 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 4.7 | 0 |
| barry-far-vless | 6106 | yes | 1.1 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.35 | 0 |
| Surfboard-tg-vless | 5889 | yes | 4.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 0.89 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 3.24 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.65 | 0 |

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
| geo | 312 |
| speed | 96 |
| 204 | 50 |
| cn-block | 32 |
