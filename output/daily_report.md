# AutoNodes 每日报告

生成时间：2026-09-15 04:36:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90171 |
| 去重后节点数 | 25748 |
| TCP 可达数 | 3000 |
| 真测通过数 | 502 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25748 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 83.2 |
| geo | 1.4 |
| probe | 452.1 |
| real_test | 590.4 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 43 | 26 | 17 | 60.5% |
| hysteria2 | 29 | 28 | 1 | 96.6% |
| shadowsocks | 170 | 160 | 10 | 94.1% |
| trojan | 2 | 1 | 1 | 50.0% |
| vless | 854 | 285 | 569 | 33.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 199 |
| speed:TimeoutError | 92 |
| geo:ClientOSError | 88 |
| cn-block:ClientOSError | 76 |
| speed:ClientOSError | 56 |
| 204:ProxyError | 40 |
| cn-block:TimeoutError | 28 |
| 204:TimeoutError | 15 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42000: bind: address already in use | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5697 |
| ConnectionRefusedError | 965 |
| gaierror | 432 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | prefer | 287 | 0.805 | 1584 |
| Surfboard-tg-mixed | 0.758 | prefer | 172 | 0.68 | 7572 |
| ermaozi | 0.628 | observe | 34 | 0.618 | 425 |
| ermaozi-get_subscribe | 0.368 | observe | 9 | 0.556 | 447 |
| mheidari-all | 0.294 | observe | 592 | 0.213 | 21540 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 120 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 8044 |
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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.213 | 126 | 466 | 592 |
| ermaozi-get_subscribe | 0.556 | 5 | 4 | 9 |
| ermaozi | 0.618 | 21 | 13 | 34 |
| Surfboard-tg-mixed | 0.68 | 117 | 55 | 172 |
| Au1rxx-base64 | 0.805 | 231 | 56 | 287 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21540 | yes | 3.49 | 0 |
| SoliSpirit-all | 8754 | yes | 1.99 | 0 |
| Epodonios-all | 8044 | yes | 3.66 | 0 |
| Surfboard-tg-mixed | 7572 | yes | 3.03 | 0 |
| barry-far-vless | 6333 | yes | 0.7 | 0 |
| Surfboard-tg-vless | 6105 | yes | 2.47 | 0 |
| DeltaKronecker-all | 5972 | yes | 3.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 4099 | yes | 1.96 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 288 |
| speed | 148 |
| cn-block | 104 |
| 204 | 57 |
| sing-box exited 1 | 1 |
