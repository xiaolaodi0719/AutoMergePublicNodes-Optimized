# AutoNodes 每日报告

生成时间：2026-09-07 12:09:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94664 |
| 去重后节点数 | 24930 |
| TCP 可达数 | 3000 |
| 真测通过数 | 507 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24930 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 43.9 |
| geo | 1.5 |
| probe | 91.2 |
| real_test | 115.3 |
| tcp | 42.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 7 | 1 | 87.5% |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 165 | 158 | 7 | 95.8% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 23 | 16 | 7 | 69.6% |
| vless | 379 | 276 | 103 | 72.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 39 |
| cn-block:ClientOSError | 22 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 11 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 5 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5615 |
| ConnectionRefusedError | 1025 |
| gaierror | 334 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 320 | 0.912 | 1781 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.84 | prefer | 148 | 0.764 | 7247 |
| mheidari-all | 0.637 | observe | 120 | 0.558 | 21631 |
| tg-oneclickvpnkeys | 0.494 | observe | 8 | 0.875 | 151 |
| DeltaKronecker-all | 0.391 | observe | 2 | 1.0 | 6417 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5750 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| Epodonios-all | 0.255 | observe | 0 | None | 7707 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.558 | 67 | 53 | 120 |
| Surfboard-tg-mixed | 0.764 | 113 | 35 | 148 |
| tg-oneclickvpnkeys | 0.875 | 7 | 1 | 8 |
| Au1rxx-base64 | 0.912 | 292 | 28 | 320 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21631 | yes | 6.08 | 0 |
| SoliSpirit-all | 8442 | yes | 4.66 | 0 |
| Epodonios-all | 7707 | yes | 3.19 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 4.45 | 0 |
| DeltaKronecker-all | 6417 | yes | 6.86 | 0 |
| barry-far-vless | 6245 | yes | 2.36 | 0 |
| Surfboard-tg-vless | 6030 | yes | 4.66 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 2.14 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 1.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 45 |
| cn-block | 36 |
| 204 | 26 |
| speed | 12 |
