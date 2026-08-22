# AutoNodes 每日报告

生成时间：2026-08-22 18:42:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86103 |
| 去重后节点数 | 23834 |
| TCP 可达数 | 3000 |
| 真测通过数 | 700 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23834 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 44.0 |
| geo | 1.5 |
| probe | 62.4 |
| real_test | 154.4 |
| tcp | 40.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 151 | 139 | 12 | 92.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 167 | 159 | 8 | 95.2% |
| vless | 353 | 269 | 84 | 76.2% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 30 |
| 204:TimeoutError | 21 |
| geo:TimeoutError | 20 |
| speed:TimeoutError | 10 |
| speed:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5233 |
| ConnectionRefusedError | 1011 |
| gaierror | 651 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| Au1rxx-base64 | 0.988 | prefer | 485 | 0.915 | 1853 |
| mheidari-all | 0.853 | prefer | 73 | 0.781 | 14443 |
| Surfboard-tg-mixed | 0.747 | prefer | 124 | 0.669 | 6394 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5974 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 176 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| DeltaKronecker-all | 0.255 | observe | 9 | 0.222 | 5015 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6972 |

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
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.222 | 2 | 7 | 9 |
| Surfboard-tg-mixed | 0.669 | 83 | 41 | 124 |
| mheidari-all | 0.781 | 57 | 16 | 73 |
| Au1rxx-base64 | 0.915 | 444 | 41 | 485 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14443 | yes | 6.56 | 0 |
| SoliSpirit-all | 7145 | yes | 4.15 | 0 |
| Epodonios-all | 6972 | yes | 6.92 | 0 |
| Surfboard-tg-mixed | 6394 | yes | 3.96 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 3.62 | 0 |
| barry-far-vless | 5527 | yes | 4.2 | 0 |
| Surfboard-tg-vless | 5216 | yes | 3.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 3.39 | 0 |
| DeltaKronecker-all | 5015 | yes | 5.16 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 0.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 35 |
| 204 | 29 |
| geo | 26 |
| speed | 17 |
