# AutoNodes 每日报告

生成时间：2026-09-29 05:23:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96799 |
| 去重后节点数 | 27001 |
| TCP 可达数 | 3000 |
| 真测通过数 | 543 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27001 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 91.5 |
| geo | 1.4 |
| probe | 289.4 |
| real_test | 416.1 |
| tcp | 44.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 23 | 10 | 69.7% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 191 | 167 | 24 | 87.4% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 30 | 27 | 3 | 90.0% |
| vless | 650 | 297 | 353 | 45.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 129 |
| speed:TimeoutError | 85 |
| speed:ClientOSError | 70 |
| geo:ClientOSError | 39 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 17 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6119 |
| ConnectionRefusedError | 985 |
| gaierror | 409 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.865 | prefer | 350 | 0.803 | 1609 |
| Surfboard-tg-mixed | 0.769 | prefer | 217 | 0.691 | 7005 |
| ermaozi | 0.724 | prefer | 29 | 0.724 | 354 |
| DeltaKronecker-all | 0.482 | observe | 14 | 0.5 | 5428 |
| mheidari-all | 0.337 | observe | 317 | 0.256 | 22589 |
| ermaozi-get_subscribe | 0.308 | observe | 5 | 0.6 | 367 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7625 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9567 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.256 | 81 | 236 | 317 |
| DeltaKronecker-all | 0.5 | 7 | 7 | 14 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.691 | 150 | 67 | 217 |
| ermaozi | 0.724 | 21 | 8 | 29 |
| Au1rxx-base64 | 0.803 | 281 | 69 | 350 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22589 | yes | 6.2 | 0 |
| SoliSpirit-all | 9567 | yes | 3.38 | 0 |
| Epodonios-all | 7625 | yes | 3.16 | 0 |
| Surfboard-tg-mixed | 7005 | yes | 4.09 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.04 | 0 |
| barry-far-vless | 6028 | yes | 2.3 | 0 |
| Surfboard-tg-vless | 5633 | yes | 3.7 | 0 |
| DeltaKronecker-all | 5428 | yes | 4.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 2.16 | 0 |
| mahdibland-V2RayAggregator | 4237 | yes | 3.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 168 |
| speed | 158 |
| 204 | 42 |
| cn-block | 26 |
