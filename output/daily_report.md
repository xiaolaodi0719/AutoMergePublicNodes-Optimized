# AutoNodes 每日报告

生成时间：2026-09-08 21:09:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84956 |
| 去重后节点数 | 22773 |
| TCP 可达数 | 3000 |
| 真测通过数 | 533 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22773 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 79.8 |
| geo | 1.5 |
| probe | 298.7 |
| real_test | 281.6 |
| tcp | 38.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 34 | 24 | 10 | 70.6% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 174 | 160 | 14 | 92.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 32 | 22 | 10 | 68.8% |
| vless | 389 | 308 | 81 | 79.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 25 |
| 204:TimeoutError | 24 |
| geo:ClientOSError | 23 |
| 204:ProxyError | 18 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| speed:TimeoutError | 4 |
| geo:ProxyError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5051 |
| ConnectionRefusedError | 880 |
| gaierror | 488 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 303 | 0.901 | 1700 |
| DeltaKronecker-all | 0.913 | prefer | 22 | 0.864 | 6097 |
| Surfboard-tg-mixed | 0.827 | prefer | 172 | 0.75 | 7370 |
| mheidari-all | 0.826 | prefer | 116 | 0.75 | 16416 |
| ermaozi | 0.711 | prefer | 34 | 0.706 | 409 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7999 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8578 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6089 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.706 | 24 | 10 | 34 |
| mheidari-all | 0.75 | 87 | 29 | 116 |
| Surfboard-tg-mixed | 0.75 | 129 | 43 | 172 |
| DeltaKronecker-all | 0.864 | 19 | 3 | 22 |
| Au1rxx-base64 | 0.901 | 273 | 30 | 303 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16416 | yes | 4.79 | 0 |
| SoliSpirit-all | 8578 | yes | 5.09 | 0 |
| Epodonios-all | 7999 | yes | 3.21 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 4.1 | 0 |
| barry-far-vless | 6497 | yes | 1.0 | 0 |
| DeltaKronecker-all | 6097 | yes | 4.77 | 0 |
| Surfboard-tg-vless | 6089 | yes | 3.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 2.66 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.3 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 47 |
| cn-block | 35 |
| geo | 27 |
| speed | 9 |
