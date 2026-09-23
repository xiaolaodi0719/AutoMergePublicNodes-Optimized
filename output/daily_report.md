# AutoNodes 每日报告

生成时间：2026-09-23 11:19:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 96837 |
| 去重后节点数 | 26486 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26486 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 72.4 |
| geo | 1.4 |
| probe | 214.5 |
| real_test | 195.3 |
| tcp | 43.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 68 | 48 | 20 | 70.6% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 167 | 157 | 10 | 94.0% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 12 | 8 | 4 | 66.7% |
| vless | 301 | 197 | 104 | 65.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 25 |
| 204:ProxyError | 24 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 17 |
| geo:TimeoutError | 15 |
| speed:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 5 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6018 |
| ConnectionRefusedError | 958 |
| gaierror | 292 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.94 | prefer | 224 | 0.879 | 1602 |
| mheidari-all | 0.816 | prefer | 89 | 0.742 | 22242 |
| Surfboard-tg-mixed | 0.788 | prefer | 128 | 0.711 | 7036 |
| ermaozi | 0.76 | prefer | 57 | 0.754 | 346 |
| DeltaKronecker-all | 0.572 | observe | 61 | 0.492 | 6471 |
| ermaozi-get_subscribe | 0.296 | observe | 10 | 0.4 | 372 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 119 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7633 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.4 | 4 | 6 | 10 |
| DeltaKronecker-all | 0.492 | 30 | 31 | 61 |
| Surfboard-tg-mixed | 0.711 | 91 | 37 | 128 |
| mheidari-all | 0.742 | 66 | 23 | 89 |
| ermaozi | 0.754 | 43 | 14 | 57 |
| Au1rxx-base64 | 0.879 | 197 | 27 | 224 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22242 | yes | 5.07 | 0 |
| SoliSpirit-all | 9066 | yes | 4.37 | 0 |
| Epodonios-all | 7633 | yes | 2.56 | 0 |
| Surfboard-tg-mixed | 7036 | yes | 3.69 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.27 | 0 |
| DeltaKronecker-all | 6471 | yes | 3.38 | 0 |
| barry-far-vless | 5975 | yes | 2.16 | 0 |
| Surfboard-tg-vless | 5755 | yes | 3.29 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 2.67 | 0 |
| mahdibland-V2RayAggregator | 4187 | yes | 2.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| geo | 37 |
| cn-block | 32 |
| speed | 18 |
