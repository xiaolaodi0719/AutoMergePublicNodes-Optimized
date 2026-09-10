# AutoNodes 每日报告

生成时间：2026-09-10 04:12:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87394 |
| 去重后节点数 | 23410 |
| TCP 可达数 | 3000 |
| 真测通过数 | 562 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23410 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 76.5 |
| geo | 1.4 |
| probe | 241.6 |
| real_test | 348.4 |
| tcp | 40.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 68 | 47 | 21 | 69.1% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 163 | 155 | 8 | 95.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 52 | 46 | 6 | 88.5% |
| vless | 468 | 288 | 180 | 61.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 42 |
| speed:TimeoutError | 37 |
| geo:TimeoutError | 34 |
| 204:ProxyError | 26 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 15 |
| cn-block:ClientOSError | 14 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5717 |
| ConnectionRefusedError | 941 |
| gaierror | 339 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | prefer | 297 | 0.902 | 1598 |
| Surfboard-tg-mixed | 0.886 | prefer | 153 | 0.81 | 7448 |
| ermaozi | 0.763 | prefer | 53 | 0.755 | 449 |
| mheidari-all | 0.667 | observe | 90 | 0.589 | 16259 |
| ermaozi-get_subscribe | 0.494 | observe | 17 | 0.529 | 469 |
| DeltaKronecker-all | 0.484 | observe | 139 | 0.403 | 5187 |
| xiaoji235-airport-v2ray-all | 0.471 | observe | 21 | 0.381 | 3508 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 147 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |

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
| ninja-vless | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.381 | 8 | 13 | 21 |
| DeltaKronecker-all | 0.403 | 56 | 83 | 139 |
| ermaozi-get_subscribe | 0.529 | 9 | 8 | 17 |
| mheidari-all | 0.589 | 53 | 37 | 90 |
| ermaozi | 0.755 | 40 | 13 | 53 |
| Surfboard-tg-mixed | 0.81 | 124 | 29 | 153 |
| Au1rxx-base64 | 0.902 | 268 | 29 | 297 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16259 | yes | 6.39 | 0 |
| SoliSpirit-all | 8706 | yes | 3.2 | 0 |
| Epodonios-all | 7910 | yes | 3.71 | 0 |
| Surfboard-tg-mixed | 7448 | yes | 4.85 | 0 |
| barry-far-vless | 6333 | yes | 2.4 | 0 |
| Surfboard-tg-vless | 6108 | yes | 4.52 | 0 |
| DeltaKronecker-all | 5187 | yes | 4.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 1.76 | 0 |
| mahdibland-V2RayAggregator | 4247 | yes | 1.67 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 76 |
| speed | 61 |
| 204 | 46 |
| cn-block | 34 |
