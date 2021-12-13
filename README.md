# Offer-Backgrounds
Offer BG names &amp; where to put them



RU
Всего 8 типов заднего фона:
offer_generic
offer_special
offer_legendary
offer_coins
offer_gems
offer_boxes
offer_finals
offer_lny
Вставлять их нужно в OwnHomeData, или же в LogicShopData, под следующими строками:
            self.write_string_reference(item['OfferTitle'])
            self.writeBoolean(False)
           => self.writeString('название') <=
Но также, можно сделать удобнее, написав 
            self.writeString(item['OfferBG'])
Не забыв внести изменения в Shop.py ||для Classic Brawl 1.0||
Найти эти названия можно в ui.sc, предварительно распаковав из lzma.

ENG
There's 8 types of backgrounds
offer_generic
offer_special
offer_legendary
offer_coins
offer_gems
offer_boxes
offer_finals
offer_lny
You need to past them in OwnHomeData, or in LogicShopData, below next strokes
           self.write_string_reference(item['OfferTitle'])
            self.writeBoolean(False)
           => self.writeString('bgname') <=
Но так также же, можно сделать удобнее, написав 
            self.writeString(item['OfferBG'])
Не забыв внести изменения в Shop.py ||для Classic Brawl 1.0||
Найти эти названия можно в ui.sc, предварительно распаковав из lzma.
