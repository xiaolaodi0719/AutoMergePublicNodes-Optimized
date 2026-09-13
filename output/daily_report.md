# AutoNodes 每日报告

生成时间：2026-09-13 16:07:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 95131 |
| 去重后节点数 | 25342 |
| TCP 可达数 | 3000 |
| 真测通过数 | 419 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25342 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.4 |
| generate | 78.3 |
| geo | 1.4 |
| probe | 276.6 |
| real_test | 243.8 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 41 | 25 | 16 | 61.0% |
| hysteria2 | 23 | 16 | 7 | 69.6% |
| shadowsocks | 155 | 143 | 12 | 92.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 18 | 17 | 1 | 94.4% |
| vless | 353 | 215 | 138 | 60.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 51 |
| cn-block:ClientOSError | 39 |
| speed:ClientOSError | 28 |
| 204:ProxyError | 18 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5505 |
| ConnectionRefusedError | 968 |
| gaierror | 494 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.911 | prefer | 300 | 0.847 | 1678 |
| Surfboard-tg-mixed | 0.8 | prefer | 98 | 0.724 | 7605 |
| ermaozi | 0.682 | observe | 34 | 0.676 | 382 |
| mheidari-all | 0.53 | observe | 147 | 0.449 | 20611 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7899 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9265 |

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
| downweight | ermaozi-get_subscribe | 0.199 | 8 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| ermaozi-get_subscribe | 0.25 | 2 | 6 | 8 |
| mheidari-all | 0.449 | 66 | 81 | 147 |
| ermaozi | 0.676 | 23 | 11 | 34 |
| Surfboard-tg-mixed | 0.724 | 71 | 27 | 98 |
| Au1rxx-base64 | 0.847 | 254 | 46 | 300 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20611 | yes | 5.64 | 0 |
| SoliSpirit-all | 9265 | yes | 6.21 | 0 |
| Epodonios-all | 7899 | yes | 6.0 | 0 |
| Surfboard-tg-mixed | 7605 | yes | 4.25 | 0 |
| barry-far-vless | 6452 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 6236 | yes | 3.65 | 0 |
| DeltaKronecker-all | 5892 | yes | 6.1 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 1.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4221 | yes | 0.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 55 |
| geo | 54 |
| 204 | 33 |
| speed | 33 |
