# AutoNodes 每日报告

生成时间：2026-09-08 04:02:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91631 |
| 去重后节点数 | 25396 |
| TCP 可达数 | 3000 |
| 真测通过数 | 646 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25396 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 50.6 |
| geo | 1.5 |
| probe | 91.8 |
| real_test | 189.2 |
| tcp | 42.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 5 | 0 | 100.0% |
| http | 58 | 51 | 7 | 87.9% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 181 | 167 | 14 | 92.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 18 | 12 | 6 | 66.7% |
| vless | 879 | 388 | 491 | 44.1% |
| vmess | 2 | 0 | 2 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 173 |
| speed:TimeoutError | 91 |
| geo:ClientOSError | 78 |
| cn-block:ClientOSError | 65 |
| speed:ClientOSError | 52 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 14 |
| 204:ProxyConnectionError | 11 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5890 |
| ConnectionRefusedError | 960 |
| gaierror | 380 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | prefer | 349 | 0.914 | 1833 |
| ermaozi-get_subscribe | 0.894 | prefer | 19 | 0.947 | 470 |
| ermaozi | 0.851 | prefer | 40 | 0.85 | 450 |
| Surfboard-tg-mixed | 0.783 | prefer | 126 | 0.706 | 7392 |
| DeltaKronecker-all | 0.487 | observe | 57 | 0.404 | 6417 |
| tg-oneclickvpnkeys | 0.408 | observe | 4 | 1.0 | 196 |
| mheidari-all | 0.36 | observe | 570 | 0.279 | 22287 |
| Epodonios-all | 0.255 | observe | 0 | None | 7885 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8682 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.279 | 159 | 411 | 570 |
| DeltaKronecker-all | 0.404 | 23 | 34 | 57 |
| Surfboard-tg-mixed | 0.706 | 89 | 37 | 126 |
| ermaozi | 0.85 | 34 | 6 | 40 |
| Au1rxx-base64 | 0.914 | 319 | 30 | 349 |
| ermaozi-get_subscribe | 0.947 | 18 | 1 | 19 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22287 | yes | 6.77 | 0 |
| SoliSpirit-all | 8682 | yes | 3.89 | 0 |
| Epodonios-all | 7885 | yes | 3.71 | 0 |
| Surfboard-tg-mixed | 7392 | yes | 4.54 | 0 |
| barry-far-vless | 6444 | yes | 2.49 | 0 |
| DeltaKronecker-all | 6417 | yes | 5.31 | 0 |
| Surfboard-tg-vless | 6186 | yes | 4.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 2.26 | 0 |
| mahdibland-V2RayAggregator | 4218 | yes | 1.87 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 4.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 252 |
| speed | 144 |
| cn-block | 88 |
| 204 | 37 |
