# isEnglish
Is that news article in English?

I started pulling news feeds from various sources for some odd project. Turns out, after I screened them for various interests, a lot of the articles were in Spanish, Japanese, and French. I looked around for an easy language filter, but the RSS feeds were not reliable and I wasn't interested in typing which foreign language was cluttering my interests, just knowin' that it weren't no English language!

I put together this pretty efficient python script to return True or False on the Englishness of the scripture. I'm sure that you can find some exceptions to this rule, but it's near perfect when the inputs are from news articles. 

Here are some articles that it excluded from my views'

average_unicode_value = 89.27    small_words = 7 of which 0% are English3s
Avis aux mÃ©dias - Condition fÃ©minine Canada
Date ---> March 02, 2018 at 02:00.00 PM
OTTAWA, le 2 mars 2018 /CNW/ - Lhonorable Maryam Monsef, ministre de la Condition fÃ©minine, fera une annonce importante concernant le budget 2018.  Veuillez noter que cet avis pourrait Ãªtre modifiÃ© sans prÃ©avis.  DÃ©tailsandnbsp;:  Dateandnbsp;: le lundi 5 mars 2018  Heure : 11 h  Emplace...


average_unicode_value = 92.95    small_words = 13 of which 15% are English3s
Fim do parcelamento sem juros segue em debate no Brasil
Date ---> March 02, 2018 at 11:48.00 AM
RIO DE JANEIRO, 2 de marÃ§o de 2018 /PRNewswire/ -- Proposto pelo setor de cartÃµes de crÃ©dito no inÃ­cio do ano, o fim da prÃ¡tica do parcelamento sem juros deverÃ¡ ser um dos principais temas de debates no comÃ©rcio ao longo de 2018. Essa medida, que tem como justificativa a reduÃ§Ã£o de custos...

average_unicode_value = 19094.48    small_words = 0 of which 0% are English3s
交番で警官が男に刺され死亡 男も別の警官に撃たれ死亡 仙台
2018年9月19日 8時42分
19日朝早く、仙台市宮城野区の交番で30代の警察官が男に刃物で刺されて死亡しました。男は交番にいた別の警察官に拳銃で撃たれ死亡し、警察は殺人未遂の疑いで現場の状況を調べています。

average_unicode_value = 130.90    small_words = 5 of which 100% are English3s
Apple repays €14B in “illegal aid” to Ireland, so EU drops court case
Cyrus Farivar - 9/18/2018, 1:34 PM
European Commissioner for Competition Margrethe Vestager said Tuesday that the European Commission will finally close its legal investigation into Apple's failure to pay back taxes to Ireland after the company paid €14 billion.



Let me know how you improve it. 


