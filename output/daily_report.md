# AutoNodes 每日报告

生成时间：2026-09-11 04:15:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87168 |
| 去重后节点数 | 24439 |
| TCP 可达数 | 3000 |
| 真测通过数 | 586 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24439 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 84.1 |
| geo | 1.4 |
| probe | 361.1 |
| real_test | 545.9 |
| tcp | 42.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 42 | 27 | 15 | 64.3% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 166 | 159 | 7 | 95.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 50 | 26 | 24 | 52.0% |
| vless | 759 | 353 | 406 | 46.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 180 |
| speed:ClientOSError | 88 |
| geo:ClientOSError | 74 |
| speed:TimeoutError | 38 |
| cn-block:TimeoutError | 25 |
| 204:ProxyError | 22 |
| 204:TimeoutError | 14 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5763 |
| ConnectionRefusedError | 976 |
| gaierror | 423 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 27 | 0.963 | 15718 |
| Au1rxx-base64 | 0.881 | prefer | 335 | 0.818 | 1613 |
| Surfboard-tg-mixed | 0.787 | prefer | 165 | 0.709 | 7301 |
| ermaozi | 0.684 | observe | 25 | 0.68 | 431 |
| ermaozi-get_subscribe | 0.502 | observe | 16 | 0.562 | 461 |
| xiaoji235-airport-v2ray-all | 0.382 | observe | 14 | 0.357 | 3508 |
| DeltaKronecker-all | 0.381 | observe | 456 | 0.3 | 5853 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 168 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.3 | 137 | 319 | 456 |
| xiaoji235-airport-v2ray-all | 0.357 | 5 | 9 | 14 |
| ermaozi-get_subscribe | 0.562 | 9 | 7 | 16 |
| ermaozi | 0.68 | 17 | 8 | 25 |
| Surfboard-tg-mixed | 0.709 | 117 | 48 | 165 |
| Au1rxx-base64 | 0.818 | 274 | 61 | 335 |
| mheidari-all | 0.963 | 26 | 1 | 27 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15718 | yes | 3.17 | 0 |
| SoliSpirit-all | 8799 | yes | 4.35 | 0 |
| Epodonios-all | 7793 | yes | 3.4 | 0 |
| Surfboard-tg-mixed | 7301 | yes | 3.82 | 0 |
| barry-far-vless | 6145 | yes | 2.54 | 0 |
| Surfboard-tg-vless | 5909 | yes | 2.7 | 0 |
| DeltaKronecker-all | 5853 | yes | 4.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 2.23 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 0.2 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 255 |
| speed | 127 |
| 204 | 38 |
| cn-block | 36 |
