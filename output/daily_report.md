# AutoNodes 每日报告

生成时间：2026-09-20 15:54:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84264 |
| 去重后节点数 | 23485 |
| TCP 可达数 | 3000 |
| 真测通过数 | 446 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23485 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 84.3 |
| geo | 1.5 |
| probe | 172.3 |
| real_test | 175.0 |
| tcp | 38.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 30 | 18 | 12 | 60.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 154 | 138 | 16 | 89.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 12 | 7 | 5 | 58.3% |
| vless | 373 | 263 | 110 | 70.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 39 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 14 |
| geo:TimeoutError | 12 |
| cn-block:ClientOSError | 11 |
| 204:ProxyConnectionError | 10 |
| speed:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5270 |
| ConnectionRefusedError | 800 |
| gaierror | 392 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | prefer | 277 | 0.899 | 1617 |
| Surfboard-tg-mixed | 0.734 | prefer | 206 | 0.655 | 7133 |
| mheidari-all | 0.683 | observe | 61 | 0.607 | 16459 |
| ermaozi | 0.679 | observe | 25 | 0.68 | 314 |
| DeltaKronecker-all | 0.352 | observe | 11 | 0.364 | 6092 |
| 10ium-ScrapeCategorize-Vless | 0.349 | observe | 3 | 0.667 | 5238 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 103 |
| Epodonios-all | 0.255 | observe | 0 | None | 7577 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.364 | 4 | 7 | 11 |
| mheidari-all | 0.607 | 37 | 24 | 61 |
| Surfboard-tg-mixed | 0.655 | 135 | 71 | 206 |
| 10ium-ScrapeCategorize-Vless | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.68 | 17 | 8 | 25 |
| Au1rxx-base64 | 0.899 | 249 | 28 | 277 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16459 | yes | 4.97 | 0 |
| SoliSpirit-all | 9286 | yes | 2.81 | 0 |
| Epodonios-all | 7577 | yes | 3.38 | 0 |
| Surfboard-tg-mixed | 7133 | yes | 4.21 | 0 |
| DeltaKronecker-all | 6092 | yes | 3.9 | 0 |
| barry-far-vless | 5918 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5703 | yes | 4.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 0.78 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 3.07 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 52 |
| 204 | 50 |
| cn-block | 33 |
| speed | 10 |
