# AutoNodes 每日报告

生成时间：2026-08-20 13:03:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94317 |
| 去重后节点数 | 25201 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1067 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25201 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| generate | 23.3 |
| geo | 0.6 |
| probe | 67.7 |
| real_test | 212.7 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 88 | 84 | 4 | 95.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 592 | 586 | 6 | 99.0% |
| vless | 385 | 272 | 113 | 70.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 47 |
| geo:TimeoutError | 16 |
| 204:TimeoutError | 14 |
| speed:TimeoutError | 12 |
| 204:ClientOSError | 10 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 6 |
| 204:ProxyError | 5 |
| cn-block:TimeoutError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5274 |
| ConnectionRefusedError | 942 |
| gaierror | 555 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 569 | 0.975 | 1789 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| mheidari-all | 0.871 | prefer | 495 | 0.792 | 21209 |
| Surfboard-tg-mixed | 0.515 | observe | 11 | 0.636 | 6453 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7150 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7279 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5135 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.636 | 7 | 4 | 11 |
| mheidari-all | 0.792 | 392 | 103 | 495 |
| Au1rxx-base64 | 0.975 | 555 | 14 | 569 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21209 | yes | 5.1 | 0 |
| SoliSpirit-all | 7279 | yes | 2.77 | 0 |
| Epodonios-all | 7150 | yes | 5.37 | 0 |
| DeltaKronecker-all | 6781 | yes | 4.91 | 0 |
| Surfboard-tg-mixed | 6453 | yes | 4.28 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.2 | 0 |
| barry-far-vless | 5460 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5135 | yes | 5.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 3.01 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 63 |
| 204 | 29 |
| speed | 18 |
| cn-block | 14 |
