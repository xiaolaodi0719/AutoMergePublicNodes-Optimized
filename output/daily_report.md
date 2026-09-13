# AutoNodes 每日报告

生成时间：2026-09-13 11:40:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94200 |
| 去重后节点数 | 25204 |
| TCP 可达数 | 3000 |
| 真测通过数 | 446 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25204 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 82.9 |
| geo | 1.5 |
| probe | 344.0 |
| real_test | 259.1 |
| tcp | 43.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 55 | 37 | 18 | 67.3% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 171 | 149 | 22 | 87.1% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 23 | 14 | 9 | 60.9% |
| vless | 347 | 220 | 127 | 63.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 41 |
| 204:TimeoutError | 36 |
| 204:ProxyError | 30 |
| speed:ClientOSError | 19 |
| cn-block:TimeoutError | 17 |
| geo:TimeoutError | 13 |
| cn-block:ClientOSError | 9 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5860 |
| ConnectionRefusedError | 978 |
| gaierror | 426 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | prefer | 259 | 0.822 | 1633 |
| Surfboard-tg-mixed | 0.757 | prefer | 153 | 0.68 | 7439 |
| ermaozi | 0.751 | prefer | 43 | 0.744 | 436 |
| mheidari-all | 0.653 | observe | 141 | 0.574 | 20485 |
| DeltaKronecker-all | 0.489 | observe | 9 | 0.667 | 5892 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| ermaozi-get_subscribe | 0.328 | observe | 13 | 0.385 | 464 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 102 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.385 | 5 | 8 | 13 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| roosterkid-openproxylist-v2ray | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.574 | 81 | 60 | 141 |
| DeltaKronecker-all | 0.667 | 6 | 3 | 9 |
| Surfboard-tg-mixed | 0.68 | 104 | 49 | 153 |
| ermaozi | 0.744 | 32 | 11 | 43 |
| Au1rxx-base64 | 0.822 | 213 | 46 | 259 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20485 | yes | 6.14 | 0 |
| SoliSpirit-all | 8920 | yes | 3.48 | 0 |
| Epodonios-all | 7887 | yes | 3.83 | 0 |
| Surfboard-tg-mixed | 7439 | yes | 4.83 | 0 |
| barry-far-vless | 6291 | yes | 1.83 | 0 |
| Surfboard-tg-vless | 6075 | yes | 4.03 | 0 |
| DeltaKronecker-all | 5892 | yes | 5.33 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 1.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.63 | 0 |
| mahdibland-V2RayAggregator | 4221 | yes | 3.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 69 |
| geo | 54 |
| speed | 30 |
| cn-block | 27 |
