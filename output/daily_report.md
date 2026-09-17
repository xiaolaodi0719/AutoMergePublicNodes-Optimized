# AutoNodes 每日报告

生成时间：2026-09-17 04:34:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89183 |
| 去重后节点数 | 24536 |
| TCP 可达数 | 3000 |
| 真测通过数 | 530 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24536 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 79.8 |
| geo | 1.4 |
| probe | 359.4 |
| real_test | 376.5 |
| tcp | 41.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 34 | 25 | 9 | 73.5% |
| hysteria2 | 24 | 21 | 3 | 87.5% |
| shadowsocks | 184 | 167 | 17 | 90.8% |
| socks | 7 | 6 | 1 | 85.7% |
| trojan | 35 | 28 | 7 | 80.0% |
| vless | 503 | 279 | 224 | 55.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 69 |
| speed:TimeoutError | 46 |
| geo:ClientOSError | 44 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 19 |
| cn-block:ClientOSError | 18 |
| 204:TimeoutError | 15 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5616 |
| ConnectionRefusedError | 928 |
| gaierror | 433 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.939 | prefer | 278 | 0.878 | 1590 |
| ermaozi | 0.785 | prefer | 24 | 0.792 | 396 |
| Surfboard-tg-mixed | 0.713 | prefer | 257 | 0.634 | 7408 |
| mheidari-all | 0.547 | observe | 165 | 0.467 | 17792 |
| DeltaKronecker-all | 0.438 | observe | 51 | 0.353 | 6081 |
| ermaozi-get_subscribe | 0.411 | observe | 10 | 0.6 | 431 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4234 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 130 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.353 | 18 | 33 | 51 |
| mheidari-all | 0.467 | 77 | 88 | 165 |
| ermaozi-get_subscribe | 0.6 | 6 | 4 | 10 |
| Surfboard-tg-mixed | 0.634 | 163 | 94 | 257 |
| ermaozi | 0.792 | 19 | 5 | 24 |
| Au1rxx-base64 | 0.878 | 244 | 34 | 278 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17792 | yes | 4.38 | 0 |
| SoliSpirit-all | 9115 | yes | 1.82 | 0 |
| Epodonios-all | 7930 | yes | 4.72 | 0 |
| Surfboard-tg-mixed | 7408 | yes | 3.22 | 0 |
| barry-far-vless | 6194 | yes | 1.59 | 0 |
| DeltaKronecker-all | 6081 | yes | 3.15 | 0 |
| Surfboard-tg-vless | 5925 | yes | 2.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4234 | yes | 1.9 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 114 |
| speed | 71 |
| cn-block | 41 |
| 204 | 35 |
