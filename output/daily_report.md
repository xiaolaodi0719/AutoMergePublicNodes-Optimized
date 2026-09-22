# AutoNodes 每日报告

生成时间：2026-09-22 16:48:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84228 |
| 去重后节点数 | 23642 |
| TCP 可达数 | 3000 |
| 真测通过数 | 419 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23642 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 81.0 |
| geo | 1.6 |
| probe | 214.7 |
| real_test | 169.8 |
| tcp | 39.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 31 | 22 | 9 | 71.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 161 | 148 | 13 | 91.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 21 | 15 | 6 | 71.4% |
| vless | 328 | 218 | 110 | 66.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 35 |
| geo:ClientOSError | 33 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 11 |
| speed:TimeoutError | 11 |
| cn-block:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5567 |
| ConnectionRefusedError | 834 |
| gaierror | 253 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | prefer | 299 | 0.866 | 1703 |
| mheidari-all | 0.905 | prefer | 38 | 0.842 | 16289 |
| DeltaKronecker-all | 0.858 | prefer | 34 | 0.794 | 6324 |
| ermaozi | 0.737 | prefer | 27 | 0.741 | 325 |
| Surfboard-tg-mixed | 0.586 | observe | 152 | 0.507 | 7076 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 132 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 4915 |
| Epodonios-all | 0.255 | observe | 0 | None | 7611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.507 | 77 | 75 | 152 |
| ermaozi | 0.741 | 20 | 7 | 27 |
| DeltaKronecker-all | 0.794 | 27 | 7 | 34 |
| mheidari-all | 0.842 | 32 | 6 | 38 |
| Au1rxx-base64 | 0.866 | 259 | 40 | 299 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16289 | yes | 4.93 | 0 |
| SoliSpirit-all | 9154 | yes | 2.28 | 0 |
| Epodonios-all | 7611 | yes | 5.16 | 0 |
| Surfboard-tg-mixed | 7076 | yes | 3.66 | 0 |
| DeltaKronecker-all | 6324 | yes | 4.49 | 0 |
| barry-far-vless | 6010 | yes | 0.93 | 0 |
| Surfboard-tg-vless | 5712 | yes | 3.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 1.65 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 48 |
| geo | 39 |
| 204 | 37 |
| cn-block | 16 |
