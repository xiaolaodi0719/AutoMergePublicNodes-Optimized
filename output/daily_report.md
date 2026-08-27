# AutoNodes 每日报告

生成时间：2026-08-27 22:07:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87058 |
| 去重后节点数 | 23525 |
| TCP 可达数 | 3000 |
| 真测通过数 | 474 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23525 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.9 |
| generate | 34.9 |
| geo | 1.5 |
| probe | 47.1 |
| real_test | 87.8 |
| tcp | 38.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 182 | 163 | 19 | 89.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 19 | 13 | 6 | 68.4% |
| vless | 313 | 245 | 68 | 78.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 35 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 5 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5097 |
| ConnectionRefusedError | 958 |
| gaierror | 475 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 307 | 0.945 | 1622 |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.835 | prefer | 141 | 0.759 | 6577 |
| mheidari-all | 0.623 | observe | 90 | 0.544 | 19755 |
| DeltaKronecker-all | 0.4 | observe | 4 | 0.75 | 4318 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5418 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4783 |
| Epodonios-all | 0.255 | observe | 0 | None | 6955 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3991 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7129 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.544 | 49 | 41 | 90 |
| DeltaKronecker-all | 0.75 | 3 | 1 | 4 |
| Surfboard-tg-mixed | 0.759 | 107 | 34 | 141 |
| Au1rxx-base64 | 0.945 | 290 | 17 | 307 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19755 | yes | 5.17 | 0 |
| SoliSpirit-all | 7129 | yes | 3.72 | 0 |
| Epodonios-all | 6955 | yes | 3.21 | 0 |
| Surfboard-tg-mixed | 6577 | yes | 4.6 | 0 |
| barry-far-vless | 5568 | yes | 1.02 | 0 |
| Surfboard-tg-vless | 5393 | yes | 3.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4783 | yes | 1.29 | 0 |
| DeltaKronecker-all | 4318 | yes | 5.18 | 0 |
| mahdibland-V2RayAggregator | 4019 | yes | 2.84 | 0 |
| MatinGhanbari-all-sub | 3991 | yes | 0.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 40 |
| 204 | 22 |
| cn-block | 19 |
| speed | 13 |
