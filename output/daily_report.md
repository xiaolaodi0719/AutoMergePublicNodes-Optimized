# AutoNodes 每日报告

生成时间：2026-08-20 01:38:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91151 |
| 去重后节点数 | 23539 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1307 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23539 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 27.7 |
| geo | 0.7 |
| probe | 73.3 |
| real_test | 229.0 |
| tcp | 37.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 177 | 169 | 8 | 95.5% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 733 | 715 | 18 | 97.5% |
| vless | 429 | 286 | 143 | 66.7% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 59 |
| speed:TimeoutError | 34 |
| geo:ClientOSError | 33 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:31350: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4586 |
| ConnectionRefusedError | 987 |
| gaierror | 579 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 731 | 0.977 | 1789 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.848 | prefer | 291 | 0.77 | 6430 |
| mheidari-all | 0.839 | prefer | 334 | 0.76 | 20672 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5974 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7184 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |

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
| DeltaKronecker-all | 0.16 | observe | 4 | 0.0 | 0 | 4713 |
| nscl5-all | 0.17 | observe | 3 | 0.0 | 0 | 2418 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.76 | 254 | 80 | 334 |
| Surfboard-tg-mixed | 0.77 | 224 | 67 | 291 |
| Au1rxx-base64 | 0.977 | 714 | 17 | 731 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20672 | yes | 5.06 | 0 |
| SoliSpirit-all | 7353 | yes | 4.14 | 0 |
| Epodonios-all | 7184 | yes | 5.26 | 0 |
| Surfboard-tg-mixed | 6430 | yes | 3.52 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.5 | 0 |
| barry-far-vless | 5381 | yes | 0.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 3.07 | 0 |
| Surfboard-tg-vless | 5059 | yes | 3.13 | 0 |
| DeltaKronecker-all | 4713 | yes | 5.69 | 0 |
| mahdibland-V2RayAggregator | 4086 | yes | 2.82 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 93 |
| speed | 48 |
| cn-block | 20 |
| 204 | 11 |
| sing-box exited 1 | 1 |
