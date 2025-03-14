---
description: >-
  Time and sales panel shows all executed trades for selected trading instrument
  in table form and provides details for each trade including date, time, price,
  quantity, and trade direction.
---

# Time & Sales

### What is Time and Sales

**Time & Sales** panel displays all trades that occur for selected instrument and provides details for each trade including date, time, price, and quantity. Each line is color-coded to indicate whether the trade was a result of an aggressive buyer or seller.

Time & Sales panel keeps a running record of trades for selected instruments displayed in chronological order. Each new entry is added to the top of the list, causing the panel screen to auto-scroll downward.

![Time & Sales panel in FundX shows all executed trades](../.gitbook/assets/time-and-sales.gif)

{% embed url="https://www.youtube.com/watch?v=-R_AXBMlNpM" %}
Aggregated Time & Sales in FundX also known as Reconstructed Tape
{% endembed %}

### Real-time and Historical modes

Real-time mode shows all the trades that are currently executed. The historical mode allows you to get all past trades for a specified period of time directly in the panel.

![Get all past trades in Time & Sales for a specified period](../.gitbook/assets/historical-mode-in-ts.png)

### General settings

The basic settings in Time & Sales are similar to the parameters of most panels in FundX — full flexibility in color settings, fonts, columns visibility, data position relative to the column, etc.&#x20;

<figure><img src="../.gitbook/assets/image (59).png" alt=""><figcaption><p>Time &#x26; Sales settings in FundX</p></figcaption></figure>

But some settings are unique for this panel:

* **Line Spacing** provides 3 options of raw formatting for better table view: **Compact, Normal, Double**
* **Rows limit** — this is the number of lines that will be displayed in the table, to save your computer's memory. When the number of lines exceeds the limit, old values will be deleted as new ones are added.
*   **Coloring scheme** — this option lets you choose the color scheme for all rows in the table based on a selected condition:\
    If you choose **“By Aggressor Flag”**, then for the trades with the Buy direction the line will be blue, and for the Sell trades, the line will be red. If the Aggressor flag is undefined (None), the color will be white.

    If you select **“By Tick Direction”**, the lines will be colored based on changes in the last price.
* **Aggregate Trades** — this mode helps you track large traders by summing up trades that match in price, direction, and time
* **Time Delay, ms** — it will continue to sum up data within the specified time with the same price and trade direction.
* **Short Price Format** reduces the amount of numbers in the price value to the left of the comma.

<figure><img src="../.gitbook/assets/Short prrice format TS.gif" alt=""><figcaption></figcaption></figure>

*   **The Abbreviation Rules** option gives you the ability to simplify the values of trading sizes for easier readability. There are 3 options for Format Mode:\
    \
    **Default:** This option displays values as is, without any abbreviation or rounding.\
    \
    **Round to:** This option rounds values after the decimal point to the specified number of decimal places.

    \
    **Abbreviate:** This option abbreviates values to the shortest form, such as "K" for thousands, "M" for millions, etc.

### Export Data

Time & Sales panel allows exporting executed trades to either _CSV_ or _HTML_ files for further analysis. In the future, we will add the ability to auto-update the data directly in the external file via DDE and RTD functions.

<figure><img src="../.gitbook/assets/image (364).png" alt=""><figcaption><p>T &#x26; S panel allows exporting data into external files</p></figcaption></figure>

* Select the "**Export Data**" in the panel's menu
* Select the necessary data that you want to export and click on the **\[Export File]** button
* Specify the type of files and the path to save it

### Setup Actions - Filters & Actions

We wrote about this functionality in the [**Advanced table filters and actions**](../general-settings/setup-actions-and-advanced-filters.md) section, which explains in details the process of adding filters and creating different notifications. Here we briefly describe the filtering process in the table and the settings of various actions.

#### Filtering in the Time & Sales table

Rows in the table can be filtered by some data value in their column. There are two ways to apply the filtering:

* **Quick filtering** can be accessed by clicking the “_**Filter**_” icon in any table column’s header.

![Quick filtering per column](../.gitbook/assets/quick-filtering.png)

Once you select some option — the table rows will be filtered to those ones, containing the selected value. Quick filter can be canceled by pressing “_**Cancel filtering**_” option.

{% hint style="info" %}
Quick filtering can be applied only to one column of the table. For filtering multiple columns, we recommend to use  “_**Setup actions**_”.
{% endhint %}

* **Advanced filtering,** for applying more complex filtering (multi-filtering). Select in the panel's context menu option “_**Setup actions**_”.&#x20;

<figure><img src="../.gitbook/assets/image (1) (4) (1).png" alt=""><figcaption></figcaption></figure>

This screen has two tabs on the left side, where the first one is an Advanced filter.

![Advanced filtering in Time\&Sales table](../.gitbook/assets/advanced-filtering.png)

This screen allows you to Enable/Disable filtering as well as set up filtering Conditions. These conditions are set up as:

&#x20;                                               _IF (condition1 AND condition2 ...) OR (conditionN...) …_

You can set up as many conditions as you like. Due to the possible complex logic of filtering, you are required to apply the changes once you finished the filter set up.

If you have additional questions or proposals about this functional, feel free to contact us. We are here to help you!
