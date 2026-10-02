# AutoNodes 每日报告

生成时间：2026-10-02 22:08:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98974 |
| 去重后节点数 | 27178 |
| TCP 可达数 | 3000 |
| 真测通过数 | 423 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27178 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 42.0 |
| geo | 1.4 |
| probe | 210.1 |
| real_test | 156.8 |
| tcp | 48.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 1 | 2 | 33.3% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 164 | 153 | 11 | 93.3% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 13 | 13 | 0 | 100.0% |
| vless | 257 | 220 | 37 | 85.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6935 |
| ConnectionRefusedError | 1128 |
| gaierror | 329 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | prefer | 270 | 0.896 | 1771 |
| Surfboard-tg-mixed | 0.957 | prefer | 63 | 0.889 | 7321 |
| mheidari-all | 0.956 | prefer | 111 | 0.883 | 23213 |
| ermaozi | 0.914 | prefer | 25 | 0.92 | 620 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5276 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 4981 |
| Epodonios-all | 0.255 | observe | 0 | None | 7814 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9326 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5999 |

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
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| mheidari-all | 0.883 | 98 | 13 | 111 |
| Surfboard-tg-mixed | 0.889 | 56 | 7 | 63 |
| Au1rxx-base64 | 0.896 | 242 | 28 | 270 |
| ermaozi | 0.92 | 23 | 2 | 25 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23213 | yes | 4.63 | 0 |
| SoliSpirit-all | 9326 | yes | 2.38 | 0 |
| Epodonios-all | 7814 | yes | 2.9 | 0 |
| Surfboard-tg-mixed | 7321 | yes | 0.27 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.17 | 0 |
| barry-far-vless | 6241 | yes | 1.65 | 0 |
| Surfboard-tg-vless | 5999 | yes | 3.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 1.31 | 0 |
| DeltaKronecker-all | 4981 | yes | 4.68 | 0 |
| mahdibland-V2RayAggregator | 4357 | yes | 1.8 | 0 |

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
| cn-block | 26 |
| speed | 15 |
| 204 | 14 |
| geo | 1 |
