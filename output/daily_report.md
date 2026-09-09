# AutoNodes 每日报告

生成时间：2026-09-09 11:14:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 85046 |
| 去重后节点数 | 22056 |
| TCP 可达数 | 3000 |
| 真测通过数 | 507 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22056 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 92.9 |
| geo | 1.7 |
| probe | 281.8 |
| real_test | 290.1 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 73 | 44 | 29 | 60.3% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 172 | 150 | 22 | 87.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 31 | 14 | 17 | 45.2% |
| vless | 363 | 280 | 83 | 77.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 36 |
| 204:ProxyError | 32 |
| geo:ClientOSError | 28 |
| cn-block:TimeoutError | 20 |
| cn-block:ClientOSError | 11 |
| geo:TimeoutError | 9 |
| 204:ProxyConnectionError | 6 |
| 204:ClientOSError | 5 |
| speed:ProxyError | 2 |
| speed:TimeoutError | 2 |
| speed:ClientOSError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4921 |
| ConnectionRefusedError | 890 |
| gaierror | 368 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | prefer | 249 | 0.896 | 1749 |
| Surfboard-tg-mixed | 0.795 | prefer | 177 | 0.718 | 7479 |
| mheidari-all | 0.786 | prefer | 117 | 0.709 | 16452 |
| DeltaKronecker-all | 0.739 | prefer | 42 | 0.667 | 5187 |
| ermaozi | 0.636 | observe | 53 | 0.623 | 442 |
| ermaozi-get_subscribe | 0.561 | observe | 22 | 0.545 | 473 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 180 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7964 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| ermaozi-get_subscribe | 0.545 | 12 | 10 | 22 |
| ermaozi | 0.623 | 33 | 20 | 53 |
| DeltaKronecker-all | 0.667 | 28 | 14 | 42 |
| mheidari-all | 0.709 | 83 | 34 | 117 |
| Surfboard-tg-mixed | 0.718 | 127 | 50 | 177 |
| Au1rxx-base64 | 0.896 | 223 | 26 | 249 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16452 | yes | 5.4 | 0 |
| SoliSpirit-all | 9095 | yes | 2.68 | 0 |
| Epodonios-all | 7964 | yes | 4.8 | 0 |
| Surfboard-tg-mixed | 7479 | yes | 4.05 | 0 |
| barry-far-vless | 6404 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 6181 | yes | 5.61 | 0 |
| DeltaKronecker-all | 5187 | yes | 4.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 2.08 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 1.72 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 79 |
| geo | 38 |
| cn-block | 32 |
| speed | 5 |
