# AutoNodes 每日报告

生成时间：2026-08-11 02:07:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85365 |
| 去重后节点数 | 24751 |
| TCP 可达数 | 3000 |
| 真测通过数 | 541 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24751 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 27.5 |
| geo | 1.2 |
| probe | 47.5 |
| real_test | 100.8 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 49 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 168 | 161 | 7 | 95.8% |
| socks | 9 | 8 | 1 | 88.9% |
| trojan | 150 | 127 | 23 | 84.7% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 329 | 176 | 153 | 53.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 62 |
| speed:TimeoutError | 37 |
| geo:ClientOSError | 33 |
| speed:ClientOSError | 24 |
| 204:ProxyError | 7 |
| cn-block:TimeoutError | 7 |
| 204:TimeoutError | 6 |
| speed:ProxyError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4745 |
| ConnectionRefusedError | 842 |
| gaierror | 295 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | prefer | 49 | 1.0 | 67 |
| Au1rxx-base64 | 0.94 | prefer | 402 | 0.883 | 1463 |
| Surfboard-tg-mixed | 0.812 | prefer | 136 | 0.735 | 6329 |
| DeltaKronecker-all | 0.374 | observe | 83 | 0.289 | 5881 |
| mheidari-all | 0.316 | observe | 53 | 0.226 | 20211 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 6946 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7525 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.226 | 12 | 41 | 53 |
| DeltaKronecker-all | 0.289 | 24 | 59 | 83 |
| Surfboard-tg-mixed | 0.735 | 100 | 36 | 136 |
| Au1rxx-base64 | 0.883 | 355 | 47 | 402 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 49 | 0 | 49 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20211 | yes | 4.92 | 0 |
| SoliSpirit-all | 7525 | yes | 2.41 | 0 |
| Epodonios-all | 6946 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 6329 | yes | 4.12 | 0 |
| DeltaKronecker-all | 5881 | yes | 4.08 | 0 |
| barry-far-vless | 5506 | yes | 1.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.62 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 2.58 | 0 |
| Surfboard-tg-vless | 5163 | yes | 2.5 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 95 |
| speed | 65 |
| 204 | 15 |
| cn-block | 10 |
