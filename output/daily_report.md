# AutoNodes 每日报告

生成时间：2026-09-06 15:19:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94591 |
| 去重后节点数 | 24561 |
| TCP 可达数 | 3000 |
| 真测通过数 | 488 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24561 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 44.8 |
| geo | 1.5 |
| probe | 87.6 |
| real_test | 118.4 |
| tcp | 41.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 9 | 14 | 39.1% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 154 | 144 | 10 | 93.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 27 | 24 | 3 | 88.9% |
| vless | 361 | 283 | 78 | 78.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 20 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 15 |
| 204:ProxyConnectionError | 14 |
| geo:ClientOSError | 12 |
| speed:TimeoutError | 8 |
| 204:ProxyError | 7 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5286 |
| ConnectionRefusedError | 1022 |
| gaierror | 388 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 348 | 0.894 | 1876 |
| Surfboard-tg-mixed | 0.835 | prefer | 161 | 0.758 | 7393 |
| mheidari-all | 0.789 | prefer | 53 | 0.717 | 21148 |
| DeltaKronecker-all | 0.529 | observe | 7 | 0.857 | 5856 |
| zhangkai | 0.46 | observe | 20 | 0.45 | 144 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5750 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| Epodonios-all | 0.255 | observe | 0 | None | 7776 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8812 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 3 | 3 |
| zhangkai | 0.45 | 9 | 11 | 20 |
| mheidari-all | 0.717 | 38 | 15 | 53 |
| Surfboard-tg-mixed | 0.758 | 122 | 39 | 161 |
| DeltaKronecker-all | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.894 | 311 | 37 | 348 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21148 | yes | 5.39 | 0 |
| SoliSpirit-all | 8812 | yes | 5.6 | 0 |
| Epodonios-all | 7776 | yes | 5.61 | 0 |
| Surfboard-tg-mixed | 7393 | yes | 3.38 | 0 |
| barry-far-vless | 6226 | yes | 2.6 | 0 |
| Surfboard-tg-vless | 6147 | yes | 3.79 | 0 |
| DeltaKronecker-all | 5856 | yes | 6.23 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 3.34 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 2.9 | 0 |
| mahdibland-V2RayAggregator | 4111 | yes | 1.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 43 |
| cn-block | 36 |
| geo | 15 |
| speed | 13 |
