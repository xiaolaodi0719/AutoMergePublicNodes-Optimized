# AutoNodes 每日报告

生成时间：2026-08-25 12:59:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78389 |
| 去重后节点数 | 22412 |
| TCP 可达数 | 3000 |
| 真测通过数 | 571 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22412 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 43.3 |
| geo | 1.4 |
| probe | 54.5 |
| real_test | 125.4 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 27 | 27 | 0 | 100.0% |
| shadowsocks | 199 | 181 | 18 | 91.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 47 | 38 | 9 | 80.9% |
| vless | 386 | 299 | 87 | 77.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 30 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 18 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 6 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5389 |
| ConnectionRefusedError | 834 |
| gaierror | 142 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.955 | prefer | 70 | 0.886 | 14402 |
| Au1rxx-base64 | 0.925 | prefer | 388 | 0.863 | 1581 |
| Surfboard-tg-mixed | 0.82 | prefer | 152 | 0.743 | 6520 |
| DeltaKronecker-all | 0.784 | prefer | 52 | 0.712 | 6340 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 7010 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7084 |

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
| DeltaKronecker-all | 0.712 | 37 | 15 | 52 |
| Surfboard-tg-mixed | 0.743 | 113 | 39 | 152 |
| Au1rxx-base64 | 0.863 | 335 | 53 | 388 |
| mheidari-all | 0.886 | 62 | 8 | 70 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14402 | yes | 4.8 | 0 |
| SoliSpirit-all | 7084 | yes | 3.22 | 0 |
| Epodonios-all | 7010 | yes | 1.81 | 0 |
| Surfboard-tg-mixed | 6520 | yes | 3.0 | 0 |
| DeltaKronecker-all | 6340 | yes | 3.64 | 0 |
| barry-far-vless | 5577 | yes | 2.08 | 0 |
| Surfboard-tg-vless | 5377 | yes | 3.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.52 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 2.48 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 2.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 35 |
| 204 | 33 |
| cn-block | 27 |
| speed | 21 |
