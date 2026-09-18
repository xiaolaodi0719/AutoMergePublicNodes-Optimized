# AutoNodes 每日报告

生成时间：2026-09-18 11:06:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83513 |
| 去重后节点数 | 22979 |
| TCP 可达数 | 3000 |
| 真测通过数 | 395 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22979 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 83.2 |
| geo | 1.6 |
| probe | 284.6 |
| real_test | 256.0 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 33 | 11 | 75.0% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 173 | 160 | 13 | 92.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 29 | 6 | 23 | 20.7% |
| vless | 293 | 186 | 107 | 63.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 29 |
| geo:TimeoutError | 26 |
| geo:ClientOSError | 23 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 17 |
| speed:TimeoutError | 16 |
| speed:ClientOSError | 10 |
| cn-block:ClientOSError | 10 |
| 204:ClientOSError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5315 |
| ConnectionRefusedError | 826 |
| gaierror | 401 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.908 | prefer | 246 | 0.846 | 1622 |
| ermaozi | 0.748 | prefer | 43 | 0.744 | 378 |
| mheidari-all | 0.712 | prefer | 66 | 0.636 | 15778 |
| Surfboard-tg-mixed | 0.706 | prefer | 145 | 0.628 | 7294 |
| DeltaKronecker-all | 0.509 | observe | 47 | 0.426 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7751 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8957 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.426 | 20 | 27 | 47 |
| Surfboard-tg-mixed | 0.628 | 91 | 54 | 145 |
| mheidari-all | 0.636 | 42 | 24 | 66 |
| ermaozi | 0.744 | 32 | 11 | 43 |
| Au1rxx-base64 | 0.846 | 208 | 38 | 246 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15778 | yes | 4.72 | 0 |
| SoliSpirit-all | 8957 | yes | 4.38 | 0 |
| Epodonios-all | 7751 | yes | 5.46 | 0 |
| Surfboard-tg-mixed | 7294 | yes | 4.0 | 0 |
| DeltaKronecker-all | 6040 | yes | 4.92 | 0 |
| barry-far-vless | 5979 | yes | 2.06 | 0 |
| Surfboard-tg-vless | 5763 | yes | 4.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 1.83 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 52 |
| geo | 50 |
| cn-block | 28 |
| speed | 26 |
