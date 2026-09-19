# AutoNodes 每日报告

生成时间：2026-09-19 20:30:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 91271 |
| 去重后节点数 | 25369 |
| TCP 可达数 | 3000 |
| 真测通过数 | 509 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25369 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 81.8 |
| geo | 1.4 |
| probe | 223.6 |
| real_test | 212.1 |
| tcp | 41.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 26 | 22 | 4 | 84.6% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 160 | 146 | 14 | 91.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 20 | 8 | 12 | 40.0% |
| vless | 430 | 317 | 113 | 73.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 34 |
| geo:ClientOSError | 26 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 15 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5509 |
| ConnectionRefusedError | 920 |
| gaierror | 447 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.918 | prefer | 303 | 0.855 | 1650 |
| mheidari-all | 0.917 | prefer | 47 | 0.851 | 19269 |
| ermaozi | 0.856 | prefer | 24 | 0.875 | 250 |
| DeltaKronecker-all | 0.797 | prefer | 150 | 0.72 | 6421 |
| Surfboard-tg-mixed | 0.702 | prefer | 125 | 0.624 | 7211 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7761 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.624 | 78 | 47 | 125 |
| DeltaKronecker-all | 0.72 | 108 | 42 | 150 |
| mheidari-all | 0.851 | 40 | 7 | 47 |
| Au1rxx-base64 | 0.855 | 259 | 44 | 303 |
| ermaozi | 0.875 | 21 | 3 | 24 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19269 | yes | 5.58 | 0 |
| SoliSpirit-all | 9098 | yes | 4.69 | 0 |
| Epodonios-all | 7761 | yes | 5.04 | 0 |
| Surfboard-tg-mixed | 7211 | yes | 4.17 | 0 |
| DeltaKronecker-all | 6421 | yes | 6.19 | 0 |
| barry-far-vless | 6077 | yes | 2.05 | 0 |
| Surfboard-tg-vless | 5765 | yes | 3.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 2.28 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 0.2 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 62 |
| 204 | 34 |
| cn-block | 28 |
| speed | 21 |
