fork from [this](http://github.com/Urinx/WeixinBot) and modified some process to achieve my purpose.

New features:

1. Rollback spy

Auto watching rollback msg. Once one man rollback a plaintext, just forward the latest plaintext from the unlucky man to your filetransfer(you can also modify it to change the forward destination even send a same plaintext msg to embarass your friends :)).

2. Auto care boring friend

With spying rollback msg for devil purpose, this robot also can be warming~
Once your friend have `我` and `无聊` in one plaintext msg(whether in private or group), a chat robot establish and send him a warming up msg `你狠无聊啊，刚好我也很无聊，我们聊聊呗~`. Then, every plaintext from this friend will send to a chat robot and response to your friend. The api is from 图灵机器人 and you can apply your own api key. Furthermore, the chat robot perform better in chinese conversation and have more request chance per day than 小黄鸡.


