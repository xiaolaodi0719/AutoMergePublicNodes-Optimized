# AutoNodes 每日报告

生成时间：2026-09-05 20:14:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97140 |
| 去重后节点数 | 25671 |
| TCP 可达数 | 3000 |
| 真测通过数 | 489 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25671 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 36.9 |
| geo | 1.4 |
| probe | 87.6 |
| real_test | 121.5 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 29 | 17 | 12 | 58.6% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 162 | 152 | 10 | 93.8% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 20 | 14 | 6 | 70.0% |
| vless | 405 | 277 | 128 | 68.4% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 47 |
| 204:ProxyError | 38 |
| geo:ClientOSError | 18 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| 204:ProxyConnectionError | 12 |
| speed:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5459 |
| ConnectionRefusedError | 1019 |
| gaierror | 415 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.886 | prefer | 356 | 0.817 | 1764 |
| Surfboard-tg-mixed | 0.877 | prefer | 151 | 0.801 | 7292 |
| mheidari-all | 0.621 | observe | 109 | 0.541 | 22630 |
| zhangkai | 0.606 | observe | 23 | 0.609 | 144 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6965 |
| tg-oneclickvpnkeys | 0.278 | observe | 6 | 0.5 | 132 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4887 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6212 |
| Epodonios-all | 0.255 | observe | 0 | None | 7653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-oneclickvpnkeys | 0.5 | 3 | 3 | 6 |
| mheidari-all | 0.541 | 59 | 50 | 109 |
| zhangkai | 0.609 | 14 | 9 | 23 |
| Surfboard-tg-mixed | 0.801 | 121 | 30 | 151 |
| Au1rxx-base64 | 0.817 | 291 | 65 | 356 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22630 | yes | 6.03 | 0 |
| SoliSpirit-all | 8694 | yes | 3.83 | 0 |
| Epodonios-all | 7653 | yes | 3.24 | 0 |
| Surfboard-tg-mixed | 7292 | yes | 3.6 | 0 |
| xiaoji235-airport-v2ray-all | 6965 | yes | 3.45 | 0 |
| barry-far-vless | 6249 | yes | 2.62 | 0 |
| DeltaKronecker-all | 6212 | yes | 5.86 | 0 |
| Surfboard-tg-vless | 6126 | yes | 3.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 2.91 | 0 |
| mahdibland-V2RayAggregator | 4087 | yes | 0.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 66 |
| cn-block | 65 |
| geo | 20 |
| speed | 6 |
