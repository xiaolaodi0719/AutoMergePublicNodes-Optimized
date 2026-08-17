# AutoNodes 每日报告

生成时间：2026-08-17 12:59:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83030 |
| 去重后节点数 | 23200 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1260 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23200 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 38.0 |
| geo | 1.0 |
| probe | 83.5 |
| real_test | 237.4 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 25 | 21 | 4 | 84.0% |
| shadowsocks | 137 | 125 | 12 | 91.2% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 773 | 768 | 5 | 99.4% |
| vless | 298 | 212 | 86 | 71.1% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 21 |
| speed:TimeoutError | 16 |
| geo:TimeoutError | 13 |
| geo:ClientOSError | 10 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4450 |
| ConnectionRefusedError | 842 |
| gaierror | 322 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 883 | 0.942 | 1983 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.948 | prefer | 279 | 0.871 | 17057 |
| Surfboard-tg-mixed | 0.874 | prefer | 66 | 0.803 | 6086 |
| DeltaKronecker-all | 0.337 | observe | 13 | 0.308 | 6368 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5085 |
| Epodonios-all | 0.255 | observe | 0 | None | 6645 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7827 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.308 | 4 | 9 | 13 |
| Surfboard-tg-mixed | 0.803 | 53 | 13 | 66 |
| mheidari-all | 0.871 | 243 | 36 | 279 |
| Au1rxx-base64 | 0.942 | 832 | 51 | 883 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17057 | yes | 5.08 | 0 |
| SoliSpirit-all | 7827 | yes | 2.34 | 0 |
| Epodonios-all | 6645 | yes | 5.24 | 0 |
| DeltaKronecker-all | 6368 | yes | 3.19 | 0 |
| Surfboard-tg-mixed | 6086 | yes | 4.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 2.6 | 0 |
| barry-far-vless | 4992 | yes | 1.8 | 0 |
| Surfboard-tg-vless | 4669 | yes | 3.31 | 0 |
| mahdibland-V2RayAggregator | 4046 | yes | 1.42 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 2.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| cn-block | 25 |
| speed | 25 |
| geo | 24 |
