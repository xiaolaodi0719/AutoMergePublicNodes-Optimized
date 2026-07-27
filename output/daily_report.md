# AutoNodes 每日报告

生成时间：2026-07-27 10:06:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84235 |
| 去重后节点数 | 22876 |
| TCP 可达数 | 3000 |
| 真测通过数 | 837 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22876 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 29.3 |
| geo | 1.4 |
| probe | 69.9 |
| real_test | 208.3 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 6 | 0 | 100.0% |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 118 | 97 | 21 | 82.2% |
| socks | 25 | 17 | 8 | 68.0% |
| trojan | 578 | 510 | 68 | 88.2% |
| vless | 402 | 119 | 283 | 29.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 148 |
| speed:ClientOSError | 68 |
| 204:TimeoutError | 39 |
| geo:ClientOSError | 33 |
| 204:ProxyError | 27 |
| cn-block:TimeoutError | 22 |
| speed:TimeoutError | 21 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 7 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4132 |
| ConnectionRefusedError | 723 |
| gaierror | 319 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| Au1rxx-base64 | 0.974 | prefer | 413 | 0.92 | 1407 |
| mheidari-all | 0.906 | prefer | 234 | 0.829 | 19339 |
| Surfboard-tg-mixed | 0.552 | observe | 197 | 0.472 | 5483 |
| tg-oneclickvpnkeys | 0.445 | observe | 5 | 1.0 | 132 |
| DeltaKronecker-all | 0.383 | observe | 285 | 0.302 | 5643 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3959 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 174 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6410 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.302 | 86 | 199 | 285 |
| Surfboard-tg-mixed | 0.472 | 93 | 104 | 197 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| mheidari-all | 0.829 | 194 | 40 | 234 |
| Au1rxx-base64 | 0.92 | 380 | 33 | 413 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19339 | yes | 4.83 | 0 |
| Epodonios-all | 6410 | yes | 2.3 | 0 |
| SoliSpirit-all | 6188 | yes | 4.29 | 0 |
| DeltaKronecker-all | 5643 | yes | 5.03 | 0 |
| Surfboard-tg-mixed | 5483 | yes | 3.64 | 0 |
| mahdibland-V2RayAggregator | 5017 | yes | 2.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 2.27 | 0 |
| barry-far-vless | 4692 | yes | 2.03 | 0 |
| Surfboard-tg-vless | 4173 | yes | 3.45 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 2.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 184 |
| speed | 91 |
| 204 | 68 |
| cn-block | 39 |
