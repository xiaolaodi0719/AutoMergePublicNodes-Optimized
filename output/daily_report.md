# AutoNodes 每日报告

生成时间：2026-09-07 21:26:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 90115 |
| 去重后节点数 | 25048 |
| TCP 可达数 | 3000 |
| 真测通过数 | 563 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25048 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 47.5 |
| geo | 1.4 |
| probe | 86.7 |
| real_test | 116.4 |
| tcp | 41.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 23 | 16 | 7 | 69.6% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 159 | 148 | 11 | 93.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 27 | 16 | 11 | 59.3% |
| vless | 435 | 355 | 80 | 81.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 28 |
| geo:ClientOSError | 20 |
| 204:TimeoutError | 19 |
| cn-block:ClientOSError | 13 |
| 204:ProxyConnectionError | 7 |
| speed:ClientOSError | 6 |
| geo:TimeoutError | 6 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5495 |
| ConnectionRefusedError | 1003 |
| gaierror | 371 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 371 | 0.946 | 1688 |
| DeltaKronecker-all | 0.898 | prefer | 20 | 0.85 | 6417 |
| mheidari-all | 0.819 | prefer | 86 | 0.744 | 16413 |
| Surfboard-tg-mixed | 0.802 | prefer | 142 | 0.725 | 7444 |
| zhangkai | 0.686 | observe | 23 | 0.696 | 144 |
| xiaoji235-airport-v2ray-all | 0.45 | observe | 25 | 0.36 | 5750 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 196 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7899 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| xiaoji235-airport-v2ray-all | 0.36 | 9 | 16 | 25 |
| zhangkai | 0.696 | 16 | 7 | 23 |
| Surfboard-tg-mixed | 0.725 | 103 | 39 | 142 |
| mheidari-all | 0.744 | 64 | 22 | 86 |
| DeltaKronecker-all | 0.85 | 17 | 3 | 20 |
| Au1rxx-base64 | 0.946 | 351 | 20 | 371 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16413 | yes | 4.02 | 0 |
| SoliSpirit-all | 8444 | yes | 3.24 | 0 |
| Epodonios-all | 7899 | yes | 2.83 | 0 |
| Surfboard-tg-mixed | 7444 | yes | 4.85 | 0 |
| DeltaKronecker-all | 6417 | yes | 4.18 | 0 |
| barry-far-vless | 6394 | yes | 2.19 | 0 |
| Surfboard-tg-vless | 6179 | yes | 3.13 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 4.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 1.96 | 0 |
| mahdibland-V2RayAggregator | 4218 | yes | 0.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 42 |
| 204 | 30 |
| geo | 27 |
| speed | 11 |
