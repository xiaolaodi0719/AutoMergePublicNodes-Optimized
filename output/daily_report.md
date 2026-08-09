# AutoNodes 每日报告

生成时间：2026-08-09 02:09:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82844 |
| 去重后节点数 | 23635 |
| TCP 可达数 | 3000 |
| 真测通过数 | 553 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23635 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 45.3 |
| geo | 1.3 |
| probe | 54.5 |
| real_test | 134.9 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 28 | 28 | 0 | 100.0% |
| shadowsocks | 157 | 145 | 12 | 92.4% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 122 | 115 | 7 | 94.3% |
| vless | 435 | 239 | 196 | 54.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 68 |
| speed:TimeoutError | 42 |
| cn-block:TimeoutError | 35 |
| speed:ClientOSError | 19 |
| geo:ClientOSError | 17 |
| 204:TimeoutError | 17 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4963 |
| ConnectionRefusedError | 833 |
| gaierror | 302 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 336 | 0.949 | 1540 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.74 | prefer | 151 | 0.662 | 6454 |
| mheidari-all | 0.58 | observe | 204 | 0.5 | 17775 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 123 |
| DeltaKronecker-all | 0.276 | observe | 49 | 0.184 | 5347 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7127 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7538 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.184 | 9 | 40 | 49 |
| mheidari-all | 0.5 | 102 | 102 | 204 |
| Surfboard-tg-mixed | 0.662 | 100 | 51 | 151 |
| Au1rxx-base64 | 0.949 | 319 | 17 | 336 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17775 | yes | 2.97 | 0 |
| SoliSpirit-all | 7538 | yes | 1.57 | 0 |
| Epodonios-all | 7127 | yes | 1.81 | 0 |
| Surfboard-tg-mixed | 6454 | yes | 2.59 | 0 |
| barry-far-vless | 5532 | yes | 0.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 0.53 | 0 |
| DeltaKronecker-all | 5347 | yes | 3.24 | 0 |
| Surfboard-tg-vless | 5209 | yes | 2.27 | 0 |
| mahdibland-V2RayAggregator | 5127 | yes | 1.88 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 85 |
| speed | 62 |
| cn-block | 42 |
| 204 | 26 |
