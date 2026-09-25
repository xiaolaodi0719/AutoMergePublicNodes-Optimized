# AutoNodes 每日报告

生成时间：2026-09-25 04:36:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97835 |
| 去重后节点数 | 26568 |
| TCP 可达数 | 3000 |
| 真测通过数 | 496 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26568 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 86.2 |
| geo | 1.4 |
| probe | 361.6 |
| real_test | 531.8 |
| tcp | 43.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 31 | 19 | 12 | 61.3% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 184 | 173 | 11 | 94.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 26 | 11 | 15 | 42.3% |
| vless | 723 | 269 | 454 | 37.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 183 |
| speed:TimeoutError | 98 |
| geo:ClientOSError | 47 |
| speed:ClientOSError | 45 |
| cn-block:ClientOSError | 42 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 19 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| speed:ClientPayloadError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48396: bind: address already in use | 1 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6340 |
| ConnectionRefusedError | 960 |
| gaierror | 320 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | prefer | 270 | 0.907 | 1702 |
| Surfboard-tg-mixed | 0.859 | prefer | 75 | 0.787 | 7399 |
| ermaozi | 0.621 | observe | 26 | 0.615 | 338 |
| ermaozi-get_subscribe | 0.399 | observe | 7 | 0.714 | 359 |
| mheidari-all | 0.359 | observe | 601 | 0.278 | 22554 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| DeltaKronecker-all | 0.324 | observe | 8 | 0.375 | 5845 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7876 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.278 | 167 | 434 | 601 |
| DeltaKronecker-all | 0.375 | 3 | 5 | 8 |
| ermaozi | 0.615 | 16 | 10 | 26 |
| ermaozi-get_subscribe | 0.714 | 5 | 2 | 7 |
| Surfboard-tg-mixed | 0.787 | 59 | 16 | 75 |
| Au1rxx-base64 | 0.907 | 245 | 25 | 270 |
| ninja-vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22554 | yes | 4.32 | 0 |
| SoliSpirit-all | 9018 | yes | 3.23 | 0 |
| Epodonios-all | 7876 | yes | 2.58 | 0 |
| Surfboard-tg-mixed | 7399 | yes | 3.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.38 | 0 |
| barry-far-vless | 6091 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 5862 | yes | 3.84 | 0 |
| DeltaKronecker-all | 5845 | yes | 4.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.89 | 0 |
| mahdibland-V2RayAggregator | 4405 | yes | 2.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 231 |
| speed | 145 |
| cn-block | 68 |
| 204 | 49 |
| sing-box exited 1 | 1 |
