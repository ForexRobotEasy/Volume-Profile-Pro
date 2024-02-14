# Volume Profile Pro

![Volume Profile Pro](https://forexroboteasy.com/wp-content/uploads/2022/01/Volume-Profile-Pro.jpg)

This is a custom indicator that calculates and displays the volume profile for a specified time period and number of bars. It is designed to visualize the support and resistance levels based on volume.

## Features

- Calculates volume profile for a specified time period and number of bars
- Displays the volume profile as a histogram on the chart
- Customizable histogram color and width

## How it works

The indicator uses the MQL5 library functions to calculate the volume profile. It first initializes by calculating the volume profile using the `iVolumeProfile` function. If the calculation is successful, it creates a histogram object using the `CChartObjectHistogram` class. The histogram object is then customized with the specified color and width.

In each iteration, the indicator checks if the volume profile is already displayed. If not, it calls the `DisplayVolumeProfile` function to calculate and display the volume profile. The function retrieves the number of price levels in the volume profile using the `iVolumeProfileInteger` function. It then loops through each price level, retrieves the volume and price range for each level, and adds a histogram bar using the `AddValue` method of the histogram object.

## Product Description

Volume Profile Pro is a powerful trading tool that visualizes the support and resistance levels based on volume. It calculates the volume profile for a specified time period and number of bars, and displays it as a histogram on the chart.

With Volume Profile Pro, you can easily identify key price levels where significant buying or selling activity has occurred. These levels can act as support or resistance, providing valuable insights for your trading decisions.

The indicator is highly customizable, allowing you to choose the time period and number of bars for the volume profile calculation. You can also customize the color and width of the histogram bars to suit your preference.

Please note that ForexRobotEasy is not the official developer of Volume Profile Pro. We are only showcasing a sample code that can work similarly to the described product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of Volume Profile Pro, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/volume-profile-pro-review-trading-visualization-support-levels/).

For more information and to purchase the official product, please visit [MQL5](https://www.mql5.com/).
