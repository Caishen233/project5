# project5


功能：
玩家分数从0-4000不断上涨，赛季刷新时不会掉分，且没有奖励
玩家4000分以上时，每200分可领取一次奖励，奖励内容为100金币，但整千时不能领取奖励，且每1000分就达到一个大段位，上限为6000分；
玩家4000分以上时，在赛季刷新时4000分以上分数会被砍掉一半，新的赛季可重新
爬取段位，且4000分以上的奖励可重新领取。

包括三个脚本
CoinManager  单例模式控制管理顶部金币总数
RewardPerfab 管理奖励预制件的脚本
RewardUIManager 全局的控制脚本