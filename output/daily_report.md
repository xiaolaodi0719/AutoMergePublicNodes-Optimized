# AutoNodes 每日报告

生成时间：2026-07-24 14:00:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82875 |
| 去重后节点数 | 22678 |
| TCP 可达数 | 3000 |
| 真测通过数 | 666 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22678 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 40.2 |
| geo | 1.3 |
| probe | 60.0 |
| real_test | 148.8 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 35 | 1 | 97.2% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 16 | 13 | 3 | 81.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 541 | 496 | 45 | 91.7% |
| vless | 297 | 116 | 181 | 39.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 72 |
| speed:ClientOSError | 42 |
| 204:ProxyError | 26 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 19 |
| geo:ClientOSError | 16 |
| cn-block:ProxyError | 10 |
| speed:TimeoutError | 10 |
| geo:ProxyError | 7 |
| speed:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4159 |
| ConnectionRefusedError | 695 |
| gaierror | 421 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.95 | prefer | 36 | 0.972 | 61 |
| DeltaKronecker-all | 0.853 | prefer | 148 | 0.777 | 5559 |
| mheidari-all | 0.808 | prefer | 655 | 0.728 | 19570 |
| Surfboard-tg-mixed | 0.703 | prefer | 51 | 0.627 | 5218 |
| Au1rxx-base64 | 0.457 | observe | 5 | 1.0 | 432 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3847 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6424 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3975 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.627 | 32 | 19 | 51 |
| mheidari-all | 0.728 | 477 | 178 | 655 |
| DeltaKronecker-all | 0.777 | 115 | 33 | 148 |
| zhangkai | 0.972 | 35 | 1 | 36 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19570 | yes | 3.58 | 0 |
| SoliSpirit-all | 6965 | yes | 1.8 | 0 |
| Epodonios-all | 6424 | yes | 1.43 | 0 |
| DeltaKronecker-all | 5559 | yes | 3.45 | 0 |
| Surfboard-tg-mixed | 5218 | yes | 1.9 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 1.67 | 0 |
| barry-far-vless | 4809 | yes | 1.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 4143 | yes | 2.02 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 1.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 95 |
| speed | 57 |
| 204 | 48 |
| cn-block | 32 |
