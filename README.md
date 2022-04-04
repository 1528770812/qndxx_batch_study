# qndxx_batch_study

使用方法：
1. 进入广东共青团，点击智慧团建，点击团员报道，点击认证资料，再点击生成电子团员证，再点击最下方生成按钮。在团员证页面复制链接（ 应为：https://tuan.12355.net/wechat/view/information/member_certification_generated.html?memberId=xxxxxx&showMemberAdditionNames=&showMemberRewardIds=&isShowAllFee=true ）
将其中xxxxxx就是接下来将要用到的USERID
2. 点击这个网页右上角的`Fork`
3. 设置仓库的 Actions Secrets <sup>[如何设置？](./how-to-enable-actions/#添加-Secrets)</sup>  
添加用户名 `USERID`
   | Name | Value |
   | :---: | :---: |
   | USERID | 第1步获得的xxxxxx |
4. 开启 GitHub Actions <sup>[如何开启？](./how-to-enable-actions/#启用-Actions)</sup>
5. 尝试点击Run workflow，运行成功后在青年大学习页面查看学习记录
6. 每三天早上 7:00 <sup>23:00 UTC</sup> 定时自动运行
