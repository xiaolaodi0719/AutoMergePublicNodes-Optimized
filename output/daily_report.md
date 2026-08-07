# AutoNodes 每日报告

生成时间：2026-08-07 07:28:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89705 |
| 去重后节点数 | 24235 |
| TCP 可达数 | 3000 |
| 真测通过数 | 482 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24235 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 44.0 |
| geo | 1.2 |
| probe | 50.3 |
| real_test | 94.3 |
| tcp | 35.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 176 | 162 | 14 | 92.0% |
| socks | 11 | 7 | 4 | 63.6% |
| trojan | 162 | 152 | 10 | 93.8% |
| vless | 209 | 120 | 89 | 57.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 40 |
| geo:ClientOSError | 25 |
| 204:TimeoutError | 19 |
| speed:ClientOSError | 10 |
| cn-block:TimeoutError | 9 |
| 204:ProxyError | 8 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4920 |
| ConnectionRefusedError | 824 |
| gaierror | 335 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.986 | prefer | 389 | 0.936 | 1300 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| mheidari-all | 0.623 | observe | 33 | 0.545 | 20715 |
| DeltaKronecker-all | 0.613 | observe | 28 | 0.536 | 5326 |
| Surfboard-tg-mixed | 0.572 | observe | 128 | 0.492 | 6241 |
| nscl5-all | 0.326 | observe | 1 | 1.0 | 1772 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 5184 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5282 |
| Epodonios-all | 0.255 | observe | 0 | None | 6873 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.492 | 63 | 65 | 128 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.536 | 15 | 13 | 28 |
| mheidari-all | 0.545 | 18 | 15 | 33 |
| Au1rxx-base64 | 0.936 | 364 | 25 | 389 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20715 | yes | 4.7 | 0 |
| SoliSpirit-all | 7440 | yes | 4.47 | 0 |
| Epodonios-all | 6873 | yes | 4.88 | 0 |
| Surfboard-tg-mixed | 6241 | yes | 3.46 | 0 |
| DeltaKronecker-all | 5326 | yes | 5.45 | 0 |
| barry-far-vless | 5297 | yes | 2.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 2.46 | 0 |
| mahdibland-V2RayAggregator | 5247 | yes | 2.68 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 4967 | yes | 2.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 65 |
| 204 | 28 |
| speed | 14 |
| cn-block | 12 |
