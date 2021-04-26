# Modern Tibetan Corpus
This repository contains a small collection of linguistically analyzed Modern Tibetan texts. The collection includes blog posts, online newspaper articles, a classic essay, and three short works of fiction.

With the exception of _tibettimes_ and _tibetcm_, the texts were machine segmented and part-of-speech tagged. Texts were then converted to [BRAT standoff format](https://brat.nlplab.org/standoff.html) for human annotation using the _brat rapid annotation tool_.

Humans then focused on annotating the argument structure of verbs, approximating the guidelines of the [Universal Dependencies](https://universaldependencies.org/u/dep/) project. Part-of-speech tags were not corrected, except when they interacted with the required annotation.

In the case of _tibettimes_ and _tibetcm_, which were imported into BRAT as unanalyzed text, humans annotated the argument structure of verbs, assigning part-of-speech tags to only those words implicated in the annotation.

Texts were then converted to [CoNLLU format](https://universaldependencies.org/format.html) for broader dissemination and use. To facilitate the proper assembly of Tibetan sentences, untagged spans of text were automatically assigned the tag ```NOTAG```. Again with the exception of _tibettimes_ and _tibetcm_, English translations of the remaining texts were aligned to the Tibetan, which can be seen in the corresponding CoNLL-U files.

Final BRAT configuration and data files for these texts are included in this repository for completeness, in case anyone wishes to reproduce the BRAT configuration used for annotating the texts. In addition, unannotated texts from the _tibettimes_ and _tibetcm_ subcollections are included. These are the wider datasets from which the annotated materials were selected.

It is important to stress that moving forward, only the CoNLL-U files will be maintained.

You may cite this work by referencing the repository and its authors: Jamyang Dakpa, Tashi Dhondup, Yeshi Jigme Gangne, Edward Garrett, Marieke Meelen, and Sonam Wangyal. We thank the AHRC for its funding of the project _Lexicography in Motion_ (2017-2021, PI Ulrich Pagel).

Here is some metadata about the collection.

| Key | Value |
| ------------- | ------------- |
| Text ID | conflict |
| Title (eng) | Conflict and Resolution: A Response to Liu Junning |
| Title (bod) | འགལ་བ་དང་འདུམ་པ། ལིའུ་ཅུན་ཉིང་ལགས་ལ་བསམ་ཚུལ་ཙམ་བཏོན་པ། |
| Source (eng) | https://highpeakspureearth.com/conflict-and-resolution-a-response-to-liu-junning-by-shokjang/ |
| Source (bod) | http://woeser.middle-way.net/2014/06/blog-post_30.html |
| Date | 07-06-2014 |
| Author | Shokjang (aka Druklo) |
| Translation | Palden Gyal |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Blog |
| Region | Tibet |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |

| Key | Value |
| ------------- | ------------- |
| Text ID | japanese |
| Title (eng) | Japanese People and Japanese Literature |
| Title (bod) | ཉི་ཧོང་གི་མི་དང་ཉི་ཧོང་གི་རྩོམ་རིག༼ལྷུག་རྩོམ༽ |
| Source (eng) | https://highpeakspureearth.com/japanese-people-and-japanese-literature-by-kyabchen-dedrol/ |
| Source (bod) | https://web.archive.org/web/20140423145916/http://www.tibetcm.com/html/degrol/201401125901.html |
| Date | 10-2013 |
| Author | Kyabchen Dedrol |
| Translation | ? |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Blog |
| Region | Tibet |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |

| Key | Value |
| ------------- | ------------- |
| Text ID | narrowfootpath |
| Title (eng) | A Threadlike Path |
| Title (bod) | རྐང་ལམ་ཕྲ་མོ། |
| Source (bod) | Rang grol (Don grub rgyal), (1984), "rKang lam phra mo" (A Small Foot Track), in sBrang char, [Xining], 1984, 3(14), pp 1-5. |
| Source (eng) | Stevenson, Mark, and Lama Choedak T. Yuthok. "A Threadlike Path." The Tibet Journal (1997): 61-66. |
| Date | 1984 |
| Author | Rang grol (Don grub rgyal) |
| Translation | Mark Stevenson and Lama Choedak T. Yuthok |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Essay |
| Region | Tibet |
| Language | Tibetan, Modern |
| Annotator's notes (eng) | Dhondup Gyal's essay "A Threadlike Path" founded a new style of Tibetan literature called which became very popular throughout Tibet. ‘A Threadlike Path’ has been the pillar stone of Tibetan prose style and is worthy of research. |
| Annotator's notes (bod) |སྡེ་ཚན་འདིའི་ཁྲོད་དུ་བོད་ཀྱི་རྩོམ་རིག་གསར་བའི་སྲོལ་འབྱེད་དཔལ་དོན་གྲུབ་རྒྱལ་གྱིས་གསར་རྩོམ་གནང་ཞིང་བོད་ཁམས་ཡོངས་སུ་ད་ལྟའང་སྐད་གྲགས་ཆོད་པའི་ལྷུག་རྩོམ་རྐང་ལམ་ཕྲ་མོ་ཡོད། རྐང་ལམ་ཕྲ་མོ་ནི་བོད་ཀྱི་དེང་རབས་ལྷུག་རྩོམ་གྱི་རྡོ་རིང་ལྟ་བུ་ཡིན་པས་ན་དེར་ཞིབ་འཇུག་གི་རིན་ཐང་ལྷག་ཏུ་ལྡན་པ་ཡིན། རྐང་ལམ་ཕྲ་མོ་ནི་བོད་ཀྱི་སྲོལ་རྒྱུན་རྩོམ་རིག་གི་རྒྱུན་དང་མ་བྲལ་ཞིང་དེང་རབས་རྩོམ་རིག་གི་མདངས་ཀྱིས་ཕྱུག་པའི་བརྩམས་ཆོས་ཤིག་ཡིན། |

| Key | Value |
| ------------- | ------------- |
| Text ID | snowpilgrimage |
| Title (eng) | Snow Pilgrimage |
| Title (bod) | གངས་སྐོར། |
| Source (bod) | https://www.tibetcm.com/specialist/deydrol/2017-12-21/8541.html |
| Source (eng) | "Snow Pilgrimage", pp. 209-218 in Dickie, Tenzin. Old demons, new deities: twenty-one short stories from Tibet. OR books, 2017. |
| Date | 21-12-2017 |
| Author | Kyabchen Dedrol |
| Translation | Tenzin Dickie, Catherine Tsuji and Dhondup Tashi Rekjong |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Short story |
| Region | Tibet |
| Language | Tibetan, Modern |
| Annotator's notes (eng) | These days many of the literary works of Tibetan writers appear and are being translated in various languages. Specially, many poems and novels have been translated into English. Such as; Pema Tseden’s Enticement: Stories of Tibet have been translated by Patrica Schiaffini-Vedani and Michael Monhart in English. Similarly, 21 short stories from Tibet have been translated into English by Tenzin Dickie titled Old Demons New Deities and Tsering Dondrup’s The Handsome Monk And Other Stories has been translated by Christopher Peacock. Thus, we are working on few selected short stories that are translated into English. These novels are very popular in modern Tibetan literature. They possess proper grammatical construction and are rich in modern style of composition having minimal use of colloquial verbs and vernacular terms. |
| Annotator's notes (bod) | དེང་སྐབས་བོད་ཀྱི་རྩོམ་པ་པོ་མང་པོའི་སྒྱུ་རྩལ་བརྩམས་ཆོས་དུ་མ་ཞིག་རྒྱལ་ཁབ་གཞན་གྱི་སྐད་ཡིག་ཏུ་བསྒྱུར་དང་སྒྱུར་བཞིན་ཡོད་ལ།ལྷག་པར་དུ་ཉེ་བའི་ཆར་སྙན་ངག་དང་བརྩམས་སྒྲུང་མང་པོ་ཞིག་དབྱིན་ཡིག་ཏུ་བསྒྱུར་ཡོད་དེ་པདྨ་ཚེ་བརྟན་གྱི་བསླུ་བྲིད་དང་སྒྲུང་ཐུང་བཅུ་ཙམ་ Patrica Schiaffini-Vedani དང་ Michael Monhart ལགས་ཀྱི་དབྱིན་ཡིག་ཏུ་བསྒྱུར་ཡོད།དེ་བཞིན་བསྟན་འཛིན་བདེ་སྐྱིད་ལགས་ཀྱིས་འདྲེ་རྙིང་པ་དང་ལྷ་གསར་པ་ཞེས་པའི་བསྒྱུར་དེབ་ཁྲོད་བོད་ཕྱི་ནང་གཉིས་སུ་བཞུགས་ཡོད་པའི་རྩོམ་པ་པོ་བཅུ་ཕྲུག་ལྷག་གིས་བརྩམས་པའི་བོད་ཡིག་སྒྲུང་ཐུང་མི་ཉུང་པ་ཞིག་དབྱིན་བསྒྱུར་ཞུས་ཡོད། དེ་བཞིན་ཉེ་སྔོན་བོད་ནང་གི་རྩོམ་པ་པོ་ཚེ་རིང་དོན་གྲུབ་ལགས་ཀྱི་སྒྲུང་ཐུང་བཙུན་ཡག་གཙོས་སྒྲུང་ཐུང་བཅུ་ལྷག་ཙམ་Christopher Peacock ལགས་ཀྱིས་དབྱིན་ཡིག་ཏུ་བསྒྱུར་ཡོད། དེ་བས་ང་ཚོས་དབྱིན་བསྒྱུར་ཞུས་ཟིན་པའི་སྒྲུང་ཐུང་འགའ་བདམས་སྟེ་ལས་ཀ་བྱེད་བཞིན་ཡོད། བརྩམས་སྒྲུང་དེ་དག་ནི་དེང་རབས་བོད་ཀྱི་རྩོམ་རིག་ཁྲོད་ན་མེ་ཏོག་བཞིན་བཞད་ཡོད། བོད་ཀྱི་བརྡ་སྤྲོད་ཀྱི་རྣམ་གཞག་དང་མཐུན་ཞིང་དེང་རབས་ཚིག་སྦྱོར་གྱི་ཉམས་ཀྱིས་ཕྱུག་ལ། ཁ་སྐད་དུ་ཡོངས་ཁྱབ་བཀོལ་སྤྱོད་བྱེད་བཞིན་པའི་བྱ་ཚིག་དང་གྲོང་ཚིག ད་དུང་བྱ་ཚིག་ཕལ་པ་བཅས་བཀོལ་ཉུང་བ་སོགས་ཀྱི་ཁྱད་ཆོས་ལྡན་ཡོད། |

| Key | Value |
| ------------- | ------------- |
| Text ID | summerpastures |
| Title (eng) | Access to summer pastures is the herders' right |
| Title (bod) | དབྱར་ས་བཀོལ་སྤྱོད་བྱེད་པ་ནི་འབྲོག་པ་རྣམས་ཀྱི་ཐོབ་ཐང་ཡིན། |
| Source (eng) | https://www.savetibet.org/tibetan-nomads-make-rare-appeal-against-removal-from-grasslands/ |
| Source (bod) | http://trimleng.cn/grassland-rights-for-nomads-2/ |
| Date | 11-07-2017 |
| Author | Drolma Kyab |
| Translation | International Campaign for Tibet |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Blog |
| Region | Tibet |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |

| Key  | Value |
| ------------- | ------------- |
| Text ID | tenvirtues |
| Title (eng) | A Reflection on the So-Called “Ten Virtues” |
| Title (bod) | དགེ་བཅུའི་ཁྲིམས་སྲོལ་སྐོར་གྱི་བསམ་ཚུལ། |
| Source (eng) | https://highpeakspureearth.com/a-reflection-on-the-so-called-ten-virtues-by-khenpo-pema-tsering/ |
| Source (bod) | https://mp.weixin.qq.com/s?__biz=MjM5Njc0NDcwMQ==&mid=219584545&idx=1&sn=9314e2a3b75990a6a78ce5fb673b56ba&scene=1&from=singlemessage&isappinstalled=0#rd |
| Date | 24-07-2015 |
| Author | Khenpo Pema Tsering |
| Translation | Palden Gyal |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Blog |
| Region | Tibet |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |

| Key | Value |
| ------------- | ------------- |
| Text ID | theparty |
| Title (eng) | Should One Follow the Party's Instructions? |
| Title (bod) | ཏང་གི་འཛུབ་སྟོན་ལ་ཉན་འོས་སམ། |
| Source | https://highpeakspureearth.com/should-one-follow-the-partys-instructions-by-shokjang/ |
| Source (bod) | https://web.archive.org/web/20200807042818/http://www.shambalapost.com/2008-11-18-12-08-03/11624-2015-04-13-09-35-48 |
| Date | 18-11-2008 |
| Author | Shokjang (aka Druklo) |
| Translation | Palden Gyal and Tsewang Norbu |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Essay |
| Region | Tibet, Amdo |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |

| Key  | Value |
| ------------- | ------------- |
| Text ID | tibetcm |
| Title (eng) | Tibetcm |
| Title (bod) | མཆོད་མེ་བོད་ཀྱི་རྩོམ་རིག་དྲ་བ། |
| Source | https://www.tibetcm.com/ |
| Date | 2015-2018 |
| Author | Various |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Genre | Interview / Fiction / Prose |
| Region | Tibet |
| Language | Tibetan, Modern |
| Annotator's notes (eng) | Chodme Tibetan Literary Website was created in 2005 in Tibet. It has published various classical and modern Tibetan literary works including news, selected writings, oral literatures, modern literature, audio visual, special edition etc. by categorizing them on the basis of numerous scholars throughout Tibet. It is the first website in Tibet that allows the fictional stories to be published. It is highly regarded and appreciated by Tibetan scholars within Tibet and outside by publishing their suggestions, articles and comments. It was launched by the young writers of Domey Kenlho Machu lead by Kyabchen Dedrol,  Konchok Tsephel and others. We are working on the interviews, prose and stories etc that are published in Chodme Tibetan Literary Website. The literature works published in the website are of high qualities such as, correct usage of grammatical construction and modern style of metrics. Especially the verbs used in modern literatures are familiar to those found in the classical literatures and usage of vernacular terms is minimized. |
| Annotator's notes (bod) | མཆོད་མེ་བོད་ཀྱི་རྩོམ་རིག་དྲ་བ་ནི ༢༠༠༥ ལོར་བོད་ནང་ནས་གསར་དུ་མགོ་བཙུགས་པ་དང་། དྲ་རྒྱ་དེའི་ཐོག་ལ་གནའ་དེང་བོད་ཀྱི་རྩོམ་རིག་གི་སྒྱུ་རྩལ་བརྩམས་ཆོས་སྣ་མང་ཞིག་བཀོད་ཡོད་པ་མ་ཟད།འཕྲིན་གསར་དང་།ལེགས་རྩོམ།ངག་རྩོམ།དེང་རྩོམ།སྒྲ་བརྙན།ཆེད་སྒྲིག་སོགས་སྡེ་ཚན་དུ་མར་དབྱེ་ནས་བོད་ས་ཁྱོན་ཡོངས་ཀྱི་རྩོམ་པ་པོའི་བརྩམས་ཆོས་མང་དག་ཅིག་འཛོམས་ཡོད།དེ་བཞིན་དྲ་རྒྱ་དེ་ནི་རྟོག་སྒྲུང་སོགས་བཀོད་ཆོག་པའི་བོད་ནང་གི་ཆེས་ཐོག་མའི་བོད་ཡིག་དྲ་རྒྱ་ཞིག་ཆགས་ཡོད།བོད་ཕྱི་ནང་གཉིས་སུ་ཡོད་པའི་བོད་མི་ཤེས་ཡོན་ཅན་དང་སྒྱུ་རྩལ་པ་མང་པོས་དྲ་རྒྱ་དེའི་ཐོག་ལ་དགོངས་འཆར་དང་དཔྱད་རྩོམ།མཆན་སོགས་འདྲ་མིན་བཀོད་དེ་དགའ་མོས་དང་འདེང་འཇོག་བྱེད་ཀྱི་ཡོད།དྲ་རྒྱ་དེ་མདོ་སྨད་ཀན་ལྷོ་རྨ་ཆུ་ཕྱོགས་ཀྱི་གཞོན་སྐྱེས་རྩོམ་པ་པོ་སྐྱབས་ཆེན་བདེ་གྲོལ་དང་དཀོན་མཆོག་ཚེ་འཕེལ་གཙོས་གཞོན་སྐྱེས་ཁག་གཅིག་གིས་གསར་བཙུགས་བྱས་པ་ཞིག་ཡིན། ང་ཚོས་འདིར་མཆོད་མེ་དྲ་བའི་སྟེང་བཀོད་ཡོད་པའི་བཅར་འདྲི་དང་ལྷུག་རྩོམ།བརྩམས་སྒྲུང་སོགས་ཀྱི་ཐོག་ལ་ལས་ཀ་བྱེད་བཞིན་ཡོད། མཆོད་མེ་དྲ་བའི་སྟེང་གི་བརྩམས་ཆོས་རྣམས་ནི་བོད་ཀྱི་བརྡ་སྤྲོད་ཀྱི་སྒྲིག་གཞི་དང་མཐུན་ཞིང་ཚིག་གི་སྡེབ་སྦྱོར་ལ་དེང་རབས་ཀྱི་ཉམས་ཡོད་པ། ལྷག་པར་དུ་དེང་རབས་བརྩམས་ཆོས་རྣམས་སུ་བཀོལ་སྤྱོད་བྱས་པའི་བྱ་ཚིག་རྣམས་ནི་བོད་ཀྱི་སྲོལ་རྒྱུན་རྩོམ་རིག་གི་བྱ་ཚིག་དང་ཐག་ཉེ་བ་མ་ཟད་ཡོངས་གྲགས་ཀྱི་ཁ་སྐད་ནང་སྤྱོད་བཞིན་པའི་གྲོང་ཚིག་གམ་བྱ་ཚིག་ཕལ་བ་བཀོལ་པ་ཉུང་བའི་ཁྱད་ཆོས་ལྡན་ཡོད། |

| Key | Value |
| ------------- | ------------- |
| Text ID | tibettimes |
| Title (eng) | Tibet Times |
| Title (bod) | བོད་ཀྱི་དུས་བབ། |
| Source | https://tibettimes.net/ |
| Date | 2014-2017 |
| Author | Various |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Genre | News |
| Region | Tibet, Diaspora |
| Language | Tibetan, Modern |
| Annotator's notes (eng) | Tibet Times is an independent press based in Dharamsala, India and it has been 23 years since its first publication. It has circulation in 20 countries around the world including Tibet. It consist of six sections i.e. News, opinions, announcements, interviews, videos, audios and photo galleries. Its main objectives are to support the just cause of Tibetan struggle, protection of Tibetan language and culture and promotion of awareness on human rights and democracy in Tibetan society etc. It has around 7000 to 10000 viewership in a day.  We are working on the news section of Tibet Times that were published from January, 2014 to November, 2017. Such news have very less grammatical errors and are found written in commonly used colloquial verbs and other terms. |
| Annotator's notes (bod) | སྡེ་ཚན་འདིའི་ཁྲོད་དུ་བོད་ཀྱི་རྩོམ་རིག་གསར་བའི་སྲོལ་འབྱེད་དཔལ་དོན་གྲུབ་རྒྱལ་གྱིས་གསར་རྩོམ་གནང་ཞིང་བོད་ཁམས་ཡོངས་སུ་ད་ལྟའང་སྐད་གྲགས་ཆོད་པའི་ལྷུག་རྩོམ་རྐང་ལམ་ཕྲ་མོ་ཡོད། རྐང་ལམ་ཕྲ་མོ་ནི་བོད་ཀྱི་དེང་རབས་ལྷུག་རྩོམ་གྱི་རྡོ་རིང་ལྟ་བུ་ཡིན་པས་ན་དེར་ཞིབ་འཇུག་གི་རིན་ཐང་ལྷག་ཏུ་ལྡན་པ་ཡིན། རྐང་ལམ་ཕྲ་མོ་ནི་བོད་ཀྱི་སྲོལ་རྒྱུན་རྩོམ་རིག་གི་རྒྱུན་དང་མ་བྲལ་ཞིང་དེང་རབས་རྩོམ་རིག་གི་མདངས་ཀྱིས་ཕྱུག་པའི་བརྩམས་ཆོས་ཤིག་ཡིན། |

| Key  | Value |
| ------------- | ------------- |
| Text ID | vegetarianism |
| Title (eng) | Coerced Vegetarianism and the Welfare of Tibetans |
| Title (bod) | དམར་ཟས་བཙན་གཅོད་དང་བོད་མིའི་བདེ་ཐང་། |
| Source (eng) | https://highpeakspureearth.com/coerced-vegetarianism-and-the-welfare-of-tibetans-by-jamyang-kyi-2/ |
| Source (bod) | Buffetrille, Katia. "A controversy on vegetarianism." Trails of the Tibetan Tradition, Papers for Elliot Sperling (2014): 113-128. |
| Date | 24-06-2013 |
| Author | Jamyang Kyi |
| Translation | Katia Buffetrille |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Blog |
| Region | Tibet |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |

| Key | Value |
| ------------- | ------------- |
| Text ID | wink |
| Title (eng) | Wink |
| Title (bod) | མིག་རྡེབ། (སྒྲུང་ཐུང་ཞིག) |
| Source (bod) | https://www.khabdha.org/?p=34109 |
| Source (eng) | "Wink", pp. 9-30 in Dickie, Tenzin. Old demons, new deities: twenty-one short stories from Tibet. OR books, 2017. |
| Date | 30-09-2012 |
| Author | Pema Bhum |
| Translation | Tenzin Dickie |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Short story |
| Region | Tibet |
| Language | Tibetan, Modern |
| Annotator's notes (eng) | These days many of the literary works of Tibetan writers appear and are being translated in various languages. Specially, many poems and novels have been translated into English. Such as; Pema Tseden’s Enticement: Stories of Tibet have been translated by Patrica Schiaffini-Vedani and Michael Monhart in English. Similarly, 21 short stories from Tibet have been translated into English by Tenzin Dickie titled Old Demons New Deities and Tsering Dondrup’s The Handsome Monk And Other Stories has been translated by Christopher Peacock. Thus, we are working on few selected short stories that are translated into English. These novels are very popular in modern Tibetan literature. They possess proper grammatical construction and are rich in modern style of composition having minimal use of colloquial verbs and vernacular terms. |
| Annotator's notes (bod) | དེང་སྐབས་བོད་ཀྱི་རྩོམ་པ་པོ་མང་པོའི་སྒྱུ་རྩལ་བརྩམས་ཆོས་དུ་མ་ཞིག་རྒྱལ་ཁབ་གཞན་གྱི་སྐད་ཡིག་ཏུ་བསྒྱུར་དང་སྒྱུར་བཞིན་ཡོད་ལ།ལྷག་པར་དུ་ཉེ་བའི་ཆར་སྙན་ངག་དང་བརྩམས་སྒྲུང་མང་པོ་ཞིག་དབྱིན་ཡིག་ཏུ་བསྒྱུར་ཡོད་དེ་པདྨ་ཚེ་བརྟན་གྱི་བསླུ་བྲིད་དང་སྒྲུང་ཐུང་བཅུ་ཙམ་ Patrica Schiaffini-Vedani དང་ Michael Monhart ལགས་ཀྱི་དབྱིན་ཡིག་ཏུ་བསྒྱུར་ཡོད།དེ་བཞིན་བསྟན་འཛིན་བདེ་སྐྱིད་ལགས་ཀྱིས་འདྲེ་རྙིང་པ་དང་ལྷ་གསར་པ་ཞེས་པའི་བསྒྱུར་དེབ་ཁྲོད་བོད་ཕྱི་ནང་གཉིས་སུ་བཞུགས་ཡོད་པའི་རྩོམ་པ་པོ་བཅུ་ཕྲུག་ལྷག་གིས་བརྩམས་པའི་བོད་ཡིག་སྒྲུང་ཐུང་མི་ཉུང་པ་ཞིག་དབྱིན་བསྒྱུར་ཞུས་ཡོད། དེ་བཞིན་ཉེ་སྔོན་བོད་ནང་གི་རྩོམ་པ་པོ་ཚེ་རིང་དོན་གྲུབ་ལགས་ཀྱི་སྒྲུང་ཐུང་བཙུན་ཡག་གཙོས་སྒྲུང་ཐུང་བཅུ་ལྷག་ཙམ་Christopher Peacock ལགས་ཀྱིས་དབྱིན་ཡིག་ཏུ་བསྒྱུར་ཡོད། དེ་བས་ང་ཚོས་དབྱིན་བསྒྱུར་ཞུས་ཟིན་པའི་སྒྲུང་ཐུང་འགའ་བདམས་སྟེ་ལས་ཀ་བྱེད་བཞིན་ཡོད། བརྩམས་སྒྲུང་དེ་དག་ནི་དེང་རབས་བོད་ཀྱི་རྩོམ་རིག་ཁྲོད་ན་མེ་ཏོག་བཞིན་བཞད་ཡོད། བོད་ཀྱི་བརྡ་སྤྲོད་ཀྱི་རྣམ་གཞག་དང་མཐུན་ཞིང་དེང་རབས་ཚིག་སྦྱོར་གྱི་ཉམས་ཀྱིས་ཕྱུག་ལ། ཁ་སྐད་དུ་ཡོངས་ཁྱབ་བཀོལ་སྤྱོད་བྱེད་བཞིན་པའི་བྱ་ཚིག་དང་གྲོང་ཚིག ད་དུང་བྱ་ཚིག་ཕལ་པ་བཅས་བཀོལ་ཉུང་བ་སོགས་ཀྱི་ཁྱད་ཆོས་ལྡན་ཡོད། |

| Key  | Value |
| ------------- | ------------- |
| Text ID | women |
| Title (eng) | Women and their Ornamentation |
| Title (bod) | འདོགས་ཆ་དང་བུད་མེད་ཀྱི་འབྲེལ་བ། |
| Source (eng) | https://highpeakspureearth.com/women-and-their-ornamentation-by-jamyang-kyi/ |
| Source (bod) | https://web.archive.org/web/20140313164328/http://sangdhor.com/blog_c.asp?id=13307&a=menzhu |
| Date | 02-01-2014 |
| Author | Jamyang Kyi |
| Translation | Tenzin Nyinjey |
| Tagging | Marieke Meelen |
| Annotation | Jamyang Dakpa & Tashi Dhondhup |
| Alignment | Sonam Wangyal |
| Genre | Blog |
| Region | Tibet |
| Language | Tibetan, Modern |
| Licensing | Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) |
| Annotator's notes (eng) | In these blogs, we can find collection of research works and articles on social issues written by young writers in Tibet. These writers are born and brought up in Tibet and are proficient in Tibetan literature. These blogs are written in accordance with modern style of literature and focuses on raising issues related to unjust laws and governance of the Government. They also focus on criticizing against the extreme religious practices. |
| Annotator's notes (bod) | ཟིན་བྲིས་འདིའི་ནང་བོད་ཀྱི་དེང་རབས་རྩོམ་པ་པོ་རྣམས་ཀྱིས་བྲིས་པའི་ལྷུག་རྩོམ་དང་སྤྱི་ཚོགས་དཔྱད་བརྗོད་ཀྱི་རིགས་རྣམས་བསྡུས་ཡོད་ལ། རྩོམ་པ་པོ་ཁོང་རྣམས་ནི་བོད་ཡུལ་རང་དུ་སྐྱེས་ཤིང་འཚར་བ་དང། དེང་རབས་བོད་ཀྱི་སྐད་ཡིག་ལ་ནང་བྱན་ཆུད་ཡོད། འདིར་ཡོད་རྩོམ་ཡིག་རྣམས་ནི་དེང་རབས་བོད་ཀྱི་ཡིག་སྐད་དང་བསྟུན་ནས་བྲིས་ཡོད་ལ། དཔྱད་བརྗོད་འདི་རིགས་ཀྱི་བརྗོད་གཞི་ནི་གཞུང་གི་དྲང་བདེན་མ་ཡིན་པའི་ཁྲིམས་དང་སྒྲིག་སྲོལ་རྣམས་ཐེར་འདོན་དང་། ཆོས་ལུགས་པ་ཚོའི་ཐལ་དྲགས་པའི་བྱ་སྤྱོད་ལ་དགག་པ་བརྒྱབས་པ་བཅས་ཡིན། |
