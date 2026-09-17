# AutoNodes 每日报告

生成时间：2026-09-17 11:31:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86889 |
| 去重后节点数 | 24176 |
| TCP 可达数 | 3000 |
| 真测通过数 | 440 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24176 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 77.1 |
| geo | 1.4 |
| probe | 275.4 |
| real_test | 246.5 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 73 | 46 | 27 | 63.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 165 | 149 | 16 | 90.3% |
| socks | 7 | 5 | 2 | 71.4% |
| trojan | 28 | 14 | 14 | 50.0% |
| vless | 313 | 205 | 108 | 65.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 40 |
| geo:ClientOSError | 27 |
| 204:TimeoutError | 23 |
| speed:TimeoutError | 18 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 13 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:30782: bind: address already in use | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5794 |
| ConnectionRefusedError | 910 |
| gaierror | 330 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.897 | prefer | 275 | 0.833 | 1663 |
| mheidari-all | 0.834 | prefer | 63 | 0.762 | 16008 |
| ermaozi | 0.748 | prefer | 54 | 0.741 | 396 |
| Surfboard-tg-mixed | 0.68 | observe | 143 | 0.601 | 7408 |
| DeltaKronecker-all | 0.668 | observe | 49 | 0.592 | 5931 |
| ermaozi-get_subscribe | 0.365 | observe | 21 | 0.333 | 431 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 129 |
| Epodonios-all | 0.255 | observe | 0 | None | 7867 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8871 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 7 | 14 | 21 |
| DeltaKronecker-all | 0.592 | 29 | 20 | 49 |
| Surfboard-tg-mixed | 0.601 | 86 | 57 | 143 |
| ermaozi | 0.741 | 40 | 14 | 54 |
| mheidari-all | 0.762 | 48 | 15 | 63 |
| Au1rxx-base64 | 0.833 | 229 | 46 | 275 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16008 | yes | 3.71 | 0 |
| SoliSpirit-all | 8871 | yes | 3.99 | 0 |
| Epodonios-all | 7867 | yes | 4.08 | 0 |
| Surfboard-tg-mixed | 7408 | yes | 2.86 | 0 |
| barry-far-vless | 6149 | yes | 2.56 | 0 |
| DeltaKronecker-all | 5931 | yes | 3.76 | 0 |
| Surfboard-tg-vless | 5925 | yes | 2.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 1.96 | 0 |
| mahdibland-V2RayAggregator | 4179 | yes | 0.17 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.02 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 66 |
| geo | 39 |
| speed | 33 |
| cn-block | 30 |
| sing-box exited 1 | 1 |
