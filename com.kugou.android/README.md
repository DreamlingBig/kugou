# 酷狗音乐
应用包名：com.android.kugou

### 参数说明

| 参数 | 类型 | 默认 | 说明 | 备注 |
| :---: | :---: | :---: | :---: | :---: |
| appid | int |
| clientver | int |  | APP版本号 |
| dfid |
| mid |
| userid | int | 0 | 酷狗ID(9位) | 如果没有登录为0 |
| token | string |  | token(61位\|64位) | 如果没有登录为空 |
| uuid | string |  | uuid(32位) |
| clienttime | int |  | 秒时间戳(10位) |
| clienttime_ms | int |  | 毫秒时间戳(13位) |

<summary>接口列表</summary>

- [x] ~~账密登录~~
- [ ] 短信登录
- [x] 刷新token
- [ ] 获取个人信息
- [x] 搜索歌曲
- [x] 获取歌曲信息
- [x] 点普通歌曲
- [x] 点会员歌曲(需要登录)
- [x] 看广告领会员
