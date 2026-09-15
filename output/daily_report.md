# AutoNodes 每日报告

生成时间：2026-09-15 21:14:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84752 |
| 去重后节点数 | 23104 |
| TCP 可达数 | 3000 |
| 真测通过数 | 447 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23104 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 81.8 |
| geo | 1.4 |
| probe | 268.5 |
| real_test | 206.1 |
| tcp | 38.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 20 | 8 | 71.4% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 165 | 152 | 13 | 92.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 8 | 8 | 0 | 100.0% |
| vless | 331 | 249 | 82 | 75.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 25 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 16 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5268 |
| ConnectionRefusedError | 839 |
| gaierror | 374 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 308 | 0.906 | 1553 |
| DeltaKronecker-all | 0.908 | prefer | 27 | 0.852 | 5932 |
| mheidari-all | 0.8 | prefer | 48 | 0.729 | 15952 |
| Surfboard-tg-mixed | 0.702 | prefer | 141 | 0.624 | 7516 |
| ermaozi | 0.695 | observe | 26 | 0.692 | 406 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 422 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 148 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |

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
| Surfboard-tg-mixed | 0.624 | 88 | 53 | 141 |
| ermaozi | 0.692 | 18 | 8 | 26 |
| mheidari-all | 0.729 | 35 | 13 | 48 |
| DeltaKronecker-all | 0.852 | 23 | 4 | 27 |
| Au1rxx-base64 | 0.906 | 279 | 29 | 308 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15952 | yes | 3.1 | 0 |
| SoliSpirit-all | 8946 | yes | 3.51 | 0 |
| Epodonios-all | 7982 | yes | 3.54 | 0 |
| Surfboard-tg-mixed | 7516 | yes | 3.38 | 0 |
| barry-far-vless | 6289 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 6065 | yes | 2.64 | 0 |
| DeltaKronecker-all | 5932 | yes | 4.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 2.22 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 0.8 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| cn-block | 34 |
| geo | 27 |
| speed | 12 |
