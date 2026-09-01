# AutoNodes 每日报告

生成时间：2026-09-01 16:26:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83812 |
| 去重后节点数 | 24692 |
| TCP 可达数 | 3000 |
| 真测通过数 | 660 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24692 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 41.6 |
| geo | 1.5 |
| probe | 88.7 |
| real_test | 129.9 |
| tcp | 40.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 8 | 8 | 0 | 100.0% |
| shadowsocks | 156 | 143 | 13 | 91.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 36 | 32 | 4 | 88.9% |
| vless | 527 | 451 | 76 | 85.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 20 |
| cn-block:ClientOSError | 15 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 8 |
| cn-block:ProxyError | 4 |
| geo:TimeoutError | 4 |
| speed:ClientOSError | 4 |
| speed:TimeoutError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48555: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5264 |
| ConnectionRefusedError | 968 |
| gaierror | 346 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | prefer | 398 | 0.91 | 1760 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.953 | prefer | 155 | 0.877 | 17557 |
| Surfboard-tg-mixed | 0.869 | prefer | 169 | 0.793 | 6964 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 7294 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7367 |
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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.793 | 134 | 35 | 169 |
| mheidari-all | 0.877 | 136 | 19 | 155 |
| Au1rxx-base64 | 0.91 | 362 | 36 | 398 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17557 | yes | 4.32 | 0 |
| SoliSpirit-all | 7657 | yes | 2.76 | 0 |
| Epodonios-all | 7367 | yes | 1.48 | 0 |
| DeltaKronecker-all | 7294 | yes | 5.77 | 0 |
| Surfboard-tg-mixed | 6964 | yes | 3.58 | 0 |
| barry-far-vless | 6013 | yes | 3.44 | 0 |
| Surfboard-tg-vless | 5838 | yes | 4.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 2.25 | 0 |
| mahdibland-V2RayAggregator | 4013 | yes | 3.01 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 41 |
| 204 | 28 |
| geo | 18 |
| speed | 7 |
| sing-box exited 1 | 1 |
