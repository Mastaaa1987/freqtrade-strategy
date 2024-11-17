# freqtrade-strategy

## Backtest Results Information

### Die Backest's mit den Strategien: FakeoutStrategy & ElliotV8_original_ichiv3 sind komplett Falsch und sollten niemals im Live Trade Mode angewand werden!

ElliotV8_original_ichiv3 ersetzt Open/High/Low mit heikinashi werten was im Backtest zu komplett falschen berechnungswerten im Profit führt ...

FakeoutStrategy schaut in die Zukunft was im Live Mode niemals funktionieren wird :-D

### Die E0V1E von ssssi (ssssi/freqtrade_strs) ist mit Abstand die beste Strategie, nachfolgend von NASOSv5_mod3 die zwar nicht halb so viele signale erzeugt, aber trotzdem beide eine Win Ratio von ~90% aufweisen. Die E0V1E Strategie nutze ich momentan im Live Mode, sie funktioniert sehr gut wie man unschwer an dem png erkennen kann. Die im Real Live erzeugten Signale sind "echte" Trades mit meinem Invest (ca. 300 USDT) ...

### Die NASOSv5_mod3 Signale lassen sich im prinzip gut mit denen von E0V1E ergänzen da das ewo_1 signal zu den buy_1 signalen viele zusätzliche erzeugt ! Ich bleibe aber Safe und nutze nur buy_1 von E0V1E, welche am 14-15.11.2024 an zwei Tagen 20% gewinne erzeugt hat ;-)

![LiveTrade Result](https://raw.githubusercontent.com/Mastaaa1987/freqtrade-strategy/refs/heads/main/user_data/E0V1E_LiveRun_and_backtest_results-2024-11-14_2024-11-16.png)
