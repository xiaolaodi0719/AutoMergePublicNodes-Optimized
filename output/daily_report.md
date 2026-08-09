# AutoNodes 每日报告

生成时间：2026-08-09 13:05:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 85362 |
| 去重后节点数 | 23924 |
| TCP 可达数 | 3000 |
| 真测通过数 | 480 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23924 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 46.5 |
| geo | 1.4 |
| probe | 48.1 |
| real_test | 113.8 |
| tcp | 35.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 144 | 133 | 11 | 92.4% |
| socks | 17 | 11 | 6 | 64.7% |
| trojan | 134 | 129 | 5 | 96.3% |
| vless | 268 | 163 | 105 | 60.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 31 |
| speed:TimeoutError | 27 |
| 204:TimeoutError | 16 |
| cn-block:TimeoutError | 13 |
| geo:TimeoutError | 12 |
| 204:ProxyError | 11 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5003 |
| ConnectionRefusedError | 823 |
| gaierror | 288 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | prefer | 410 | 0.907 | 1704 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.772 | prefer | 105 | 0.695 | 6480 |
| mheidari-all | 0.286 | observe | 66 | 0.197 | 20170 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 77 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5505 |
| Epodonios-all | 0.255 | observe | 0 | None | 7128 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7369 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5320 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.197 | 13 | 53 | 66 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| Surfboard-tg-mixed | 0.695 | 73 | 32 | 105 |
| Au1rxx-base64 | 0.907 | 372 | 38 | 410 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20170 | yes | 3.98 | 0 |
| SoliSpirit-all | 7369 | yes | 1.96 | 0 |
| Epodonios-all | 7128 | yes | 5.02 | 0 |
| Surfboard-tg-mixed | 6480 | yes | 3.0 | 0 |
| barry-far-vless | 5659 | yes | 0.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 0.49 | 0 |
| Surfboard-tg-vless | 5320 | yes | 3.34 | 0 |
| mahdibland-V2RayAggregator | 5130 | yes | 2.55 | 0 |
| DeltaKronecker-all | 4998 | yes | 4.05 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 44 |
| speed | 36 |
| 204 | 29 |
| cn-block | 18 |
