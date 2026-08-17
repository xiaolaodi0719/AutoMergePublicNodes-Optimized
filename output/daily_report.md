# AutoNodes 每日报告

生成时间：2026-08-17 01:44:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 80829 |
| 去重后节点数 | 22248 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1313 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22248 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 28.0 |
| geo | 1.3 |
| probe | 70.6 |
| real_test | 240.9 |
| tcp | 33.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 27 | 22 | 5 | 81.5% |
| shadowsocks | 136 | 130 | 6 | 95.6% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 689 | 679 | 10 | 98.5% |
| vless | 590 | 350 | 240 | 59.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 103 |
| speed:TimeoutError | 44 |
| cn-block:TimeoutError | 37 |
| geo:ClientOSError | 31 |
| speed:ClientOSError | 16 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4361 |
| ConnectionRefusedError | 810 |
| gaierror | 235 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 913 | 0.962 | 1994 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.837 | prefer | 150 | 0.76 | 5916 |
| mheidari-all | 0.671 | observe | 311 | 0.592 | 17074 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 129 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 6595 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.198 | 66 | 0.106 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.106 | 7 | 59 | 66 |
| mheidari-all | 0.592 | 184 | 127 | 311 |
| Surfboard-tg-mixed | 0.76 | 114 | 36 | 150 |
| Au1rxx-base64 | 0.962 | 878 | 35 | 913 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17074 | yes | 4.67 | 0 |
| SoliSpirit-all | 7537 | yes | 4.16 | 0 |
| Epodonios-all | 6595 | yes | 4.92 | 0 |
| Surfboard-tg-mixed | 5916 | yes | 3.54 | 0 |
| DeltaKronecker-all | 5092 | yes | 5.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 3.19 | 0 |
| barry-far-vless | 4905 | yes | 2.92 | 0 |
| Surfboard-tg-vless | 4572 | yes | 3.7 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 1.66 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.75 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 134 |
| speed | 61 |
| cn-block | 44 |
| 204 | 22 |
