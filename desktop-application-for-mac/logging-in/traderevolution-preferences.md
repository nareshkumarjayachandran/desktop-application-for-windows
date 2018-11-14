# TraderEvolution Preferences

To open the 'TraderEvolution Preferences' menu, click on the button 'Preferences' located 

This menu contains such sections, as:

* General:
  * Allow automatic login – if checked, Mac application will automatically connect to the server while launching;
  * Automatically reconnect application – if checked, Mac application will try to reconnect to the server after losing connection.
* View:
  * Display quantity in lots – if checked, orders quantity is shown in lots, otherwise - in units;
  * Display quantity in absolute – if checked, orders quantity is shown in absolute values;
  * Reverse buttons order – if checked, trading buttons will be reversed to Sell/Buy pattern;
  * Activate deal tickets – if checked, the system will display informational deal tickets.
* Sounds – allows to enable/disable System and Trading sounds:
  * System
    * Welcome;
    * Connection established;
    * Connection lost;
    * Confirmation;
    * Alert.
  * Trading
    * Order;
    * Position;
    * Reject;
    * Modify;
    * Lock workspace;
    * Unlock workspace.

The option 'Disable sounds' allows to switch off all the sounds, System and Trading ones.

* Trading defaults:
  * Account – allows to select a default account for trading;
  * Symbol – allows to select a default instrument for trading;
  * Order type – allows to select a default type of order for trading:
    * Market – an order to buy or sell a security at the best available price immediately;
    * Limit – an order to buy or sell a security at specified price or better;
    * Stop – an order to buy or sell a security when its price surpasses a particular point, thus ensuring a greater probability of achieving a predetermined entry or exit price, limiting the investor's loss or locking profit;
    * Stop limit – an order to be executed at a specified price \(or better\) after a given stop price is reached. Once the stop price is reached, the stop-limit order becomes a limit order to buy \(or sell\) at the limit price or better;
    * Trailing stop:
      * Sell trailing stop order sets the stop price at a fixed amount below the market price on the trailing offset. As the market price rises, the stop price rises by the trail amount, but if the stock price falls, the stop loss price doesn't change, and a market order is submitted when the stop price is hit;
      * Buy trailing stop orders are the mirror image of sell trailing stop orders.
    * OCO \(One cancels other\) – an order containing two parts, if one part is executed, then the other part is automatically canceled;
  * Market TIF – allows to set up a default time-in-force of a Market order. The following types of TIF are available:
    * Day – an order will be valid for a current trading day;
    * GTC \(Good till canceled\) – an order will remain active until it is canceled or a contract expires;
    * IOC \(Immediate or cancel\) – an order or its part will be immediately executed;
    * GTD \(Good till date\) – an order will be cancelled on a specified date, if not executed, or will remain active until a contract expiration;
    * FOK \(Fill or kill\) – an order will be immediately fully executed or not executed at all.
  * Limit/Stop Limit TIF – allows to set up a default time-in-force of Limit and Stop Limit orders;
  * Stop TIF – allows to set up a default time-in-force of a Stop order;
  * Default qty in lots – allows to indicate the default qty of lots for trading;
  * Show offset in – allows to show offset in Ticks or Points;
  * Set SL/TP values in offset – if checked, order prices are shown in offset, if unchecked – in absolute values.
* Confirmations – allows to activate the following confirmations:
  * Confirm order placement;
  * Confirm order cancellation;
  * Confirm order/position modification;
  * Confirm position closing;
  * Confirm position reversing.
* Warnings – allows to enable the option 'Warn if application is closed'.
