# AutoNodes 每日报告

生成时间：2026-09-04 20:39:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84231 |
| 去重后节点数 | 23539 |
| TCP 可达数 | 3000 |
| 真测通过数 | 596 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23539 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 42.7 |
| geo | 1.3 |
| probe | 67.6 |
| real_test | 129.4 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 29 | 29 | 0 | 100.0% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 173 | 154 | 19 | 89.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 30 | 28 | 2 | 93.3% |
| vless | 459 | 368 | 91 | 80.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 16 |
| geo:TimeoutError | 15 |
| cn-block:ClientOSError | 13 |
| 204:TimeoutError | 12 |
| speed:TimeoutError | 11 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 8 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 5 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5256 |
| ConnectionRefusedError | 881 |
| gaierror | 260 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Au1rxx-base64 | 0.946 | prefer | 337 | 0.878 | 1756 |
| mheidari-all | 0.904 | prefer | 117 | 0.829 | 16096 |
| DeltaKronecker-all | 0.869 | prefer | 36 | 0.806 | 7089 |
| Surfboard-tg-mixed | 0.845 | prefer | 185 | 0.768 | 7342 |
| tg-oneclickvpnkeys | 0.589 | observe | 9 | 1.0 | 118 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| Epodonios-all | 0.255 | observe | 0 | None | 7798 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8118 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.768 | 142 | 43 | 185 |
| DeltaKronecker-all | 0.806 | 29 | 7 | 36 |
| mheidari-all | 0.829 | 97 | 20 | 117 |
| Au1rxx-base64 | 0.878 | 296 | 41 | 337 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 9 | 0 | 9 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16096 | yes | 2.85 | 0 |
| SoliSpirit-all | 8118 | yes | 1.42 | 0 |
| Epodonios-all | 7798 | yes | 1.04 | 0 |
| Surfboard-tg-mixed | 7342 | yes | 0.21 | 0 |
| DeltaKronecker-all | 7089 | yes | 2.93 | 0 |
| barry-far-vless | 6376 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 6159 | yes | 2.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 1.53 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 0.89 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 36 |
| geo | 31 |
| 204 | 25 |
| speed | 21 |
