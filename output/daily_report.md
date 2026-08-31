# AutoNodes 每日报告

生成时间：2026-08-31 22:46:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 78460 |
| 去重后节点数 | 22374 |
| TCP 可达数 | 3000 |
| 真测通过数 | 637 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22374 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 42.1 |
| geo | 1.5 |
| probe | 83.7 |
| real_test | 127.7 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 12 | 11 | 52.2% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 171 | 164 | 7 | 95.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 28 | 27 | 1 | 96.4% |
| vless | 495 | 411 | 84 | 83.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 16 |
| cn-block:ClientOSError | 13 |
| 204:ProxyConnectionError | 12 |
| geo:ClientOSError | 10 |
| speed:TimeoutError | 10 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4931 |
| ConnectionRefusedError | 925 |
| gaierror | 323 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.955 | prefer | 38 | 0.895 | 5904 |
| Au1rxx-base64 | 0.95 | prefer | 285 | 0.905 | 1182 |
| mheidari-all | 0.926 | prefer | 180 | 0.85 | 14929 |
| Surfboard-tg-mixed | 0.913 | prefer | 214 | 0.836 | 7016 |
| zhangkai | 0.544 | observe | 24 | 0.542 | 144 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7323 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7470 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5879 |

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
| zhangkai | 0.542 | 13 | 11 | 24 |
| Surfboard-tg-mixed | 0.836 | 179 | 35 | 214 |
| mheidari-all | 0.85 | 153 | 27 | 180 |
| DeltaKronecker-all | 0.895 | 34 | 4 | 38 |
| Au1rxx-base64 | 0.905 | 258 | 27 | 285 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14929 | yes | 3.55 | 0 |
| SoliSpirit-all | 7470 | yes | 3.56 | 0 |
| Epodonios-all | 7323 | yes | 3.85 | 0 |
| Surfboard-tg-mixed | 7016 | yes | 2.88 | 0 |
| barry-far-vless | 6031 | yes | 0.56 | 0 |
| DeltaKronecker-all | 5904 | yes | 4.41 | 0 |
| Surfboard-tg-vless | 5879 | yes | 2.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.57 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 1.01 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 40 |
| cn-block | 32 |
| speed | 18 |
| geo | 15 |
