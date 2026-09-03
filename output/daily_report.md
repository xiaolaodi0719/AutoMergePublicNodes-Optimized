# AutoNodes 每日报告

生成时间：2026-09-03 16:14:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82139 |
| 去重后节点数 | 22600 |
| TCP 可达数 | 3000 |
| 真测通过数 | 584 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22600 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 34.9 |
| geo | 1.7 |
| probe | 86.9 |
| real_test | 126.7 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 26 | 1 | 96.3% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 156 | 143 | 13 | 91.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 27 | 25 | 2 | 92.6% |
| vless | 436 | 363 | 73 | 83.3% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 22 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4603 |
| ConnectionRefusedError | 927 |
| gaierror | 370 |
| OSError | 31 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 330 | 0.952 | 1770 |
| zhangkai | 0.926 | prefer | 23 | 0.957 | 144 |
| mheidari-all | 0.871 | prefer | 108 | 0.796 | 15770 |
| DeltaKronecker-all | 0.864 | prefer | 35 | 0.8 | 6335 |
| Surfboard-tg-mixed | 0.817 | prefer | 173 | 0.74 | 7139 |
| tg-oneclickvpnkeys | 0.445 | observe | 5 | 1.0 | 145 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7586 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.74 | 128 | 45 | 173 |
| mheidari-all | 0.796 | 86 | 22 | 108 |
| DeltaKronecker-all | 0.8 | 28 | 7 | 35 |
| Au1rxx-base64 | 0.952 | 314 | 16 | 330 |
| zhangkai | 0.957 | 22 | 1 | 23 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15770 | yes | 4.74 | 0 |
| SoliSpirit-all | 7991 | yes | 4.71 | 0 |
| Epodonios-all | 7586 | yes | 1.45 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.29 | 0 |
| DeltaKronecker-all | 6335 | yes | 5.14 | 0 |
| barry-far-vless | 6219 | yes | 2.57 | 0 |
| Surfboard-tg-vless | 6006 | yes | 3.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 2.82 | 0 |
| mahdibland-V2RayAggregator | 4081 | yes | 1.53 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 37 |
| geo | 26 |
| cn-block | 17 |
| speed | 12 |
