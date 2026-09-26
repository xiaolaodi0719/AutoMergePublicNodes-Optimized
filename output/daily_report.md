# AutoNodes 每日报告

生成时间：2026-09-26 11:16:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 97168 |
| 去重后节点数 | 26417 |
| TCP 可达数 | 3000 |
| 真测通过数 | 354 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26417 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 87.9 |
| geo | 1.6 |
| probe | 269.9 |
| real_test | 180.9 |
| tcp | 43.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 16 | 20 | 44.4% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 157 | 138 | 19 | 87.9% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 34 | 15 | 19 | 44.1% |
| vless | 241 | 160 | 81 | 66.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 30 |
| 204:TimeoutError | 29 |
| cn-block:ClientOSError | 27 |
| 204:ProxyError | 25 |
| geo:TimeoutError | 15 |
| speed:TimeoutError | 9 |
| cn-block:ProxyError | 3 |
| geo:ClientOSError | 3 |
| speed:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6111 |
| ConnectionRefusedError | 964 |
| gaierror | 393 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | prefer | 239 | 0.891 | 1660 |
| mheidari-all | 0.67 | observe | 103 | 0.592 | 22392 |
| Surfboard-tg-mixed | 0.64 | observe | 107 | 0.561 | 7247 |
| ermaozi | 0.424 | observe | 37 | 0.405 | 352 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5512 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7713 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.405 | 15 | 22 | 37 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| Surfboard-tg-mixed | 0.561 | 60 | 47 | 107 |
| mheidari-all | 0.592 | 61 | 42 | 103 |
| Au1rxx-base64 | 0.891 | 213 | 26 | 239 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22392 | yes | 5.67 | 0 |
| SoliSpirit-all | 9376 | yes | 1.66 | 0 |
| Epodonios-all | 7713 | yes | 3.06 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 3.83 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.33 | 0 |
| barry-far-vless | 6071 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5840 | yes | 3.38 | 0 |
| DeltaKronecker-all | 5512 | yes | 5.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 2.53 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 0.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 60 |
| 204 | 54 |
| geo | 18 |
| speed | 11 |
