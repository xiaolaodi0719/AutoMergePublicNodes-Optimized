# AutoNodes 每日报告

生成时间：2026-07-25 03:20:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 80289 |
| 去重后节点数 | 22839 |
| TCP 可达数 | 3000 |
| 真测通过数 | 731 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22839 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 22.8 |
| geo | 1.4 |
| probe | 70.5 |
| real_test | 197.2 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 32 | 1 | 97.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 16 | 12 | 4 | 75.0% |
| socks | 14 | 10 | 4 | 71.4% |
| trojan | 461 | 438 | 23 | 95.0% |
| vless | 720 | 235 | 485 | 32.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 190 |
| geo:TimeoutError | 165 |
| speed:TimeoutError | 56 |
| geo:ClientOSError | 44 |
| cn-block:TimeoutError | 43 |
| 204:TimeoutError | 7 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4376 |
| ConnectionRefusedError | 697 |
| gaierror | 321 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.945 | prefer | 33 | 0.97 | 61 |
| Surfboard-tg-mixed | 0.765 | prefer | 255 | 0.686 | 5472 |
| mheidari-all | 0.647 | observe | 880 | 0.567 | 19397 |
| DeltaKronecker-all | 0.383 | observe | 74 | 0.297 | 5559 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| tg-ConfigV2rayNG | 0.263 | observe | 1 | 1.0 | 200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6656 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6389 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.297 | 22 | 52 | 74 |
| mheidari-all | 0.567 | 499 | 381 | 880 |
| Surfboard-tg-mixed | 0.686 | 175 | 80 | 255 |
| zhangkai | 0.97 | 32 | 1 | 33 |
| tg-ConfigV2rayNG | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19397 | yes | 4.15 | 0 |
| Epodonios-all | 6656 | yes | 3.19 | 0 |
| SoliSpirit-all | 6389 | yes | 2.83 | 0 |
| DeltaKronecker-all | 5559 | yes | 4.45 | 0 |
| Surfboard-tg-mixed | 5472 | yes | 2.52 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 1.98 | 0 |
| barry-far-vless | 4847 | yes | 1.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.62 | 0 |
| Surfboard-tg-vless | 4180 | yes | 2.69 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 246 |
| geo | 210 |
| cn-block | 46 |
| 204 | 15 |
