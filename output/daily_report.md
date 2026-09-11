# AutoNodes 每日报告

生成时间：2026-09-11 16:23:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 5/101 |
| 原始节点数 | 83892 |
| 去重后节点数 | 23232 |
| TCP 可达数 | 3000 |
| 真测通过数 | 420 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23232 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 84.0 |
| geo | 1.5 |
| probe | 255.3 |
| real_test | 239.9 |
| tcp | 40.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 23 | 12 | 65.7% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 150 | 137 | 13 | 91.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 20 | 17 | 3 | 85.0% |
| vless | 323 | 223 | 100 | 69.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 42 |
| 204:ProxyError | 19 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 11 |
| 204:TimeoutError | 11 |
| geo:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 5 |
| geo:ProxyError | 3 |
| 204:ProxyConnectionError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5395 |
| ConnectionRefusedError | 890 |
| gaierror | 405 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.941 | prefer | 34 | 0.882 | 15708 |
| Au1rxx-base64 | 0.895 | prefer | 255 | 0.827 | 1758 |
| Surfboard-tg-mixed | 0.816 | prefer | 89 | 0.742 | 7370 |
| ermaozi | 0.748 | prefer | 28 | 0.75 | 377 |
| DeltaKronecker-all | 0.732 | prefer | 136 | 0.654 | 6070 |
| tg-oneclickvpnkeys | 0.32 | observe | 2 | 1.0 | 228 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7833 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8514 |

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
| downweight | ermaozi-get_subscribe | 0.152 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.167 | 1 | 5 | 6 |
| DeltaKronecker-all | 0.654 | 89 | 47 | 136 |
| Surfboard-tg-mixed | 0.742 | 66 | 23 | 89 |
| ermaozi | 0.75 | 21 | 7 | 28 |
| Au1rxx-base64 | 0.827 | 211 | 44 | 255 |
| mheidari-all | 0.882 | 30 | 4 | 34 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15708 | yes | 5.62 | 0 |
| SoliSpirit-all | 8514 | yes | 1.98 | 0 |
| Epodonios-all | 7833 | yes | 3.51 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 4.34 | 0 |
| barry-far-vless | 6192 | yes | 1.5 | 0 |
| DeltaKronecker-all | 6070 | yes | 4.91 | 0 |
| Surfboard-tg-vless | 5979 | yes | 4.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 0.76 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 3.7 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.58 | 0 |

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
| geo | 52 |
| 204 | 38 |
| cn-block | 25 |
| speed | 16 |
