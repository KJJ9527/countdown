## 倒计时说明

结束时间减去当前时间，再转为天,时,分,秒,设置定时器每1s调用一次

注意防止页面刷新时定时器还需等待1s导致页面效果不好，在定时器前先调用一次函数即可解决