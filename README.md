LNURL 文档
===============

这些都是描述可以在 LNURL 框架下实现的每一小部分协议的单独文档。不同的钱包和服务可以实现不同的协议集。

| Number   |描述| Wallets (in alphabetical order) |
|----------|-------------------------------------------------------------|---------|
| [01][01] |基本 LNURL 编码和解码。| _all the ones listed below_ |
| [02][02] | `channelRequest` base spec.                                 |[Satoshis 平衡][BOS]，[BitBanana][BitBanana]，[Blixt][Blixt]，[布利兹][布利兹]，[Cliché][Cliche]，[OBW][OBW]，[Zap Android][Zap]，[Zap Desktop][Zap]，[宙斯][宙斯]|
| [03][03] | `withdrawRequest` base spec.                                |[Alby][Alby]，[Balance of Satoshis][BOS]，[BitBanana][BitBanana]，[BLIXT][BLIXT]，[BlueWallet][BlueWallet]，[Breez]，[CLAMS]，〔 CoinCorner 〕[CoinCorner 〕，〔 Coinos 〕[Coinos 〕，〔 Fountain 〕[Fountain]，[LightningTipBot][LTB]，[Mash][Mash]，[MuUN][MuUN]，[Phoenix][Phoenix]、[Pouch.pH][PouchPh]、[ShockWallet][ShockWallet]、[OBW][OBW]、[OneKey][OneKey]、[ThunderHub][ThunderHub]、[小智的钱包][WOS]、[ZAP 桌面][ZAP]，[ZAP IOS][Zap]，[ZBD 不和谐][zbd]，[zbd 扩展][zbd]，[zbd 电报][zBD]，[西庇太][zBD]，[宙斯][Zeus]|
| [04][04] | Auth base spec.                                             |[Alby][Alby]，[Balance of Satoshis][Bos]，[Bitbanana][Bitbanana]，[BLIXT][BLIXT]，（Breez） [Breez]，（BlueWallet） [BlueWallet]，[CLAMS][CLAMS]，[COINOS][COINOS]，[GEYSER]，[LIFPAY][LIFPAY[Phoenix][Phoenix]，[Seedauth][Seedauth]，[SeedAuthExtension][SAE]，[OBW][OBW]，[OneKey][OneKey]，[Sparrow Wallet][Sparrow]，[ThunderHub]，[Zap Desktop][Zap]，「Zeus」[Zeus]|
| [05][05] | BIP32-based seed generation for auth protocol.              |[ALBY][ALBY]，[COINOS][COINOS]，[OBW][OBW]，[ONEKEY][ONEKEY]，[凤凰][凤凰]|
| [06][06] | `payRequest` base spec.                                     |[Alby][Alby]，[Balance of Satoshis][BOS]，[BIPA][BIPA]，[bitBanana][bitBanana]、[blixt][blixt]、[blueWallet][blueWallet]、[breez][breez]、[btcpayserver][btcp]、[clams]、[cliché][cliche]、[coincorner]，[coinos][[ELECTRUM][ELECTRUM]，[FOUNTAIN][FOUNTAIN]，[GALOY][GALOY]，[GEYSER][GEYSER]，[LIFPAY]，[LNBITS]，[lnlink]，[lnpay.Co][lnpay]，〔 Lightningtipbot 〕[LTB]，〔 MACHANK[OneKey][OneKey]，[Phoenix][Phoenix]，[Pouch.pH][Pouchph]，[River][River]，[河闪电][RiverLightning]，[河钱包][ShockWallet]、[ThunderHub][ThunderHub]、[小智钱包][WOS]、[Zap Android][Zap]、[ZBD Discord][ZBD]、[ZBD Extension][[ZBD 电报][ZBD]，[西庇太][ZBD]，[宙斯][宙斯]|
| [07][07] | `hostedChannelRequest` 基本规格| [OBW][obw] |
| [08][08] |速度快 `withdrawRequest`。| [cliché][cliche], [OBW][obw], [ZBD Extension][zbd] |
| [09][09] | `successAction` field for `payRequest`.                     |[ALBY][ALBY]，[BITBANANA][BITBANANA]，[BLIXT][BLIXT]，[BLUEWALLET][BLUEWALLET]，[BREEZ]，[CLAMS]，[CLICHE]，〔 COINOS 〕[COINOS 〕，〔 FOUNTAIN 〕[FOUNTAIN 〕，〔 [Phoenix][Phoenix]，[ShockWallet][ShockWallet]，[OBW][OBW]，[OneKey][OneKey]，[ThunderHub][ThunderHub]，[Satoshi 的钱包][WOS]、[Zap Android][Zap]、[zbd Discord][zbd]、[zbd Extension][zbd]、〔 zbd Telegram 〕 [zbd 〕、〔 Zebedee[宙斯][宙斯]|
| [10][10] | `aes` success action in `payRequest`.                       |[ALBY][ALBY]，[BITBANANA][BITBANANA]，[BLIXT][BLIXT]，[BLUEWALLET][BLUEWALLET]，[BREEZ]，[CLAMS]，[CLICHE]、[COINOS]、[LNBITS][LNBITS][ThunderHub][ThunderHub]，[小智的钱包][WOS]，[Zap Android][Zap]，[宙斯][宙斯]|
| [11][11] |一次性和可储存 `payRequest` 的。| [Blixt][blixt], [OBW][obw], [ZBD Extension][zbd] |
| [12][12] | Comments in `payRequest`.                                   |[ALBY][ALBY]，[BIPA][BIPA]，[BITBANANA][BITBANANA]，[BLIXT][BLIXT]，[BLUEWALLET]，[BREEZ]，[CLAMS]，[FOUNTAIN]，〔 LIFPAY 〕[LIFPAY 〕，〔 LNB[Phoenix][Phoenix]，[Stacker.News][Stacker.News]，[ThunderHub][ThunderHub]，[ZBD Discord][ZBD]，[ZBD Extension][ZBD]，[ZBD Telegram][zbd]，[西庇太][zbd]，[宙斯][宙斯]|
| [13][13] | `signMessage`-based seed generation for auth protocol.      |[Alby][Alby]，[Satoshis 的平衡][Bos]，[Bitbanana][Bitbanana]，[Blixt][Blixt]，[蛤][蛤]，[宙斯][宙斯]|
| [14][14] | `balanceCheck`：可重复使用 `withdrawRequest`| [Alby][alby], [Blixt][blixt], [LNbits][lnbits], |
| [15][15] | `balanceNotify`：加快提款流程的服务。| [LNbits][lnbits] |
| [16][16] | Paying to static internet identifiers.                      |[ALBY][ALBY]，[BIPA][BIPA]，[SATOSHIS 平衡][BOS]，[BITBANANA][BITBANANA]，（BLIXT） [BLIXT]，（BTCPAYSERVER） [BTCP]，[CLAMS]，[CLICHE][CLICHE]，[COINCORNER][COINCORNER]，[COINOS][lnbits][lnbits]，[lnlink][lnlink]，[LightningTipBot][LTB]，[Machankura][Machankura]，（MASH） [MASH]，（OBW） [OBW]，[ONEKEY]，[Phoenix]，[POUCH.pH][POUCHPH]，[RIVER][RIVER]，[河闪电 [zap 安卓][zap]，[zbd 不和][zbd]，[zbd 扩展][ZBD]，[ZBD 电报][ZBD]，[西庇太][Zbd]，[宙斯][Zeus]|
| [17][17] | Scheme prefixes and raw (non bech32-encoded) URLs.          |[Alby][Alby]，[Bitbanana][Bitbanana]，[Blixt][Blixt]，[btcpayserver][btcp]，（clams） [clams]，（cliché） [cliche]，[CoinCorner][CoinCorner]，[LifPay]，[Mash]，〔 OneKey 〕，〔 ZBD Discord 〕〔 ZBD 〕，〔 ZBD| [Wallet of Satoshi][wos] |
| [18][18] | Payer identity in `payRequest` protocol.                    |[ALBY][ALBY]，[BITBANANA][BITBANANA]，[BLIXT][BLIXT]，[CLICHE][CLICHE]，[OBW]，[ZBD Discord][ZBD]，[ZBD Telegram][zbd]|
| [19][19] | Pay link discoverable from withdraw link.                   |[Blixt][Blixt]，[CoinCorner][CoinCorner]，[OBW][OBW]，[LnBits][LnBits]|
| [20][20] | Long payment description for pay protocol.                  |[ALBY][ALBY]，[BITBANANA][BITBANANA]，[BLIXT][BLIXT]，[CLAMS][CLAMS]，[Cliché][Cliche]，[MASH]，[ONEKEY]，[PHOENIX][PHOENIX]|

[alby]: https://github.com/getAlby/lightning-browser-extension
[bipa]: https://bipa.app
[bitbanana]: https://bitbanana.app
[bos]: https://github.com/alexbosworth/balanceofsatoshis
[blixt]: https://blixtwallet.github.io
[bluewallet]: https://bluewallet.io
[btcp]: https://btcpayserver.org
[breez]: https://breez.technology
[clams]: https://clams.tech
[cliche]: https://github.com/fiatjaf/cliche
[coincorner]: https://coincorner.com
[coinos]: https://coinos.io
[electrum]: https://electrum.org
[fountain]: https://fountain.fm
[galoy]: https://galoy.io
[geyser]: https://geyser.fund
[lifpay]: https://lifpay.me
[lnbits]: https://lnbits.com
[lnlink]: https://lnlink.app
[lnpay]: https://lnpay.co
[ltb]: https://ln.tips
[machankura]: https://8333.mobi
[mash]: https://mash.com/consumer-experience/
[muun]: https://muun.com
[OBW]: https://darthcoin.substack.com/p/obw-open-bitcoin-wallet
[OneKey]: https://onekey.so
[phoenix]: https://phoenix.acinq.co
[pouchlite]: https://pouch.ph/lite
[pouchph]: https://pouch.ph
[river]: https://river.com
[riverlightning]: https://rls.dev
[sae]: https://github.com/pseudozach/seedauthextension
[sbw]: https://lightning-wallet.com
[seedauth]: https://seedauth.etleneum.com/
[shockwallet]: https://shockwallet.app
[sparrow]: https://sparrowwallet.com/
[Stacker.news]：https://stacker.news/
[thunderhub]: https://www.thunderhub.io
[wos]: https://www.walletofsatoshi.com
[zap]: https://zaphq.io/
[zbd]: https://zebedee.io/wallet
[zeus]: https://zeusln.app

服务
--------

|名字| LUDs                                                           |
| ----                                                                                                | ----                                                           |
|[Azteco](https://azte.co/)| [01][01] [03][03]                                              |
|[Bipa](https://bipa.app)| [01][01] [06][06] [12][12] [16][16]                                              |
|[BTC 起源故事](https://btcoriginstories.com/)| [01][01] [06][06]                                              |
|[比特币反弹](https://thndr.games/)| [01][01] [03][03] [08][08]                                     |
|[Bitrefill](https://bitrefill.com/)| [01][01] [02][02] [06][06] [16][16]                            |
|[Blocktank](https://synonym.to/blocktank/)| [01][01] [02][02]                                              |
|[牛市比特币](https://www.bullbitcoin.com/)| [01][01] [03][03]                                              |
|[CoinCorner](https://www.coincorner.com)| [01][01] [03][03] [06][06] [16][16] [17][17] [19][19]          |
|[喷泉播客](https://fountain.fm)| [01][01] [03][03] [06][06] [09][09] [12][12] [16][16]          |
|[Galoy](https://galoy.io/)| [01][01] [06][06]                                              |
|[Geyser](https://geyser.fund/)| [01][01] [04][04] [06][06]                                     |
|[各付各的](https://goingdutch.pm/)| [01][01] [03][03] [06][06]                                     |
|[HangarSix](https://www.hangarsixgaming.com/)| [01][01] [03][03]                                              |
|[IBEXHub](https://ibexmercado.gitbook.io/ibex-hub-api/reference/api-reference)| [01][01] [03][03] [06][06] [16][16]                            |
|[Infuse](https://zebedee.io/infuse/)| [01][01] [03][03]                                              |
|[Kollider](https://kollider.xyz/)| [01][01] [03][03] [04][04]                                     |
|[LifPay](https://lifpay.me)| [01][01] [03][03] [04][04] [06][06] [09][09] [12][12] [16][16] [17][17]                   |
|[LNBIG](https://lnbig.com/)| [01][01] [02][02]                                              |
|[ln.cash](https://ln.cash)| [01][01] [03][03]                                              |
|[LNMarkets](https://lnmarkets.com/)| [01][01] [03][03] [04][04] [06][06] [16][16]                   |
|[LNPay.co](https://lnpay.co)| [01][01] [03][03] [06][06] [14][14]                            |
|[LNbits.com](https://lnbits.com/)| [01][01] [03][03] [04][04] [14][14] [15][15]                   |
|[闪电.视频](https://lightning.video/)| [01][01] [04][04] [06][06] [16][16]                            |
|[闪电礼物](https://lightning.gifts/)| [01][01] [03][03] [06][06] [12][12]                            |
|[闪电机器人](https://ln.tips/)| [01][01] [03][03] [06][06] [09][09] [12][12] [16][16] [18][18] |
|[lnurl-pay 聊天](https://chat.blixtwallet.com/)| [01][01] [06][06] [11][11] [12][12] [18][18]                   |
|[Loft](https://loft.trade/)| [01][01] [03][03] [04][04]                                     |
|[Machankura](https://8333.mobi)| [01][01] [06][06] [16][16]                                     |
|[Mash](https://mash.com)| [01][01] [03][03] [06][06] [16][16]                            |
|[微型枪骑兵](https://microlancer.io/)| [01][01] [03][03] [14][14]                                     |
|[OpenNode](https://developers.opennode.com/reference/initiate-lnurl-withdrawal)| [01][01] [03][03]                                              |
|[Paywall](https://paywall.link)| [01][01] [03][03]                                              |
|[河流闪电](https://rls.dev)| [01][01] [03][03] [06][06] [16][16] [17][17]                   |
|[Sats4Likes](https://sats4likes.com/)| [01][01] [03][03] [14][14] [16][16]                            |
|[Satsback.com](https://satsback.com)| [01][01] [03][03] [06][06] [16][16]                            |
|[sms4sats](https://sms4sats.com/)| [01][01] [03][03]                                              |
|[南方交易所](https://www.southxchange.com/)| [01][01] [03][03]                                              |
|[斯塔克新闻](https://stacker.news/)| [01][01] [03][03] [04][04] [06][06] [12][12] [16][16]          |
|[冲浪城市停车场](https://surfcity.app/)| [01][01] [03][03]                                              |
|[命运之轮](https://fortune.lngames.net)| [01][01] [03][03] [04][04]                                     |
|[bridgeaddr](https://bridgeaddr.fiatjaf.com)| [01][01] [06][06] [09][09] [12][12] [16][16]                   |
|[coinos](https://coinos.io/)| [01][01] [03][03] [04][04] [06][06] [16][16]                   |
|[lnshort.it](https://lnshort.it/)| [01][01] [04][04] [06][06]                                     |
|[LNSMS.世界](https://lnsms.world/)| [01][01] [06][04] [11][11] [12][12] [16][16]                   |
|[lnurl-pay.me](https://lnurl-pay.me)| [01][01] [06][06] [16][16]                                     |
|[pollofeed](https://pollofeed.com)| [01][01] [06][06] [16][16]                                     |
|[zbd.gg](https://zbd.gg/)| [01][01] [03][03] [06][06] [09][09] [12][12] [16][16]          |
|[Lnurlpay.com](https://lnurlpay.com/)| [01][01] [06][06] [12][12] [16][16]                            |
|[零费路由](https://zerofeerouting.com/mobile-wallets/)| [01][01] [02][02]                                              |
|[罢工.军队](https://strike.army/)| [01][01] [03][03] [06][06] [12][12] [16][16]                   |

[rtb]: https://play.google.com/store/apps/details?id=com.pseudozach.rewardstobitcoin

自我托管
-----------

|名字| LUDs                                         |
| ----                                                                                       | ----                                         |
|[无地址](https://github.com/futurepaul/addressless)| [01][01] [06][06] [09][09] [16][16]          |
|[Bleskomat](https://github.com/samotari/bleskomat)| [01][01] [03][03]                            |
|[BtcPayServer](https://btcpayserver.org/)| [01][01] [06][06] [16][16] [17][17]          |
|[Citadel 比特币节点](https://github.com/runcitadel)| [01][01] [06][06] [16][16]                   |
|[Cypherapp](https://github.com/SatoshiPortal/lnurl_cypherapp)| [01][01] [03][03]                            |
|[lnurl 守护进程](https://github.com/yanascz/lnurld)| [01][01] [06][06] [09][09] [12][12] [16][16] |
|[LNURLPoS](https://github.com/arcbtc/LNURLPoS)| [01][01] [06][06] [09][09]                   |
|[LNURLp](https://github.com/lnbits/lnbits/tree/master/lnbits/extensions/lnurlp)| [01][01] [06][06] [12][12]                   |
|[LNURLw](https://github.com/lnbits/lnbits/tree/master/lnbits/extensions/withdraw)| [01][01] [03][03]                            |
|[LNbits.com](https://github.com/fiatjaf/lnbits)| [01][01] [03][03] [04][04] [14][14] [15][15] |
|[闪电 ATM](https://github.com/21isenough/LightningATM)| [01][01] [03][03]                            |
|[NextPay](https://github.com/apotdevin/NextPay)| [01][01] [06][06] [16][16]                   |
|[离线商店](https://github.com/lnbits/lnbits/tree/master/lnbits/extensions/offlineshop)| [01][01] [06][06] [09][09]                   |
|[Satdress](https://github.com/fiatjaf/satdress)| [01][01] [06][06] [09][09] [16][16]          |
|[拖缆副驾驶](https://github.com/lnbits/lnbits/tree/master/lnbits/extensions/copilot)| [01][01] [06][06] [12][12]                   |
|[GO-主机-LNADDR](https://github.com/hieblmi/go-host-lnaddr)| [01][01] [06][06] [09][09] [16][16]          |
|[ligess](https://github.com/Dolu89/ligess/)| [01][01] [06][06] [09][09] [16][16]          |
|[lnme](https://github.com/bumi/lnme)| [01][01] [06][06] [09][09] [16][16]          |

图书馆
---------

| Name                                                  |卢兹|
| ----                                                  | ----                                                                                                                                                     |
| [IMMORTAN](https://github.com/fiatjaf/IMMORTAN)       | [01][01] [02][02] [03][03] [04][04] [05][05] [06][06] [07][07] [08][08] [09][09] [10][10] [11][11] [12][12] [16][16] [17][17] [18][18] [20][20]          |
| [LNURL C#](https://github.com/Kukks/LNURL)            | [01][01] [02][02] [03][03] [04][04] [06][06] [07][07] [08][08] [09][09] [10][10] [11][11] [12][12] [14][14] [15][15] [16][16] [17][17] [18][18] [19][19] |
| [dart-lnurl](https://github.com/saentari/dart_lnurl)  | [01][01] [02][02] [03][03] [04][04] [05][05] [06][06] [09][09] [10][10] [11][11] [12][12] [14][14] [17][17] [18][18] [19][19]                            |
| [go-lnurl](https://github.com/fiatjaf/go-lnurl)       | [01][01] [02][02] [03][03] [04][04] [06][06] [08][08] [09][09] [10][10] [11][11] [12][12] [14][14] [16][16] [18][18] [20][20]                            |
| [js-lnurl](https://github.com/fiatjaf/js-lnurl)       | [01][01] [02][02] [03][03] [04][04] [06][06] [08][08] [09][09] [10][10] [11][11] [12][12]                                                                |
| [lnurl-node](https://github.com/chill117/lnurl-node)  | [01][01] [02][02] [03][03] [04][04] [06][06] [08][08] [09][09] [10][10] [11][11] [12][12]                                                                |
| [lnurl-platformio][platformio]                        | [01][01] [03][03]                                                                                                                                        |
| [lnurl-ruby](https://github.com/bumi/lnurl-ruby)      | [01][01] [06][06] [09][09]                                                                                                                               |
| [lnurlauth](https://github.com/xplorfin/lnurlauth)    | [01][01] [04][04]                                                                                                                                        |
| [php-lnurl](https://github.com/tkijewski/php-lnurl)   | [01][01]                                                                                                                                                 |
| [python-lnurl](https://github.com/python-ln/lnurl)    | [01][01] [02][02] [03][03] [04][04] [06][06]                                                                                                             |
| [bitcoin-s](https://github.com/bitcoin-s/bitcoin-s)   | [01][01] [03][03] [06][06] [09][09]                                                                                                                      |
| [lnurl-rs][lnurl-rs]                                  | [01][01] [03][03] [06][06]                                                                                                                               |
| [rust-lnurl][rust-lnurl]                              | [01][01] [03][03] [04][04]                                                                                                                               |
| [spring-lnurl][springlnurl]                           | [01][01] [04][04]                                                                                                                                        |
| [lnurl_client-ex][lnurl_client-ex]                    | [01][01] [06][06]                                                                                                                                        |

[rust-lnurl]: https://github.com/edouardparis/rust-lnurl [lnurl-rs]: https://github.com/benthecarman/lnurl-rs
[platformio]: https://github.com/chill117/lnurl-platformio
[springlnurl]: https://github.com/theborakompanioni/bitcoin-spring-boot-starter#spring-lnurl
[lnurl_client-ex]: https://github.com/ramontayag/lnurl_client-ex

开发人员的工具
--------------------

| Name                                                                   |卢兹|
| ----                                                                   | ----                                                                                                        |
| [LNURLProxyAPI](https://github.com/21isenough/LNURLProxyAPI)           | [01][01] [03][03]                                                                                           |
| [Lightning Decoder](https://lightningdecoder.com/)                     | [01][01] [02][02] [03][03] [04][04] [06][06] [16][16]                                                       |
| [Lightning Login](https://lightninglogin.live/)                        | [01][01] [04][04]                                                                                           |
| [bifrost](https://github.com/takinbo/bifrost)                          | [01][01] [02][02]                                                                                           |
| [lnch-vekslak](https://github.com/Kixunil/lnch-vekslak)                | [01][01] [02][02]                                                                                           |
| [lnurl codec JS](https://lnurl.fiatjaf.com/codec)                      | [01][01]                                                                                                    |
| [lnurl codec Scala](https://j-chimienti.github.io/lnurl_codec/)        | [01][01]                                                                                                    |
| [lnurl playground](https://lnurl.fiatjaf.com)                          | [01][01] [02][02] [03][03] [04][04] [06][06] [09][09] [10][10] [12][12] [14][14] [15][15] [18][18] [20][20] |
| [lnurl-toolbox](https://lnurl-toolbox.degreesofzero.com/)              | [01][01] [02][02] [03][03] [04][04] [06][06]                                                                |
| [passport-lnurl-auth](https://github.com/chill117/passport-lnurl-auth) | [01][01] [04][04]                                                                                           |
| [Zerologin](https://github.com/zerologin/zerologin)                    | [01][01] [04][04]                                                                                           |

[01]: 01.md
[02]: 02.md
[03]: 03.md
[04]: 04.md
[05]: 05.md
[06]: 06.md
[07]: 07.md
[08]: 08.md
[09]: 09.md
[10]: 10.md
[11]: 11.md
[12]: 12.md
[13]: 13.md
[14]: 14.md
[15]: 15.md
[16]: 16.md
[17]: 17.md
[18]: 18.md
[19]: 19.md
[20]: 20.md

依赖关系树
---------------

LNURL 协议套件的整体思想是它们是可选的。每个新的 Lud 可以由一些钱包而不是其他钱包实现，由一些服务而不是其他服务实现，但它们仍应始终保持兼容性（当然，如果服务_要求_具有新功能，则除外）。

在 Lud 之间还有一个内部依赖关系的层次结构--例如，如果你还没有实现基本 `payRequest` 规范，则不能在 S 中实现发送注释 `payRequest`。下图显示了内部依赖关系的层次结构（但你可以安全地忽略它）。

[![dependencies](dependencies.png)](dependencies.dot)

如何添加自己的文档
----------------------------

用你的建议打开一个拉取请求。为你的建议选择下一个未保留的号码。要被接受，它必须是体面的，有意义的，并由 2 个或更多的钱包实施或目前正在实施。

如果你只是想谈论你的想法或谈论一般的 LNURL 协议，请加入https://t.me/lnurl 。
