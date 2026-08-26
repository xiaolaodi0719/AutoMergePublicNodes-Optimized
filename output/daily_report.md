# AutoNodes 每日报告

生成时间：2026-08-26 01:46:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79196 |
| 去重后节点数 | 22564 |
| TCP 可达数 | 3000 |
| 真测通过数 | 753 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22564 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 42.1 |
| geo | 1.5 |
| probe | 74.6 |
| real_test | 219.2 |
| tcp | 36.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 28 | 27 | 1 | 96.4% |
| shadowsocks | 103 | 98 | 5 | 95.1% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 73 | 50 | 23 | 68.5% |
| vless | 1182 | 549 | 633 | 46.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 362 |
| speed:ClientOSError | 121 |
| geo:ClientOSError | 81 |
| speed:TimeoutError | 37 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4832 |
| ConnectionRefusedError | 873 |
| gaierror | 342 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 475 | 0.895 | 1944 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| Surfboard-tg-mixed | 0.92 | prefer | 23 | 0.87 | 6470 |
| mheidari-all | 0.523 | observe | 15 | 0.533 | 14587 |
| DeltaKronecker-all | 0.395 | observe | 875 | 0.314 | 6340 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 191 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 7017 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7048 |

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
| nscl5-all | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.314 | 275 | 600 | 875 |
| mheidari-all | 0.533 | 8 | 7 | 15 |
| Surfboard-tg-mixed | 0.87 | 20 | 3 | 23 |
| Au1rxx-base64 | 0.895 | 425 | 50 | 475 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14587 | yes | 5.22 | 0 |
| SoliSpirit-all | 7048 | yes | 4.0 | 0 |
| Epodonios-all | 7017 | yes | 3.42 | 0 |
| Surfboard-tg-mixed | 6470 | yes | 4.52 | 0 |
| DeltaKronecker-all | 6340 | yes | 4.98 | 0 |
| barry-far-vless | 5579 | yes | 3.15 | 0 |
| Surfboard-tg-vless | 5307 | yes | 3.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 3.37 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 0.93 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 3.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 443 |
| speed | 159 |
| cn-block | 34 |
| 204 | 29 |
