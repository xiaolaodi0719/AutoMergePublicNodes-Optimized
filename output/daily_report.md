# AutoNodes 每日报告

生成时间：2026-08-16 01:46:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 79337 |
| 去重后节点数 | 22383 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1139 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22383 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 36.8 |
| geo | 0.9 |
| probe | 70.4 |
| real_test | 249.2 |
| tcp | 34.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 152 | 149 | 3 | 98.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 600 | 592 | 8 | 98.7% |
| vless | 517 | 251 | 266 | 48.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 101 |
| speed:TimeoutError | 71 |
| cn-block:TimeoutError | 33 |
| geo:ClientOSError | 32 |
| speed:ClientOSError | 20 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4583 |
| ConnectionRefusedError | 794 |
| gaierror | 322 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 784 | 0.977 | 1995 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.789 | prefer | 139 | 0.712 | 5707 |
| mheidari-all | 0.575 | observe | 277 | 0.495 | 16315 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 2601 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 145 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1995 |
| Epodonios-all | 0.255 | observe | 0 | None | 6340 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3984 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7329 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| DeltaKronecker-all | 0.172 | downweight | 85 | 0.082 | 0 | 5773 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.172 | 85 | 0.082 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.082 | 7 | 78 | 85 |
| mheidari-all | 0.495 | 137 | 140 | 277 |
| Surfboard-tg-mixed | 0.712 | 99 | 40 | 139 |
| Au1rxx-base64 | 0.977 | 766 | 18 | 784 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16315 | yes | 4.28 | 0 |
| SoliSpirit-all | 7329 | yes | 1.97 | 0 |
| Epodonios-all | 6340 | yes | 2.92 | 0 |
| DeltaKronecker-all | 5773 | yes | 4.74 | 0 |
| Surfboard-tg-mixed | 5707 | yes | 3.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 1.54 | 0 |
| barry-far-vless | 4782 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 4387 | yes | 4.43 | 0 |
| MatinGhanbari-all-sub | 3984 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 2.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 134 |
| speed | 92 |
| cn-block | 41 |
| 204 | 12 |
