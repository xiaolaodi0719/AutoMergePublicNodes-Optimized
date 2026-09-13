# AutoNodes 每日报告

生成时间：2026-09-13 20:44:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 90275 |
| 去重后节点数 | 25551 |
| TCP 可达数 | 3000 |
| 真测通过数 | 455 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25551 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 81.1 |
| geo | 1.6 |
| probe | 268.5 |
| real_test | 199.8 |
| tcp | 43.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 23 | 15 | 60.5% |
| hysteria2 | 30 | 27 | 3 | 90.0% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 17 | 11 | 6 | 64.7% |
| vless | 328 | 242 | 86 | 73.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 29 |
| 204:ProxyError | 22 |
| cn-block:ClientOSError | 17 |
| cn-block:TimeoutError | 16 |
| speed:ClientOSError | 11 |
| 204:TimeoutError | 10 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:exit-country | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5819 |
| ConnectionRefusedError | 1000 |
| gaierror | 517 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 306 | 0.908 | 1781 |
| Surfboard-tg-mixed | 0.787 | prefer | 155 | 0.71 | 7511 |
| mheidari-all | 0.735 | prefer | 56 | 0.661 | 16210 |
| ermaozi | 0.637 | observe | 35 | 0.629 | 382 |
| xiaoji235-airport-v2ray-all | 0.412 | observe | 17 | 0.353 | 5301 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4222 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 8029 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8804 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 5 | 5 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| xiaoji235-airport-v2ray-all | 0.353 | 6 | 11 | 17 |
| ermaozi | 0.629 | 22 | 13 | 35 |
| mheidari-all | 0.661 | 37 | 19 | 56 |
| Surfboard-tg-mixed | 0.71 | 110 | 45 | 155 |
| Au1rxx-base64 | 0.908 | 278 | 28 | 306 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16210 | yes | 3.85 | 0 |
| SoliSpirit-all | 8804 | yes | 3.64 | 0 |
| Epodonios-all | 8029 | yes | 2.67 | 0 |
| Surfboard-tg-mixed | 7511 | yes | 2.94 | 0 |
| barry-far-vless | 6390 | yes | 2.48 | 0 |
| Surfboard-tg-vless | 6079 | yes | 3.09 | 0 |
| DeltaKronecker-all | 5892 | yes | 4.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 2.69 | 0 |
| mahdibland-V2RayAggregator | 4222 | yes | 0.75 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.83 | 0 |

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
| geo | 37 |
| 204 | 36 |
| cn-block | 34 |
| speed | 19 |
