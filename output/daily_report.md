# AutoNodes 每日报告

生成时间：2026-08-21 07:01:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94141 |
| 去重后节点数 | 24585 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1172 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24585 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 45.0 |
| geo | 0.9 |
| probe | 69.8 |
| real_test | 207.1 |
| tcp | 38.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 192 | 178 | 14 | 92.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 642 | 631 | 11 | 98.3% |
| vless | 345 | 226 | 119 | 65.5% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 45 |
| speed:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 19 |
| 204:TimeoutError | 15 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4767 |
| ConnectionRefusedError | 930 |
| gaierror | 578 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 641 | 0.958 | 1607 |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| mheidari-all | 0.922 | prefer | 295 | 0.844 | 21864 |
| Surfboard-tg-mixed | 0.855 | prefer | 242 | 0.777 | 6368 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| DeltaKronecker-all | 0.366 | observe | 26 | 0.269 | 6250 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5148 |
| Epodonios-all | 0.255 | observe | 0 | None | 7077 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

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
| DeltaKronecker-all | 0.269 | 7 | 19 | 26 |
| Surfboard-tg-mixed | 0.777 | 188 | 54 | 242 |
| mheidari-all | 0.844 | 249 | 46 | 295 |
| Au1rxx-base64 | 0.958 | 614 | 27 | 641 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21864 | yes | 5.26 | 0 |
| Epodonios-all | 7077 | yes | 4.66 | 0 |
| SoliSpirit-all | 7024 | yes | 4.81 | 0 |
| Surfboard-tg-mixed | 6368 | yes | 3.49 | 0 |
| DeltaKronecker-all | 6250 | yes | 5.3 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.97 | 0 |
| barry-far-vless | 5415 | yes | 1.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 2.99 | 0 |
| Surfboard-tg-vless | 5051 | yes | 3.23 | 0 |
| mahdibland-V2RayAggregator | 4647 | yes | 2.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 65 |
| speed | 31 |
| cn-block | 26 |
| 204 | 25 |
