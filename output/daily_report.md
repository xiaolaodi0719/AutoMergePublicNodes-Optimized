# AutoNodes 每日报告

生成时间：2026-08-02 13:44:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78289 |
| 去重后节点数 | 22870 |
| TCP 可达数 | 3000 |
| 真测通过数 | 699 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22870 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 39.0 |
| geo | 1.6 |
| probe | 62.8 |
| real_test | 174.2 |
| tcp | 34.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 149 | 118 | 31 | 79.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 28 | 24 | 4 | 85.7% |
| vless | 620 | 389 | 231 | 62.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 116 |
| speed:TimeoutError | 36 |
| cn-block:TimeoutError | 29 |
| 204:TimeoutError | 25 |
| geo:ClientOSError | 18 |
| speed:ClientOSError | 18 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46587: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4587 |
| ConnectionRefusedError | 800 |
| gaierror | 315 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 143 | 1.0 | 344 |
| Au1rxx-base64 | 0.787 | prefer | 555 | 0.721 | 1667 |
| Surfboard-tg-mixed | 0.691 | observe | 124 | 0.613 | 5249 |
| DeltaKronecker-all | 0.64 | observe | 132 | 0.561 | 4549 |
| mheidari-all | 0.446 | observe | 8 | 0.625 | 16891 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |
| Epodonios-all | 0.255 | observe | 0 | None | 5857 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6807 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| roosterkid-openproxylist-v2ray | 0.133 | observe | 1 | 0.0 | 0 | 150 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.561 | 74 | 58 | 132 |
| Surfboard-tg-mixed | 0.613 | 76 | 48 | 124 |
| mheidari-all | 0.625 | 5 | 3 | 8 |
| Au1rxx-base64 | 0.721 | 400 | 155 | 555 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16891 | yes | 5.56 | 0 |
| SoliSpirit-all | 6807 | yes | 3.92 | 0 |
| Epodonios-all | 5857 | yes | 3.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 2.69 | 0 |
| Surfboard-tg-mixed | 5249 | yes | 4.06 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 3.07 | 0 |
| DeltaKronecker-all | 4549 | yes | 5.58 | 0 |
| barry-far-vless | 4517 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 4140 | yes | 4.2 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 2.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 136 |
| speed | 54 |
| cn-block | 41 |
| 204 | 37 |
| sing-box exited 1 | 1 |
