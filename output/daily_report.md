# AutoNodes 每日报告

生成时间：2026-08-17 07:11:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82922 |
| 去重后节点数 | 23092 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1377 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23092 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 43.7 |
| geo | 0.8 |
| probe | 74.9 |
| real_test | 241.4 |
| tcp | 34.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 146 | 130 | 16 | 89.0% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 785 | 776 | 9 | 98.9% |
| vless | 430 | 314 | 116 | 73.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 37 |
| cn-block:TimeoutError | 21 |
| speed:TimeoutError | 20 |
| 204:TimeoutError | 16 |
| 204:ProxyError | 14 |
| geo:ClientOSError | 13 |
| speed:ClientOSError | 11 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4205 |
| ConnectionRefusedError | 818 |
| gaierror | 379 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 876 | 0.952 | 1991 |
| mheidari-all | 1.0 | prefer | 265 | 0.947 | 17400 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.792 | prefer | 217 | 0.714 | 5925 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3043 |
| DeltaKronecker-all | 0.306 | observe | 29 | 0.207 | 6368 |
| ninja-vless | 0.279 | observe | 2 | 0.5 | 1791 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 164 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5085 |

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
| DeltaKronecker-all | 0.207 | 6 | 23 | 29 |
| ninja-vless | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.714 | 155 | 62 | 217 |
| mheidari-all | 0.947 | 251 | 14 | 265 |
| Au1rxx-base64 | 0.952 | 834 | 42 | 876 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17400 | yes | 4.91 | 0 |
| SoliSpirit-all | 7808 | yes | 3.06 | 0 |
| Epodonios-all | 6602 | yes | 4.13 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.08 | 0 |
| Surfboard-tg-mixed | 5925 | yes | 3.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 2.52 | 0 |
| barry-far-vless | 4931 | yes | 2.79 | 0 |
| Surfboard-tg-vless | 4592 | yes | 3.22 | 0 |
| mahdibland-V2RayAggregator | 4046 | yes | 1.39 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 50 |
| 204 | 33 |
| speed | 31 |
| cn-block | 28 |
