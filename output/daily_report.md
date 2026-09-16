# AutoNodes 每日报告

生成时间：2026-09-16 11:22:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 87785 |
| 去重后节点数 | 24305 |
| TCP 可达数 | 3000 |
| 真测通过数 | 440 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24305 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 91.0 |
| geo | 1.4 |
| probe | 228.5 |
| real_test | 240.3 |
| tcp | 40.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 47 | 23 | 67.1% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 135 | 125 | 10 | 92.6% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 24 | 11 | 13 | 45.8% |
| vless | 307 | 235 | 72 | 76.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| 204:ProxyError | 22 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 12 |
| geo:TimeoutError | 10 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:43353: bind: address already in use | 1 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5120 |
| ConnectionRefusedError | 925 |
| gaierror | 467 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.943 | prefer | 49 | 0.878 | 16003 |
| Au1rxx-base64 | 0.926 | prefer | 301 | 0.86 | 1687 |
| ermaozi | 0.736 | prefer | 55 | 0.727 | 407 |
| DeltaKronecker-all | 0.708 | prefer | 16 | 0.75 | 6081 |
| Surfboard-tg-mixed | 0.704 | prefer | 123 | 0.626 | 7446 |
| ermaozi-get_subscribe | 0.445 | observe | 17 | 0.471 | 438 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 8003 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.471 | 8 | 9 | 17 |
| Surfboard-tg-mixed | 0.626 | 77 | 46 | 123 |
| ermaozi | 0.727 | 40 | 15 | 55 |
| DeltaKronecker-all | 0.75 | 12 | 4 | 16 |
| Au1rxx-base64 | 0.86 | 259 | 42 | 301 |
| mheidari-all | 0.878 | 43 | 6 | 49 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16003 | yes | 5.35 | 0 |
| SoliSpirit-all | 9052 | yes | 3.49 | 0 |
| Epodonios-all | 8003 | yes | 6.01 | 0 |
| Surfboard-tg-mixed | 7446 | yes | 4.41 | 0 |
| barry-far-vless | 6340 | yes | 1.49 | 0 |
| DeltaKronecker-all | 6081 | yes | 4.95 | 0 |
| Surfboard-tg-vless | 6044 | yes | 3.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 1.71 | 0 |
| mahdibland-V2RayAggregator | 4206 | yes | 3.22 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.79 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 47 |
| geo | 31 |
| cn-block | 25 |
| speed | 19 |
| sing-box exited 1 | 1 |
