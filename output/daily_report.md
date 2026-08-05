# AutoNodes 每日报告

生成时间：2026-08-05 14:24:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 87256 |
| 去重后节点数 | 24192 |
| TCP 可达数 | 3000 |
| 真测通过数 | 512 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24192 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 31.4 |
| geo | 0.8 |
| probe | 49.0 |
| real_test | 111.5 |
| tcp | 36.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 150 | 140 | 10 | 93.3% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 159 | 154 | 5 | 96.9% |
| vless | 270 | 176 | 94 | 65.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 37 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 10 |
| 204:TimeoutError | 10 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 2 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5063 |
| ConnectionRefusedError | 819 |
| gaierror | 242 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.991 | prefer | 418 | 0.931 | 1552 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.683 | observe | 144 | 0.604 | 5862 |
| mheidari-all | 0.542 | observe | 24 | 0.458 | 20132 |
| DeltaKronecker-all | 0.326 | observe | 15 | 0.267 | 5316 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 4655 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6386 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7443 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.267 | 4 | 11 | 15 |
| mheidari-all | 0.458 | 11 | 13 | 24 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.604 | 87 | 57 | 144 |
| Au1rxx-base64 | 0.931 | 389 | 29 | 418 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20132 | yes | 4.81 | 0 |
| SoliSpirit-all | 7443 | yes | 2.12 | 0 |
| Epodonios-all | 6386 | yes | 2.55 | 0 |
| Surfboard-tg-mixed | 5862 | yes | 2.88 | 0 |
| DeltaKronecker-all | 5316 | yes | 4.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 0.94 | 0 |
| mahdibland-V2RayAggregator | 5147 | yes | 2.25 | 0 |
| barry-far-vless | 4943 | yes | 1.88 | 0 |
| Surfboard-tg-vless | 4686 | yes | 3.77 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 1.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 49 |
| 204 | 31 |
| cn-block | 18 |
| speed | 15 |
