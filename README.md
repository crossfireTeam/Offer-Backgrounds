# Offer-Backgrounds
Offer BG names &amp; where to put them



# RU
Всего 8 типов заднего фона[^3]:  
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
Не забыв внести изменения в Shop.py[^1]  
Найти эти названия можно в ui.sc, предварительно распаковав из lzma.  


# ENG
There's 8 types of backgrounds[^3]  
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
You can do that better:  
            self.writeString(item['OfferBG'])  
But don't forget to do changes in Shop.py[^2]  
If you want to find these names, lzma decompress ui.sc  
  
  
[^1]: Относится к первой версии Classic Brawl
[^2]: Refers to the first version of Classic Brawl    
[^3]: ![lol2](https://github.com/crossfireTeam/Offer-Backgrounds/blob/main/tutorial.jpg)
