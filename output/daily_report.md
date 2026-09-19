# AutoNodes 每日报告

生成时间：2026-09-19 10:47:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87584 |
| 去重后节点数 | 25144 |
| TCP 可达数 | 3000 |
| 真测通过数 | 484 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25144 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 76.1 |
| geo | 1.4 |
| probe | 224.1 |
| real_test | 217.3 |
| tcp | 41.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 38 | 12 | 76.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 175 | 158 | 17 | 90.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 18 | 13 | 5 | 72.2% |
| vless | 415 | 258 | 157 | 62.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 40 |
| cn-block:ClientOSError | 32 |
| geo:TimeoutError | 23 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 20 |
| speed:TimeoutError | 20 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 13 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5718 |
| ConnectionRefusedError | 892 |
| gaierror | 434 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | prefer | 307 | 0.844 | 1569 |
| ermaozi | 0.764 | prefer | 50 | 0.76 | 358 |
| DeltaKronecker-all | 0.716 | prefer | 31 | 0.645 | 6421 |
| Surfboard-tg-mixed | 0.691 | observe | 206 | 0.612 | 7474 |
| mheidari-all | 0.568 | observe | 80 | 0.487 | 19088 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7699 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.487 | 39 | 41 | 80 |
| Surfboard-tg-mixed | 0.612 | 126 | 80 | 206 |
| DeltaKronecker-all | 0.645 | 20 | 11 | 31 |
| ermaozi | 0.76 | 38 | 12 | 50 |
| Au1rxx-base64 | 0.844 | 259 | 48 | 307 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19088 | yes | 3.66 | 0 |
| SoliSpirit-all | 8837 | yes | 1.25 | 0 |
| Epodonios-all | 7699 | yes | 2.36 | 0 |
| Surfboard-tg-mixed | 7474 | yes | 2.6 | 0 |
| DeltaKronecker-all | 6421 | yes | 3.79 | 0 |
| Surfboard-tg-vless | 6006 | yes | 2.81 | 0 |
| barry-far-vless | 5996 | yes | 1.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 1.03 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 2.02 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 64 |
| cn-block | 52 |
| 204 | 44 |
| speed | 33 |
