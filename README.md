Um diese Handelsstrategie zu implementieren, benötigen wir eine Reihe von Klassen und Funktionen. Die Hauptklassen und Funktionen, die wir benötigen, sind:

1. `VWAPIndicator`: Diese Klasse berechnet den Volume Weighted Average Price (VWAP) und die Standardabweichungen. Sie wird Methoden wie `calculate_vwap` und `calculate_std_dev` haben.

2. `TradingStrategy`: Diese Klasse implementiert die eigentliche Handelsstrategie. Sie wird Methoden wie `buy_signal`, `sell_signal`, `place_buy_order` und `place_sell_order` haben.

3. `Trade`: Diese Klasse repräsentiert einen einzelnen Handel. Sie wird Attribute wie `entry_price`, `exit_price`, `stop_loss` und `take_profit` haben.

4. `Backtester`: Diese Klasse führt einen Backtest der Strategie durch. Sie wird Methoden wie `run_backtest` und `calculate_performance_metrics` haben.

5. `main`: Dies ist die Hauptfunktion, die die gesamte Strategie ausführt.

Jetzt werde ich den Code für jede dieser Klassen und Funktionen ausarbeiten.

src/vwap_indicator.py
