# AutoNodes 每日报告

生成时间：2026-09-22 04:23:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 1/104 |
| 原始节点数 | 91704 |
| 去重后节点数 | 25163 |
| TCP 可达数 | 3000 |
| 真测通过数 | 512 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25163 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 80.2 |
| geo | 1.4 |
| probe | 215.8 |
| real_test | 266.5 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 18 | 14 | 56.2% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 170 | 160 | 10 | 94.1% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 39 | 29 | 10 | 74.4% |
| vless | 574 | 285 | 289 | 49.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 74 |
| geo:TimeoutError | 54 |
| cn-block:ClientOSError | 54 |
| speed:TimeoutError | 45 |
| speed:ClientOSError | 43 |
| cn-block:TimeoutError | 25 |
| 204:ProxyError | 18 |
| 204:TimeoutError | 11 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6332 |
| ConnectionRefusedError | 915 |
| gaierror | 241 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.918 | prefer | 302 | 0.854 | 1658 |
| Surfboard-tg-mixed | 0.657 | observe | 237 | 0.578 | 7121 |
| ermaozi | 0.586 | observe | 26 | 0.577 | 369 |
| mheidari-all | 0.504 | observe | 227 | 0.423 | 19852 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 153 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5290 |
| Epodonios-all | 0.255 | observe | 0 | None | 7572 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8704 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5672 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.161 | 35 | 0.057 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.235 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.057 | 2 | 33 | 35 |
| ninja-vless | 0.25 | 1 | 3 | 4 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| mheidari-all | 0.423 | 96 | 131 | 227 |
| ermaozi | 0.577 | 15 | 11 | 26 |
| Surfboard-tg-mixed | 0.578 | 137 | 100 | 237 |
| Au1rxx-base64 | 0.854 | 258 | 44 | 302 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19852 | yes | 3.95 | 0 |
| SoliSpirit-all | 8704 | yes | 2.82 | 0 |
| Epodonios-all | 7572 | yes | 3.59 | 0 |
| Surfboard-tg-mixed | 7121 | yes | 3.11 | 0 |
| DeltaKronecker-all | 6181 | yes | 4.21 | 0 |
| barry-far-vless | 5888 | yes | 1.09 | 0 |
| Surfboard-tg-vless | 5672 | yes | 2.77 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 1.6 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 1.96 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 0.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 128 |
| speed | 88 |
| cn-block | 80 |
| 204 | 31 |
