# AutoNodes 每日报告

生成时间：2026-08-22 06:53:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 91263 |
| 去重后节点数 | 23609 |
| TCP 可达数 | 3000 |
| 真测通过数 | 777 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23609 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 37.3 |
| geo | 1.4 |
| probe | 58.7 |
| real_test | 161.6 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 111 | 1 | 99.1% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 213 | 195 | 18 | 91.5% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 206 | 189 | 17 | 91.7% |
| vless | 393 | 260 | 133 | 66.2% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 66 |
| geo:ClientOSError | 26 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48458: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5242 |
| ConnectionRefusedError | 928 |
| gaierror | 694 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.988 | prefer | 112 | 0.991 | 144 |
| Au1rxx-base64 | 0.97 | prefer | 447 | 0.919 | 1299 |
| Surfboard-tg-mixed | 0.881 | prefer | 174 | 0.805 | 6140 |
| mheidari-all | 0.69 | observe | 152 | 0.612 | 21732 |
| DeltaKronecker-all | 0.43 | observe | 58 | 0.345 | 5015 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3321 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 151 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6729 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3992 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.345 | 20 | 38 | 58 |
| mheidari-all | 0.612 | 93 | 59 | 152 |
| Surfboard-tg-mixed | 0.805 | 140 | 34 | 174 |
| Au1rxx-base64 | 0.919 | 411 | 36 | 447 |
| zhangkai | 0.991 | 111 | 1 | 112 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21732 | yes | 4.24 | 0 |
| SoliSpirit-all | 7142 | yes | 2.58 | 0 |
| Epodonios-all | 6729 | yes | 4.48 | 0 |
| Surfboard-tg-mixed | 6140 | yes | 3.08 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.31 | 0 |
| barry-far-vless | 5261 | yes | 1.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 0.78 | 0 |
| DeltaKronecker-all | 5015 | yes | 5.25 | 0 |
| Surfboard-tg-vless | 4954 | yes | 2.62 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 2.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 92 |
| 204 | 28 |
| speed | 27 |
| cn-block | 23 |
| sing-box exited 1 | 1 |
