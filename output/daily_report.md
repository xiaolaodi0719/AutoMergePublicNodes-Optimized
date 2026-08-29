# AutoNodes 每日报告

生成时间：2026-08-29 16:35:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78466 |
| 去重后节点数 | 21213 |
| TCP 可达数 | 3000 |
| 真测通过数 | 553 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21213 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 36.2 |
| geo | 1.4 |
| probe | 58.0 |
| real_test | 126.6 |
| tcp | 34.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 178 | 165 | 13 | 92.7% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 32 | 19 | 13 | 59.4% |
| vless | 359 | 316 | 43 | 88.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 14 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| geo:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4372 |
| ConnectionRefusedError | 887 |
| gaierror | 504 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 358 | 0.936 | 1807 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.883 | prefer | 125 | 0.808 | 6877 |
| DeltaKronecker-all | 0.868 | prefer | 31 | 0.806 | 4926 |
| mheidari-all | 0.845 | prefer | 83 | 0.771 | 14622 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 156 |
| nscl5-all | 0.283 | observe | 1 | 1.0 | 700 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4635 |
| Epodonios-all | 0.255 | observe | 0 | None | 7290 |

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
| mheidari-all | 0.771 | 64 | 19 | 83 |
| DeltaKronecker-all | 0.806 | 25 | 6 | 31 |
| Surfboard-tg-mixed | 0.808 | 101 | 24 | 125 |
| Au1rxx-base64 | 0.936 | 335 | 23 | 358 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14622 | yes | 4.62 | 0 |
| SoliSpirit-all | 7426 | yes | 1.62 | 0 |
| Epodonios-all | 7290 | yes | 2.74 | 0 |
| Surfboard-tg-mixed | 6877 | yes | 3.59 | 0 |
| barry-far-vless | 5725 | yes | 2.62 | 0 |
| Surfboard-tg-vless | 5686 | yes | 4.2 | 0 |
| DeltaKronecker-all | 4926 | yes | 5.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 4635 | yes | 2.43 | 0 |
| mahdibland-V2RayAggregator | 4012 | yes | 1.78 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 24 |
| cn-block | 23 |
| geo | 16 |
| speed | 10 |
