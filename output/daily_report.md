# AutoNodes 每日报告

生成时间：2026-09-12 15:28:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83067 |
| 去重后节点数 | 22816 |
| TCP 可达数 | 3000 |
| 真测通过数 | 428 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22816 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.9 |
| generate | 76.5 |
| geo | 1.4 |
| probe | 201.8 |
| real_test | 228.0 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 43 | 25 | 18 | 58.1% |
| hysteria2 | 21 | 16 | 5 | 76.2% |
| shadowsocks | 158 | 141 | 17 | 89.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 16 | 13 | 3 | 81.2% |
| vless | 353 | 231 | 122 | 65.4% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 63 |
| 204:TimeoutError | 17 |
| cn-block:ClientOSError | 15 |
| speed:ClientOSError | 14 |
| cn-block:TimeoutError | 14 |
| 204:ProxyError | 13 |
| 204:ProxyConnectionError | 12 |
| 204:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46410: bind: address already in use | 1 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5104 |
| ConnectionRefusedError | 876 |
| gaierror | 511 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.928 | prefer | 297 | 0.872 | 1455 |
| Surfboard-tg-mixed | 0.718 | prefer | 114 | 0.64 | 7345 |
| mheidari-all | 0.619 | observe | 74 | 0.541 | 15620 |
| ermaozi | 0.556 | observe | 35 | 0.543 | 393 |
| DeltaKronecker-all | 0.543 | observe | 65 | 0.462 | 5970 |
| ermaozi-get_subscribe | 0.465 | observe | 7 | 0.857 | 408 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7743 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.462 | 30 | 35 | 65 |
| mheidari-all | 0.541 | 40 | 34 | 74 |
| ermaozi | 0.543 | 19 | 16 | 35 |
| Surfboard-tg-mixed | 0.64 | 73 | 41 | 114 |
| ermaozi-get_subscribe | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.872 | 259 | 38 | 297 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15620 | yes | 4.4 | 0 |
| SoliSpirit-all | 8959 | yes | 2.93 | 0 |
| Epodonios-all | 7743 | yes | 3.53 | 0 |
| Surfboard-tg-mixed | 7345 | yes | 3.31 | 0 |
| barry-far-vless | 6112 | yes | 0.82 | 0 |
| DeltaKronecker-all | 5970 | yes | 4.28 | 0 |
| Surfboard-tg-vless | 5912 | yes | 4.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 1.55 | 0 |
| mahdibland-V2RayAggregator | 4207 | yes | 2.74 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 69 |
| 204 | 47 |
| cn-block | 30 |
| speed | 20 |
| sing-box exited 1 | 1 |
