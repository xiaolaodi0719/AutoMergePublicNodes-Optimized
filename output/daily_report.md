# AutoNodes 每日报告

生成时间：2026-08-26 07:01:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77824 |
| 去重后节点数 | 22072 |
| TCP 可达数 | 3000 |
| 真测通过数 | 592 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22072 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 38.6 |
| geo | 1.4 |
| probe | 56.5 |
| real_test | 139.9 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 25 | 24 | 1 | 96.0% |
| shadowsocks | 180 | 165 | 15 | 91.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 57 | 48 | 9 | 84.2% |
| vless | 510 | 328 | 182 | 64.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 56 |
| geo:TimeoutError | 54 |
| cn-block:TimeoutError | 24 |
| geo:ClientOSError | 20 |
| speed:ClientOSError | 17 |
| 204:TimeoutError | 15 |
| cn-block:ClientOSError | 10 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4618 |
| ConnectionRefusedError | 856 |
| gaierror | 392 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| Au1rxx-base64 | 0.905 | prefer | 377 | 0.828 | 1986 |
| Surfboard-tg-mixed | 0.757 | prefer | 165 | 0.679 | 6380 |
| DeltaKronecker-all | 0.7 | prefer | 98 | 0.622 | 6107 |
| mheidari-all | 0.691 | observe | 124 | 0.613 | 14091 |
| nscl5-all | 0.402 | observe | 5 | 0.8 | 887 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4825 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 206 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1990 |
| Epodonios-all | 0.255 | observe | 0 | None | 6845 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.613 | 76 | 48 | 124 |
| DeltaKronecker-all | 0.622 | 61 | 37 | 98 |
| Surfboard-tg-mixed | 0.679 | 112 | 53 | 165 |
| nscl5-all | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.828 | 312 | 65 | 377 |
| zhangkai | 0.958 | 23 | 1 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14091 | yes | 5.15 | 0 |
| SoliSpirit-all | 6976 | yes | 4.42 | 0 |
| Epodonios-all | 6845 | yes | 5.33 | 0 |
| Surfboard-tg-mixed | 6380 | yes | 4.05 | 0 |
| DeltaKronecker-all | 6107 | yes | 5.43 | 0 |
| barry-far-vless | 5518 | yes | 3.86 | 0 |
| Surfboard-tg-vless | 5270 | yes | 4.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 3.57 | 0 |
| MatinGhanbari-all-sub | 3990 | yes | 4.49 | 0 |
| mahdibland-V2RayAggregator | 3981 | yes | 3.6 | 0 |

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
| geo | 75 |
| speed | 73 |
| cn-block | 35 |
| 204 | 27 |
