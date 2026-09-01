# AutoNodes 每日报告

生成时间：2026-09-01 11:29:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83205 |
| 去重后节点数 | 24567 |
| TCP 可达数 | 3000 |
| 真测通过数 | 589 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24567 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 34.7 |
| geo | 1.5 |
| probe | 87.6 |
| real_test | 121.7 |
| tcp | 39.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 9 | 6 | 3 | 66.7% |
| shadowsocks | 133 | 127 | 6 | 95.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 33 | 20 | 13 | 60.6% |
| vless | 537 | 411 | 126 | 76.5% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 35 |
| 204:TimeoutError | 27 |
| speed:TimeoutError | 23 |
| geo:ClientOSError | 17 |
| geo:TimeoutError | 14 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 10 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4741 |
| ConnectionRefusedError | 1015 |
| gaierror | 430 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Au1rxx-base64 | 0.923 | prefer | 329 | 0.857 | 1711 |
| mheidari-all | 0.839 | prefer | 193 | 0.762 | 17148 |
| Surfboard-tg-mixed | 0.83 | prefer | 182 | 0.753 | 6921 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7334 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7625 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5831 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.189 | 11 | 0.091 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.091 | 1 | 10 | 11 |
| Surfboard-tg-mixed | 0.753 | 137 | 45 | 182 |
| mheidari-all | 0.762 | 147 | 46 | 193 |
| Au1rxx-base64 | 0.857 | 282 | 47 | 329 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17148 | yes | 4.54 | 0 |
| SoliSpirit-all | 7625 | yes | 4.67 | 0 |
| Epodonios-all | 7334 | yes | 4.81 | 0 |
| DeltaKronecker-all | 7294 | yes | 5.0 | 0 |
| Surfboard-tg-mixed | 6921 | yes | 3.56 | 0 |
| barry-far-vless | 6092 | yes | 3.08 | 0 |
| Surfboard-tg-vless | 5831 | yes | 3.34 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 3.07 | 0 |
| mahdibland-V2RayAggregator | 4013 | yes | 0.51 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 47 |
| 204 | 43 |
| geo | 33 |
| speed | 27 |
