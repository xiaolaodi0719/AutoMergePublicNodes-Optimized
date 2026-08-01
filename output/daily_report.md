# AutoNodes 每日报告

生成时间：2026-08-01 08:33:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78775 |
| 去重后节点数 | 23170 |
| TCP 可达数 | 3000 |
| 真测通过数 | 621 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23170 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 35.1 |
| geo | 1.3 |
| probe | 65.8 |
| real_test | 167.7 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 155 | 155 | 0 | 100.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 157 | 129 | 28 | 82.2% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 42 | 35 | 7 | 83.3% |
| vless | 624 | 283 | 341 | 45.4% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 140 |
| speed:TimeoutError | 53 |
| geo:ClientOSError | 51 |
| speed:ClientOSError | 39 |
| 204:TimeoutError | 39 |
| cn-block:TimeoutError | 26 |
| 204:ProxyError | 21 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4629 |
| ConnectionRefusedError | 751 |
| gaierror | 232 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 157 | 1.0 | 228 |
| Au1rxx-base64 | 0.769 | prefer | 506 | 0.704 | 1655 |
| Surfboard-tg-mixed | 0.506 | observe | 92 | 0.424 | 5316 |
| DeltaKronecker-all | 0.354 | observe | 232 | 0.272 | 5502 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| mheidari-all | 0.314 | observe | 9 | 0.333 | 16723 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| tg-v2nodes | 0.256 | observe | 1 | 1.0 | 20 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5391 |
| Epodonios-all | 0.255 | observe | 0 | None | 5937 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.272 | 63 | 169 | 232 |
| mheidari-all | 0.333 | 3 | 6 | 9 |
| Surfboard-tg-mixed | 0.424 | 39 | 53 | 92 |
| Au1rxx-base64 | 0.704 | 356 | 150 | 506 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-v2nodes | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 157 | 0 | 157 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16723 | yes | 4.68 | 0 |
| SoliSpirit-all | 6670 | yes | 3.12 | 0 |
| Epodonios-all | 5937 | yes | 5.12 | 0 |
| DeltaKronecker-all | 5502 | yes | 5.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 1.92 | 0 |
| Surfboard-tg-mixed | 5316 | yes | 4.88 | 0 |
| mahdibland-V2RayAggregator | 5039 | yes | 2.91 | 0 |
| barry-far-vless | 4552 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 4168 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 191 |
| speed | 92 |
| 204 | 67 |
| cn-block | 31 |
