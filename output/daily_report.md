# AutoNodes 每日报告

生成时间：2026-09-05 10:23:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83253 |
| 去重后节点数 | 22135 |
| TCP 可达数 | 3000 |
| 真测通过数 | 509 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22135 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 35.8 |
| geo | 1.4 |
| probe | 84.0 |
| real_test | 106.7 |
| tcp | 36.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 165 | 155 | 10 | 93.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 24 | 16 | 8 | 66.7% |
| vless | 376 | 293 | 83 | 77.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| geo:ClientOSError | 22 |
| cn-block:TimeoutError | 14 |
| 204:ProxyError | 13 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 7 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4546 |
| ConnectionRefusedError | 891 |
| gaierror | 371 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Au1rxx-base64 | 0.959 | prefer | 271 | 0.889 | 1813 |
| Surfboard-tg-mixed | 0.866 | prefer | 180 | 0.789 | 7332 |
| mheidari-all | 0.862 | prefer | 108 | 0.787 | 15508 |
| DeltaKronecker-all | 0.645 | observe | 21 | 0.571 | 6212 |
| tg-oneclickvpnkeys | 0.482 | observe | 6 | 1.0 | 118 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8561 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.571 | 12 | 9 | 21 |
| mheidari-all | 0.787 | 85 | 23 | 108 |
| Surfboard-tg-mixed | 0.789 | 142 | 38 | 180 |
| Au1rxx-base64 | 0.889 | 241 | 30 | 271 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15508 | yes | 5.03 | 0 |
| SoliSpirit-all | 8561 | yes | 4.02 | 0 |
| Epodonios-all | 7793 | yes | 5.26 | 0 |
| Surfboard-tg-mixed | 7332 | yes | 3.75 | 0 |
| barry-far-vless | 6302 | yes | 2.77 | 0 |
| DeltaKronecker-all | 6212 | yes | 5.86 | 0 |
| Surfboard-tg-vless | 6108 | yes | 4.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 2.42 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 0.28 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| geo | 26 |
| cn-block | 24 |
| speed | 12 |
