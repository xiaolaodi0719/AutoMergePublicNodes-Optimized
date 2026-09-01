# AutoNodes 每日报告

生成时间：2026-09-01 04:33:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79985 |
| 去重后节点数 | 22311 |
| TCP 可达数 | 3000 |
| 真测通过数 | 666 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22311 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 45.4 |
| geo | 1.4 |
| probe | 89.6 |
| real_test | 154.2 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 151 | 140 | 11 | 92.7% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 65 | 39 | 26 | 60.0% |
| vless | 817 | 440 | 377 | 53.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 194 |
| geo:ClientOSError | 68 |
| speed:ClientOSError | 49 |
| speed:TimeoutError | 46 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4949 |
| ConnectionRefusedError | 901 |
| gaierror | 283 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | prefer | 364 | 0.915 | 1549 |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.893 | prefer | 105 | 0.819 | 6997 |
| mheidari-all | 0.732 | prefer | 133 | 0.654 | 15162 |
| DeltaKronecker-all | 0.382 | observe | 449 | 0.301 | 5904 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7436 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7837 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5908 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.301 | 135 | 314 | 449 |
| mheidari-all | 0.654 | 87 | 46 | 133 |
| Surfboard-tg-mixed | 0.819 | 86 | 19 | 105 |
| Au1rxx-base64 | 0.915 | 333 | 31 | 364 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15162 | yes | 4.61 | 0 |
| SoliSpirit-all | 7837 | yes | 3.46 | 0 |
| Epodonios-all | 7436 | yes | 3.09 | 0 |
| Surfboard-tg-mixed | 6997 | yes | 3.78 | 0 |
| barry-far-vless | 6067 | yes | 2.8 | 0 |
| Surfboard-tg-vless | 5908 | yes | 3.44 | 0 |
| DeltaKronecker-all | 5904 | yes | 4.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.59 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 1.56 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 264 |
| speed | 96 |
| cn-block | 33 |
| 204 | 24 |
