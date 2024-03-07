# LT Pointer Sync

This is a custom indicator code called 'LT Pointer Sync' developed by Forex Robot Easy Team. This code allows for enhanced synchronization of Forex charts by replicating the cross pointer across all open charts.

## How it Works

1. Initialization: The custom indicator is initialized by adding a middle mouse click event and an object edit event.
2. Mouse Move Event: When the middle mouse button is clicked and the mouse is moved, the indicator gets the mouse coordinates.
3. Chart Replication: The indicator replicates the cross pointer on all open charts except the current chart using the obtained mouse coordinates.
4. Object Edit Event: When an object is edited on the chart, the indicator checks the name of the object.
5. Horizontal or Vertical Line: If the object name contains 'H', it is identified as a horizontal line and its color is set to the specified HLineColor. If the object name contains 'V', it is identified as a vertical line and its color is set to the specified VLineColor.

## Product Description

The LT Pointer Sync indicator enhances Forex chart synchronization by replicating the cross pointer across multiple open charts. It provides a convenient way to analyze multiple charts simultaneously without the need to manually navigate and compare charts.

Key Features:
- Synchronization: Replicates the cross pointer position across open charts.
- Easy Comparison: Allows for easy comparison of price levels and patterns across multiple charts.
- Customizable Colors: The indicator allows for customizing the colors of horizontal and vertical lines.

Please note that Forex Robot Easy is not the official developer of this product. We provide this code as a sample that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - LT Pointer Sync Review](https://forexroboteasy.com/forex-robot-review/lt-pointer-sync-review-enhancing-forex-chart-synchronization/).
