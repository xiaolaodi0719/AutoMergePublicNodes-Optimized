# AutoNodes 每日报告

生成时间：2026-09-10 20:52:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83486 |
| 去重后节点数 | 22839 |
| TCP 可达数 | 3000 |
| 真测通过数 | 391 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22839 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 152.4 |
| geo | 1.5 |
| probe | 284.9 |
| real_test | 225.2 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 18 | 7 | 72.0% |
| hysteria2 | 19 | 14 | 5 | 73.7% |
| shadowsocks | 155 | 138 | 17 | 89.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 21 | 13 | 8 | 61.9% |
| vless | 288 | 208 | 80 | 72.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 21 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 19 |
| cn-block:ClientOSError | 12 |
| geo:TimeoutError | 12 |
| 204:ProxyError | 9 |
| 204:ProxyConnectionError | 7 |
| 204:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4733 |
| ConnectionRefusedError | 902 |
| gaierror | 442 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.928 | prefer | 260 | 0.865 | 1642 |
| DeltaKronecker-all | 0.83 | prefer | 22 | 0.773 | 5853 |
| Surfboard-tg-mixed | 0.751 | prefer | 138 | 0.674 | 7221 |
| ermaozi | 0.683 | observe | 25 | 0.68 | 405 |
| mheidari-all | 0.68 | observe | 58 | 0.603 | 15823 |
| roosterkid-openproxylist-v2ray | 0.364 | observe | 3 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| Epodonios-all | 0.255 | observe | 0 | None | 7677 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8881 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.603 | 35 | 23 | 58 |
| Surfboard-tg-mixed | 0.674 | 93 | 45 | 138 |
| ermaozi | 0.68 | 17 | 8 | 25 |
| DeltaKronecker-all | 0.773 | 17 | 5 | 22 |
| Au1rxx-base64 | 0.865 | 225 | 35 | 260 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15823 | yes | 4.69 | 0 |
| SoliSpirit-all | 8881 | yes | 1.45 | 0 |
| Epodonios-all | 7677 | yes | 4.91 | 0 |
| Surfboard-tg-mixed | 7221 | yes | 3.83 | 0 |
| barry-far-vless | 6058 | yes | 1.18 | 0 |
| DeltaKronecker-all | 5853 | yes | 5.26 | 0 |
| Surfboard-tg-vless | 5840 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 0.48 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.91 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.75 | 0 |

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
| 204 | 42 |
| cn-block | 33 |
| geo | 33 |
| speed | 11 |
