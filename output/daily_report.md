# AutoNodes 每日报告

生成时间：2026-09-20 04:35:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 87371 |
| 去重后节点数 | 25384 |
| TCP 可达数 | 3000 |
| 真测通过数 | 706 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25384 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 94.0 |
| geo | 1.7 |
| probe | 289.1 |
| real_test | 513.2 |
| tcp | 41.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 58 | 41 | 17 | 70.7% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 186 | 178 | 8 | 95.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 17 | 13 | 4 | 76.5% |
| vless | 919 | 455 | 464 | 49.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 215 |
| geo:ClientOSError | 95 |
| speed:TimeoutError | 66 |
| speed:ClientOSError | 48 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 13 |
| 204:TimeoutError | 6 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40344: bind: address already in use | 1 |
| 204:ServerDisconnectedError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5285 |
| ConnectionRefusedError | 933 |
| gaierror | 543 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 340 | 0.894 | 1654 |
| ermaozi | 0.713 | prefer | 51 | 0.706 | 365 |
| Surfboard-tg-mixed | 0.601 | observe | 140 | 0.521 | 7138 |
| DeltaKronecker-all | 0.528 | observe | 531 | 0.448 | 6421 |
| mheidari-all | 0.462 | observe | 121 | 0.38 | 15978 |
| ermaozi-get_subscribe | 0.337 | observe | 7 | 0.571 | 394 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5174 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| xiaoji235-airport-v2ray-all | 0.272 | observe | 7 | 0.286 | 3625 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.38 | 46 | 75 | 121 |
| DeltaKronecker-all | 0.448 | 238 | 293 | 531 |
| Surfboard-tg-mixed | 0.521 | 73 | 67 | 140 |
| ermaozi-get_subscribe | 0.571 | 4 | 3 | 7 |
| ermaozi | 0.706 | 36 | 15 | 51 |
| Au1rxx-base64 | 0.894 | 304 | 36 | 340 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15978 | yes | 6.74 | 0 |
| SoliSpirit-all | 8830 | yes | 2.02 | 0 |
| Epodonios-all | 7601 | yes | 3.64 | 0 |
| Surfboard-tg-mixed | 7138 | yes | 3.9 | 0 |
| DeltaKronecker-all | 6421 | yes | 3.03 | 0 |
| barry-far-vless | 5908 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 5693 | yes | 4.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 3.18 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 310 |
| speed | 114 |
| 204 | 39 |
| cn-block | 31 |
| sing-box exited 1 | 1 |
