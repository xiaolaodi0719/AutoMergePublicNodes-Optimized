# AutoNodes 每日报告

生成时间：2026-09-16 04:30:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85237 |
| 去重后节点数 | 23245 |
| TCP 可达数 | 3000 |
| 真测通过数 | 574 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23245 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 82.9 |
| geo | 1.4 |
| probe | 350.4 |
| real_test | 569.8 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 29 | 4 | 87.9% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 61 | 38 | 23 | 62.3% |
| vless | 710 | 333 | 377 | 46.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 222 |
| geo:ClientOSError | 56 |
| speed:TimeoutError | 47 |
| speed:ClientOSError | 33 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 15 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 12 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5258 |
| ConnectionRefusedError | 848 |
| gaierror | 436 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.947 | prefer | 260 | 0.885 | 1634 |
| ermaozi | 0.868 | prefer | 25 | 0.88 | 407 |
| Surfboard-tg-mixed | 0.864 | prefer | 86 | 0.791 | 7549 |
| mheidari-all | 0.663 | observe | 113 | 0.584 | 16114 |
| ermaozi-get_subscribe | 0.485 | observe | 9 | 0.778 | 438 |
| DeltaKronecker-all | 0.441 | observe | 497 | 0.36 | 5932 |
| ninja-vless | 0.279 | observe | 2 | 0.5 | 1791 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 163 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8042 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.36 | 179 | 318 | 497 |
| ninja-vless | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.584 | 66 | 47 | 113 |
| ermaozi-get_subscribe | 0.778 | 7 | 2 | 9 |
| Surfboard-tg-mixed | 0.791 | 68 | 18 | 86 |
| ermaozi | 0.88 | 22 | 3 | 25 |
| Au1rxx-base64 | 0.885 | 230 | 30 | 260 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16114 | yes | 3.42 | 0 |
| SoliSpirit-all | 8939 | yes | 3.15 | 0 |
| Epodonios-all | 8042 | yes | 4.02 | 0 |
| Surfboard-tg-mixed | 7549 | yes | 2.73 | 0 |
| barry-far-vless | 6344 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 6134 | yes | 2.9 | 0 |
| DeltaKronecker-all | 5932 | yes | 3.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 0.61 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 279 |
| speed | 80 |
| 204 | 31 |
| cn-block | 31 |
