# AutoNodes 每日报告

生成时间：2026-10-16 20:57:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99400 |
| 去重后节点数 | 27657 |
| TCP 可达数 | 3000 |
| 真测通过数 | 445 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27657 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 79.4 |
| geo | 1.5 |
| probe | 254.1 |
| real_test | 291.0 |
| tcp | 48.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 61 | 25 | 36 | 41.0% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 160 | 133 | 27 | 83.1% |
| trojan | 48 | 43 | 5 | 89.6% |
| vless | 331 | 226 | 105 | 68.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 48 |
| 204:TimeoutError | 37 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 14 |
| speed:ClientOSError | 14 |
| geo:TimeoutError | 14 |
| cn-block:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| 204:ClientOSError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44687: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7143 |
| ConnectionRefusedError | 1049 |
| gaierror | 234 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.867 | prefer | 501 | 0.788 | 1995 |
| Surfboard-tg-mixed | 0.515 | observe | 44 | 0.432 | 7222 |
| ermaozi | 0.418 | observe | 59 | 0.39 | 618 |
| mheidari-all | 0.389 | observe | 13 | 0.385 | 23910 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 88 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 4946 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7598 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.385 | 5 | 8 | 13 |
| ermaozi | 0.39 | 23 | 36 | 59 |
| Surfboard-tg-mixed | 0.432 | 19 | 25 | 44 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.788 | 395 | 106 | 501 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23910 | yes | 3.59 | 0 |
| SoliSpirit-all | 10077 | yes | 2.0 | 0 |
| Epodonios-all | 7598 | yes | 2.92 | 0 |
| Surfboard-tg-mixed | 7222 | yes | 4.35 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.84 | 0 |
| barry-far-vless | 5818 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 5648 | yes | 2.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 1.41 | 0 |
| DeltaKronecker-all | 4946 | yes | 3.43 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 94 |
| geo | 28 |
| cn-block | 28 |
| speed | 25 |
| sing-box exited 1 | 1 |
