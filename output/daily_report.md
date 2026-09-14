# AutoNodes 每日报告

生成时间：2026-09-14 04:29:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 84465 |
| 去重后节点数 | 23126 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23126 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 82.6 |
| geo | 1.4 |
| probe | 281.5 |
| real_test | 354.9 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 58 | 40 | 18 | 69.0% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 162 | 150 | 12 | 92.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 29 | 15 | 14 | 51.7% |
| vless | 488 | 264 | 224 | 54.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 48 |
| speed:TimeoutError | 48 |
| speed:ClientOSError | 42 |
| geo:ClientOSError | 41 |
| cn-block:TimeoutError | 29 |
| cn-block:ClientOSError | 25 |
| 204:ProxyError | 19 |
| 204:TimeoutError | 14 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5229 |
| ConnectionRefusedError | 891 |
| gaierror | 476 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.846 | prefer | 319 | 0.781 | 1684 |
| Surfboard-tg-mixed | 0.72 | prefer | 201 | 0.642 | 7482 |
| ermaozi | 0.709 | prefer | 50 | 0.7 | 417 |
| mheidari-all | 0.565 | observe | 132 | 0.485 | 15963 |
| roosterkid-openproxylist-v2ray | 0.406 | observe | 4 | 1.0 | 150 |
| ermaozi-get_subscribe | 0.384 | observe | 8 | 0.625 | 444 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7945 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8786 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.232 | 44 | 0.136 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.136 | 6 | 38 | 44 |
| 10ium-ScrapeCategorize-Vless | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.485 | 64 | 68 | 132 |
| ermaozi-get_subscribe | 0.625 | 5 | 3 | 8 |
| Surfboard-tg-mixed | 0.642 | 129 | 72 | 201 |
| ermaozi | 0.7 | 35 | 15 | 50 |
| Au1rxx-base64 | 0.781 | 249 | 70 | 319 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15963 | yes | 3.59 | 0 |
| SoliSpirit-all | 8786 | yes | 2.32 | 0 |
| Epodonios-all | 7945 | yes | 1.95 | 0 |
| Surfboard-tg-mixed | 7482 | yes | 2.65 | 0 |
| barry-far-vless | 6350 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 6107 | yes | 2.45 | 0 |
| DeltaKronecker-all | 5892 | yes | 2.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.02 | 0 |
| mahdibland-V2RayAggregator | 4222 | yes | 1.99 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 90 |
| speed | 90 |
| cn-block | 55 |
| 204 | 36 |
