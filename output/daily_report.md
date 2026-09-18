# AutoNodes 每日报告

生成时间：2026-09-18 20:52:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 87619 |
| 去重后节点数 | 25094 |
| TCP 可达数 | 3000 |
| 真测通过数 | 458 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25094 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 77.5 |
| geo | 1.4 |
| probe | 289.5 |
| real_test | 228.3 |
| tcp | 42.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 22 | 11 | 66.7% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 165 | 150 | 15 | 90.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 7 | 5 | 2 | 71.4% |
| vless | 403 | 259 | 144 | 64.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 40 |
| geo:ClientOSError | 38 |
| 204:ProxyError | 24 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 12 |
| geo:TimeoutError | 12 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5884 |
| ConnectionRefusedError | 908 |
| gaierror | 423 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.928 | prefer | 277 | 0.866 | 1615 |
| ermaozi | 0.828 | prefer | 25 | 0.84 | 325 |
| Surfboard-tg-mixed | 0.756 | prefer | 146 | 0.678 | 7333 |
| mheidari-all | 0.638 | observe | 170 | 0.559 | 19747 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5076 |
| Epodonios-all | 0.255 | observe | 0 | None | 7771 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8922 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.136 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| mheidari-all | 0.559 | 95 | 75 | 170 |
| Surfboard-tg-mixed | 0.678 | 99 | 47 | 146 |
| ermaozi | 0.84 | 21 | 4 | 25 |
| Au1rxx-base64 | 0.866 | 240 | 37 | 277 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19747 | yes | 6.93 | 0 |
| SoliSpirit-all | 8922 | yes | 4.91 | 0 |
| Epodonios-all | 7771 | yes | 3.21 | 0 |
| Surfboard-tg-mixed | 7333 | yes | 4.19 | 0 |
| barry-far-vless | 6051 | yes | 2.81 | 0 |
| DeltaKronecker-all | 6040 | yes | 3.93 | 0 |
| Surfboard-tg-vless | 5838 | yes | 5.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 2.56 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 0.73 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.33 | 0 |

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
| cn-block | 61 |
| geo | 50 |
| 204 | 45 |
| speed | 18 |
