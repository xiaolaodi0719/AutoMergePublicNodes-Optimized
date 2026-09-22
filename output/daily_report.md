# AutoNodes 每日报告

生成时间：2026-09-22 11:27:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 91703 |
| 去重后节点数 | 25251 |
| TCP 可达数 | 3000 |
| 真测通过数 | 461 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25251 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 93.9 |
| geo | 1.4 |
| probe | 232.0 |
| real_test | 199.7 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 48 | 32 | 16 | 66.7% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 153 | 145 | 8 | 94.8% |
| socks | 6 | 1 | 5 | 16.7% |
| trojan | 28 | 18 | 10 | 64.3% |
| vless | 491 | 247 | 244 | 50.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 80 |
| geo:ClientOSError | 67 |
| speed:ClientOSError | 43 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 21 |
| geo:TimeoutError | 20 |
| 204:TimeoutError | 17 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5869 |
| ConnectionRefusedError | 931 |
| gaierror | 295 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.946 | prefer | 292 | 0.884 | 1630 |
| ermaozi | 0.689 | observe | 44 | 0.682 | 369 |
| Surfboard-tg-mixed | 0.594 | observe | 179 | 0.514 | 7157 |
| mheidari-all | 0.434 | observe | 204 | 0.353 | 19835 |
| DeltaKronecker-all | 0.382 | observe | 14 | 0.357 | 6324 |
| ermaozi-get_subscribe | 0.309 | observe | 5 | 0.6 | 393 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 4242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7495 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9028 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.353 | 72 | 132 | 204 |
| DeltaKronecker-all | 0.357 | 5 | 9 | 14 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.514 | 92 | 87 | 179 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| ermaozi | 0.682 | 30 | 14 | 44 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19835 | yes | 6.18 | 0 |
| SoliSpirit-all | 9028 | yes | 5.49 | 0 |
| Epodonios-all | 7495 | yes | 3.52 | 0 |
| Surfboard-tg-mixed | 7157 | yes | 5.27 | 0 |
| DeltaKronecker-all | 6324 | yes | 5.31 | 0 |
| barry-far-vless | 5817 | yes | 2.48 | 0 |
| Surfboard-tg-vless | 5792 | yes | 4.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 2.75 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 1.87 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 3.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 103 |
| geo | 88 |
| speed | 53 |
| 204 | 41 |
