# AutoNodes 每日报告

生成时间：2026-07-27 19:47:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85905 |
| 去重后节点数 | 22931 |
| TCP 可达数 | 3000 |
| 真测通过数 | 771 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22931 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 35.7 |
| geo | 1.4 |
| probe | 65.9 |
| real_test | 182.5 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 59 | 0 | 100.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 140 | 113 | 27 | 80.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 508 | 457 | 51 | 90.0% |
| vless | 292 | 129 | 163 | 44.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 68 |
| speed:ClientOSError | 36 |
| cn-block:TimeoutError | 33 |
| 204:ProxyError | 29 |
| 204:TimeoutError | 29 |
| geo:ClientOSError | 23 |
| speed:TimeoutError | 10 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36196: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4152 |
| ConnectionRefusedError | 764 |
| gaierror | 334 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.995 | prefer | 139 | 0.921 | 19371 |
| zhangkai | 0.987 | prefer | 59 | 1.0 | 74 |
| Au1rxx-base64 | 0.976 | prefer | 448 | 0.917 | 1499 |
| Surfboard-tg-mixed | 0.644 | observe | 37 | 0.568 | 5739 |
| DeltaKronecker-all | 0.537 | observe | 326 | 0.457 | 5643 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3959 |
| tg-Farah_VPN | 0.263 | observe | 1 | 1.0 | 200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6710 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3964 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.457 | 149 | 177 | 326 |
| Surfboard-tg-mixed | 0.568 | 21 | 16 | 37 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.917 | 411 | 37 | 448 |
| mheidari-all | 0.921 | 128 | 11 | 139 |
| tg-Farah_VPN | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 59 | 0 | 59 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19371 | yes | 4.56 | 0 |
| Epodonios-all | 6710 | yes | 2.43 | 0 |
| SoliSpirit-all | 6251 | yes | 3.27 | 0 |
| Surfboard-tg-mixed | 5739 | yes | 3.24 | 0 |
| DeltaKronecker-all | 5643 | yes | 4.55 | 0 |
| barry-far-vless | 5170 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 4997 | yes | 2.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 2.2 | 0 |
| Surfboard-tg-vless | 4648 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3964 | yes | 2.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 94 |
| 204 | 58 |
| speed | 47 |
| cn-block | 43 |
| sing-box exited 1 | 1 |
