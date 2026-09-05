# AutoNodes 每日报告

生成时间：2026-09-05 03:55:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84344 |
| 去重后节点数 | 23684 |
| TCP 可达数 | 3000 |
| 真测通过数 | 531 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23684 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 43.7 |
| geo | 1.4 |
| probe | 90.0 |
| real_test | 132.3 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 105 | 105 | 0 | 100.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 80 | 48 | 32 | 60.0% |
| vless | 476 | 327 | 149 | 68.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 85 |
| speed:TimeoutError | 39 |
| geo:ClientOSError | 21 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4827 |
| ConnectionRefusedError | 897 |
| gaierror | 342 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | prefer | 380 | 0.911 | 1796 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| mheidari-all | 0.69 | observe | 193 | 0.611 | 16194 |
| tg-oneclickvpnkeys | 0.554 | observe | 8 | 1.0 | 135 |
| Surfboard-tg-mixed | 0.53 | observe | 10 | 0.7 | 7291 |
| DeltaKronecker-all | 0.393 | observe | 97 | 0.309 | 7089 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 4810 |
| Epodonios-all | 0.255 | observe | 0 | None | 7727 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8350 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.309 | 30 | 67 | 97 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.611 | 118 | 75 | 193 |
| Surfboard-tg-mixed | 0.7 | 7 | 3 | 10 |
| Au1rxx-base64 | 0.911 | 346 | 34 | 380 |
| tg-oneclickvpnkeys | 1.0 | 8 | 0 | 8 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16194 | yes | 4.56 | 0 |
| SoliSpirit-all | 8350 | yes | 4.12 | 0 |
| Epodonios-all | 7727 | yes | 4.86 | 0 |
| Surfboard-tg-mixed | 7291 | yes | 4.17 | 0 |
| DeltaKronecker-all | 7089 | yes | 5.39 | 0 |
| barry-far-vless | 6282 | yes | 2.54 | 0 |
| Surfboard-tg-vless | 6083 | yes | 3.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 2.83 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 3.06 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 106 |
| speed | 42 |
| cn-block | 21 |
| 204 | 14 |
