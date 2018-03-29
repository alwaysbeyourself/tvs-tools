# 电视节目单
### trailer.*
#### 问法

#### JSON
```json
{
    //返回码，-1错误，0成功，101频道名为空，102节目名为空
    "resStatus": 0,
    
    //语音播报正文
    "strSpeakText": "10:35 偶像独播剧场:美人心计(39)\n11:24 偶像独播剧场:美人心计(40)\n12:00 中华文明之美\n12:10 午间新闻\n12:30 卫视气象站\n12:33 青春独播剧场:浪花一朵朵(1)\n13:32 青春独播剧场:浪花一朵朵(2)\n14:34 青春独播剧场:浪花一朵朵(3)\n15:36 青春独播剧场:浪花一朵朵(4)\n16:38 青春独播剧场:浪花一朵朵(5)\n17:40 法治中国(3)\n18:30 湖南新闻联播\n18:57 卫视气象站\n19:00 转播中央台新闻联播\n19:32 中华文明之美\n19:40 金鹰独播剧场:人间至味是清欢(10)\n20:49 金鹰独播剧场:人间至味是清欢(11)\n21:58 钻石独播剧场:浪花一朵朵(30)\n22:59 钻石独播剧场:浪花一朵朵(31)\n23:52 我是大美人\n<a href=\"http://m.tvmao.com/program/HUNANTV-HUNANTV1-w1.html\">更多></a>",
    
    //无屏幕端回复语
    "strSpeakTipsText": "下面是湖南卫视今天的电视节目:",
    
    //有屏幕端回复语
    "strTipsText": "下面是湖南卫视今天的电视节目:",
    
    //微信端正文
    "strWxText": "下面是湖南卫视今天的电视节目:\n 10:35 偶像独播剧场:美人心计(39)\n 11:24 偶像独播剧场:美人心计(40)\n 12:00 中华文明之美\n 12:10 午间新闻\n 12:30 卫视气象站\n 12:33 青春独播剧场:浪花一朵朵(1)\n 13:32 青春独播剧场:浪花一朵朵(2)\n 14:34 青春独播剧场:浪花一朵朵(3)\n 15:36 青春独播剧场:浪花一朵朵(4)\n 16:38 青春独播剧场:浪花一朵朵(5)\n 17:40 法治中国(3)\n 18:30 湖南新闻联播\n 18:57 卫视气象站\n 19:00 转播中央台新闻联播\n 19:32 中华文明之美\n 19:40 金鹰独播剧场:人间至味是清欢(10)\n 20:49 金鹰独播剧场:人间至味是清欢(11)\n 21:58 钻石独播剧场:浪花一朵朵(30)\n 22:59 钻石独播剧场:浪花一朵朵(31)\n 23:52 我是大美人\n <a href=\"http://m.tvmao.com/program/HUNANTV-HUNANTV1-w1.html\">更多></a>",
    
    //返回节目单数据
    "vecTvProgramsList": [
        {
            //查看更多url
            "strMoreUrl": "http://m.tvmao.com/program/HUNANTV-HUNANTV1-w1.html",
            
            //电视台节目单
            "vecTvProgramsItem": [
                {
                    //是否正在播 0不是 1正在播
                    "iIsPlaying": 1,
                    
                    //播放电视台名称
                    "strChannel": "湖南卫视",
                    
                    //节目的日期
                    "strDate": "2017-08-21",
                    
                    //电视节目的名称
                    "strTVName": "偶像独播剧场:美人心计(39)",
                    
                    //节目播放时间
                    "strTime": "10:35",
                    
                    //周几的打印串，例如：周一、周天
                    "strWeekPrint": "周一"
                },
                {
                    "iIsPlaying": 0,
                    "strChannel": "湖南卫视",
                    "strDate": "2017-08-21",
                    "strTVName": "我是大美人",
                    "strTime": "23:52",
                    "strWeekPrint": "周一",
                    //播放类型（仅支持电视剧和综艺节目），0未知 1直播 2首播 3重播
                    "iPlayType": 2,
                    //节目封面
                    "strThumb": ""
                }
            ]
        }
    ]
}
```