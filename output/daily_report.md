# AutoNodes 每日报告

生成时间：2026-09-10 16:21:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 91095 |
| 去重后节点数 | 24432 |
| TCP 可达数 | 3000 |
| 真测通过数 | 455 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24432 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 80.8 |
| geo | 1.4 |
| probe | 318.1 |
| real_test | 277.2 |
| tcp | 41.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 20 | 7 | 74.1% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 158 | 141 | 17 | 89.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 34 | 20 | 14 | 58.8% |
| vless | 381 | 253 | 128 | 66.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 50 |
| 204:TimeoutError | 31 |
| cn-block:ClientOSError | 20 |
| 204:ProxyError | 19 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 11 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5221 |
| ConnectionRefusedError | 984 |
| gaierror | 461 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.931 | prefer | 275 | 0.865 | 1693 |
| ermaozi | 0.85 | prefer | 22 | 0.864 | 405 |
| Surfboard-tg-mixed | 0.78 | prefer | 158 | 0.703 | 7191 |
| mheidari-all | 0.62 | observe | 159 | 0.541 | 19266 |
| tg-oneclickvpnkeys | 0.264 | observe | 1 | 1.0 | 214 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7902 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8955 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5790 |

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
| ermaozi-get_subscribe | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.541 | 86 | 73 | 159 |
| Surfboard-tg-mixed | 0.703 | 111 | 47 | 158 |
| ermaozi | 0.864 | 19 | 3 | 22 |
| Au1rxx-base64 | 0.865 | 238 | 37 | 275 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19266 | yes | 3.72 | 0 |
| SoliSpirit-all | 8955 | yes | 3.46 | 0 |
| Epodonios-all | 7902 | yes | 4.34 | 0 |
| Surfboard-tg-mixed | 7191 | yes | 3.2 | 0 |
| barry-far-vless | 6248 | yes | 1.76 | 0 |
| DeltaKronecker-all | 5853 | yes | 4.11 | 0 |
| Surfboard-tg-vless | 5790 | yes | 3.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 2.13 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 2.39 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.57 | 0 |

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
| geo | 59 |
| 204 | 54 |
| cn-block | 40 |
| speed | 16 |
