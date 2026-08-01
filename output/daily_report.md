# AutoNodes 每日报告

生成时间：2026-08-01 13:43:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78943 |
| 去重后节点数 | 23426 |
| TCP 可达数 | 3000 |
| 真测通过数 | 610 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23426 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 28.9 |
| geo | 1.5 |
| probe | 51.6 |
| real_test | 140.3 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 146 | 146 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 158 | 134 | 24 | 84.8% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 51 | 48 | 3 | 94.1% |
| vless | 411 | 265 | 146 | 64.5% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 48 |
| geo:TimeoutError | 37 |
| speed:TimeoutError | 30 |
| 204:ProxyError | 14 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 14 |
| geo:ClientOSError | 9 |
| 204:ClientOSError | 8 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4617 |
| ConnectionRefusedError | 772 |
| gaierror | 310 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.994 | prefer | 148 | 0.993 | 194 |
| DeltaKronecker-all | 0.889 | prefer | 45 | 0.822 | 5502 |
| Au1rxx-base64 | 0.81 | prefer | 487 | 0.743 | 1689 |
| Surfboard-tg-mixed | 0.662 | observe | 96 | 0.583 | 5351 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 16460 |
| SoliSpirit-all | 0.391 | observe | 2 | 1.0 | 6948 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| tg-v2nodes | 0.256 | observe | 1 | 1.0 | 20 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5391 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.583 | 56 | 40 | 96 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.743 | 362 | 125 | 487 |
| DeltaKronecker-all | 0.822 | 37 | 8 | 45 |
| zhangkai | 0.993 | 147 | 1 | 148 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-v2nodes | 1.0 | 1 | 0 | 1 |
| SoliSpirit-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16460 | yes | 5.03 | 0 |
| SoliSpirit-all | 6948 | yes | 4.29 | 0 |
| Epodonios-all | 5964 | yes | 5.62 | 0 |
| DeltaKronecker-all | 5502 | yes | 5.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 3.51 | 0 |
| Surfboard-tg-mixed | 5351 | yes | 4.08 | 0 |
| mahdibland-V2RayAggregator | 5039 | yes | 3.1 | 0 |
| barry-far-vless | 4602 | yes | 2.79 | 0 |
| Surfboard-tg-vless | 4224 | yes | 4.23 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 70 |
| geo | 48 |
| speed | 44 |
| cn-block | 17 |
