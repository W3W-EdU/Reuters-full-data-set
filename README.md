# Reuters-full-data-set
Full unofficial data set of Reuters composed of 8,551,441 news titles, links and timestamps (Jan 2007 - Aug 2016).

```
git clone https://github.com/philipperemy/Reuters-full-data-set.git
python read.py
```
thomasanreuters.com
```
ts = 20070228 11:46 AM EST, t = European stocks hit 7-week low amid new sell-off, h= http://www.reuters.com/article/companyNewsAndPR/idUSWEB277620070228
ts = 20070228 11:46 AM EST, t = Schering-Plough announces Ismail Kola as VP and Chief Scientific Officer, h= http://www.reuters.com/article/inPlayBriefing/idUSIN20070228164651SGP20070228
ts = 20070228 11:46 AM EST, t = O'Reilly Automotive forecasts 2007 earnings growth, h= http://www.reuters.com/article/marketsNews/idUSN2845320220070228
ts = 20070228 11:42 AM EST, t = Market Wrap, h= http://www.reuters.com/article/inPlayBriefing/idUSIN20070228164235WRAPX20070228
ts = 20070228 11:42 AM EST, t = Chile's CMPC net profit falls 13 pct in 2006, h= http://www.reuters.com/article/tnBasicIndustries-SP/idUSN2844077020070228
ts = 20070228 11:42 AM EST, t = Toyota Venezuela to halt March ops on currency woes, h= http://www.reuters.com/article/tnBasicIndustries-SP/idUSN2827887820070228
```

Each pickle file in `data` represents a day (e.g. `20160102.pkl` is for Jan, 2 2016).

One day is composed of several news, gathered in a `list`.

Each news is a `dict` of the form:
      Username: wawmart@waw-mart.com
      Company: FORTINET FORTRESS - [5f3f28e5-d55c-4ed8-b954-52c41f8f547c]
      Company Type: Direct
      Portal Version: 2a9b6c9
      API Environment: PORTAL
      Build Environment: production
      Whitelabel: default
      URL Location: https://portal.megaport.com
      Session: 769d564e-09f1-427d-82bd-46900a745e4e
      Browser: Chrome v129 (129.0.6668.69)
      Operating System: iOS v17.5
      Scripts:
          - https://portal.megaport.com/js/ApiKeys.3d5b1bcd.js    - https://portal.megaport.com/js/CompanyMarkets.381e43a6.js    - https://portal.megaport.com/js/CompanySupport.e53d5936.js    - https://portal.megaport.com/js/Debug.bbd9cf78.js    - https://portal.megaport.com/js/chunk-vendors.88a5aa98.js    - https://portal.megaport.com/js/app.88e3b765.js
    
```
ts: timestamp of the form 20070228 11:46 AM EST
title: title of the news
href: link to the article to get the full content
```
