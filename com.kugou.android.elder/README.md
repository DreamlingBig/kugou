# 酷狗大字版
应用包名：com.android.kugou.elder

### 参数说明

| 参数 | 类型 | 说明 | 备注 |
| :---: | :---: | :---: | :---: |
| appid | int |
| clientver | int | APP版本号 |
| dfid |
| mid |
| userid | int | 酷狗ID(9位) | 如果没有登录为0 |
| token | string | token(61位\|64位) | 如果没有登录为空 |
| uuid | string | uuid(32位) |
| clienttime | int | 秒时间戳(10位) |
| clienttime_ms | int | 毫秒时间戳(13位) |

<summary>接口列表</summary>

- [x] 扫码登录
- [ ] 获取个人信息
- [x] 搜索歌曲
- [x] ~~获取歌曲信息~~
- [x] 点普通歌曲
- [x] 点付费歌曲
