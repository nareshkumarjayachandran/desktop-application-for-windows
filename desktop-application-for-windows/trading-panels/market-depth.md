# Market depth

The Market depth panel allows to view and trade Level II quotes. To open a new Market depth panel, go to Terminal -&gt; Market depth.

![](../../.gitbook/assets/37%20%281%29.png)

The Market depth panel consists of several sections:

* Level I - only Level I quotes;
* Position bar - short information about opened positions \(quantity, average price, current profit and loss\).



Selection between 'P/L by currency' and 'P/L by points' is available when 'Show offset in = Points' in the section 'Trading defaults' of the 'General settings'.

Position bar has extended functionality for Multiple position mode:

When clicking on the Price value, one of two options can be selected: 'Average open price' or 'Break-even'.

       Break-even = \(Long qty.\*Average long – Short qty.\*Average short\)/\(Long qty. – Short qty.\)

When clicking on QTY value, one of two options can be selected: Net QTY or Gross QTY.

       Net QTY = Qty1 + Qty2 + Qty3

       Gross QTY = \|Qty1\| + \|Qty2\| + \|Qty3\|

The color of QTY cell depends on a side of a position:

       a\) If all positions have Side = Long, qty. cell will be colored in blue;

       b\) If all positions have Side = Short, qty. cell will be colored in red;

       c\) If positions are multidirectional, then qty. cell is not colored;

       d\) If there are no positions, qty. cell will not be colored and qty. value = N/A.

* Quick trading bar - this function makes placing Stop or Limit orders very simple. Just choose the offset and click the corresponding button. The step option adjusts the offset buttons. In order to activate quick trading, click on the 'Quick trading' button located near 'Mouse trading' button, or choose the same option from the context menu;
* Detail quote section - this section includes the latest quotes data similar to Watchlist panel. But unlike Level I quotes, it shows the total volume at each price level. On the left side are bid volumes, and on the right one – ask volumes;
* Order entry is a compact bar similar to the 'Order entry' panel. It can be displayed in two ways: compact view \(showing only buttons and main boxes\) and extended view \(with explanation labels for buttons and boxes\). The quantity, type and TIF of an order, limit and stop price can all be adjusted here.



![](../../.gitbook/assets/38.png)



The detail quote section is displayed as a table with the following columns:

* MPID \(market participant ID\) – ECN or exchange, where the orders are set;
* Price – buy or sell price from the highest Bid and the lowest Ask to lower Bids and higher Asks;
* Size – the volume being offered to purchase at a specified Bid price or to sell at a specified Ask price;
* Time – time of offer;
* Avg. price – the price with slippage that appears because of low liquidity;
* Total size – the aggregated traded volume;
* Source – ECN or exchange, where orders are set. This field is similar to MPID, but it has another representation on the server. Is unavailable when 'Aggregate size by=By price level' is set up in the Market depth settings;
* Order – order number of this current price;
* CCY value – the value of Ask/Bid size expressed in the quote currency \(for example, "USD value"\), Price \* Ask/Bid size;
* CCY Total value – the value of total Ask/Bid size expressed in the quote currency \(for example, "USD value"\), Price \* Total Ask/Bid size.

### **Mouse trading**                    

Mouse trading – allows placing Limit/Stop orders with one click \(when the corresponding button is activated on the top of the panel Market depth\). With left mouse click you can place Buy orders, with right click – Sell orders. If an order is already placed, you can cancel it using right click on the order row.

You can switch the order type from Limit to Stop using the Hotkey \(can be set in General settings - &gt; Hotkeys - &gt; Market depth\).

To modify the pending order – simply drag it and drop at the needed price.

If mouse trading is enabled, then when hovering the cursor on the desired row, all columns will be highlighted.

If mouse trading is disabled, then when hovering the cursor on the desired row only active columns will be highlighted.

### **Active columns and substitution of parameters in OE**

* Size – when clicking on the Size column, the price and size values will be substituted in OE;
* Total size – when clicking on the Total size column, the price and total size values will be substituted in OE;
* Price – when clicking on the Price column, only the price value will be substituted in OE \(for Limit order – limit price, for the Stop limit order, Stop order, Tr. stop – stop price\).

![](../../.gitbook/assets/39%20%281%29.png)

### **Market depth settings**

#### **General settings**

#### **View**

![](../../.gitbook/assets/40.png)

*  Standard settings – Font, Grid;
* Show size in – 
* Round precision – 
* View by – 
* Highlight new order – 
* Mirror view – 
* Use Stop limit instead Stop – 
* Limit offset – 
* Show own orders – 
* Show toolbar – allows showing toolbar.

#### Colors

![](../../.gitbook/assets/41.png)



#### **Coloring methods**

The Market depth panel offers various coloring methods for Level 2 quotes. For setting up the coloring method, go to the Context menu - &gt; Settings - &gt; General - &gt; Colors. In this menu, the coloring method for each element is configured separately for the element text and background.

Depending on the selected criterion, there are six coloring methods available in the menu:

![](../../.gitbook/assets/42.png)

* By price level – coloring the quotes depending on price tier. The coloring is configurable for up to 5 tiers separately:

![](../../.gitbook/assets/43.png)

*  Relative to volume – Level 2 quotes are colored with the max volume getting the most saturated color. Allows setting the most saturated Ask and Bid colors:

![](../../.gitbook/assets/44.png)

*  Step to max volume – Level 2 quotes are colored so that the max volume set in the "Max volume" field has the most saturated color. Allows setting the most saturated Ask and Bid colors;

![](../../.gitbook/assets/45%20%281%29.png)

* By update time – the most recently updated Ask and Bid values are colored with the most saturated Ask and Bid colors set in the menu.

![](../../.gitbook/assets/46%20%281%29.png)

*  By source and volume conditions 

![](../../.gitbook/assets/47%20%281%29.png)

*  Size histogram

![](../../.gitbook/assets/51%20%281%29.png)



The colors for the text and background of the newly added order can be set in the menu.

![](../../.gitbook/assets/544.png)

* Buy/Sell color settings – allows to change colors in the Position bar \(Price and QTY\), when positions are Long/Short;
* Profit/Loss color settings – allows to change colors in the Position bar \(Price and QTY\), when P/L is positive/negative.
* Limit order/Stop order – allows to change colors of Limit and Stop orders.

#### **Monitored colors**

* Monitored price background - allows setting text and background colors for monitoring of the selected price;
* Monitored MPID background - allows setting text and background colors for monitoring of the selected MPID.

Select desired price or MPID - &gt; right click on it - &gt; set the monitor - &gt; this price or MPID will be highlighted with set monitored color.

#### **Additional**

The Additional tab of the Market depth settings looks as follows:

![](../../.gitbook/assets/53%20%281%29.png)



#### **Tab order**

![](../../.gitbook/assets/54%20%281%29.png)



The user can change the arrangement of the controls in the Tab order section \(and therefore the sequence of switching between the menu items\) by drag and dropping the items in the menu list with the mouse.


