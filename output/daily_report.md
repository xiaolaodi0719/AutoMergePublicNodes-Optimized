# AutoNodes 每日报告

生成时间：2026-08-22 12:53:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 92293 |
| 去重后节点数 | 23763 |
| TCP 可达数 | 3000 |
| 真测通过数 | 798 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23763 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 40.0 |
| geo | 1.4 |
| probe | 60.9 |
| real_test | 158.6 |
| tcp | 38.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 186 | 167 | 19 | 89.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 172 | 167 | 5 | 97.1% |
| vless | 448 | 330 | 118 | 73.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 44 |
| geo:TimeoutError | 21 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 18 |
| speed:TimeoutError | 12 |
| cn-block:ClientOSError | 11 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5044 |
| ConnectionRefusedError | 947 |
| gaierror | 786 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| Au1rxx-base64 | 0.993 | prefer | 499 | 0.928 | 1674 |
| Surfboard-tg-mixed | 0.886 | prefer | 168 | 0.81 | 6287 |
| mheidari-all | 0.615 | observe | 153 | 0.536 | 21719 |
| 10ium-HighSpeed | 0.345 | observe | 2 | 1.0 | 839 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3321 |
| DeltaKronecker-all | 0.284 | observe | 6 | 0.333 | 5015 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 161 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6868 |

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
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 2 | 4 | 6 |
| mheidari-all | 0.536 | 82 | 71 | 153 |
| Surfboard-tg-mixed | 0.81 | 136 | 32 | 168 |
| Au1rxx-base64 | 0.928 | 463 | 36 | 499 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21719 | yes | 5.19 | 0 |
| SoliSpirit-all | 6876 | yes | 2.68 | 0 |
| Epodonios-all | 6868 | yes | 4.36 | 0 |
| Surfboard-tg-mixed | 6287 | yes | 3.54 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.41 | 0 |
| barry-far-vless | 5403 | yes | 0.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 3.48 | 0 |
| Surfboard-tg-vless | 5093 | yes | 3.23 | 0 |
| DeltaKronecker-all | 5015 | yes | 3.64 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 0.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 65 |
| cn-block | 33 |
| 204 | 25 |
| speed | 22 |
