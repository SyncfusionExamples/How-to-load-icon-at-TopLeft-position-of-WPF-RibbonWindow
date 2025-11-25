# How to load icon at TopLeft position of WPF RibbonWindow?

This sample shows the demo on how to use Office2010 icon property in [RibbonWindow](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Tools.Controls.RibbonWindow.html).

You can set the icon at the TopLeft position in [RibbonWindow](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Tools.Controls.RibbonWindow.html) by using the [Office2010Icon](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Tools.Controls.RibbonWindow.html#Syncfusion_Windows_Tools_Controls_RibbonWindow_Office2010Icon) property.


## Project setup
1. Create a Resources folder in your WPF project.
2. Add the required icon to the Resources folder.
3. Set the icon’s Build Action to Resource in Properties.
4. Ensure Syncfusion WPF packages are referenced.

## Code snippet
Use the following snippet to configure the RibbonWindow with an icon and theme:

```xml
<syncfusion:RibbonWindow x:Class="Office2010Icon_Ribbon.MainWindow"
       xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
       xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
       Office2010Icon="Resources/TitleIcon.png" 
       syncfusion:SkinStorage.VisualStyle="Office2013"
       xmlns:syncfusion="http://schemas.syncfusion.com/wpf"
       WindowStartupLocation="CenterScreen"            
       Title="Office2010Icon_Ribbon" Height="350" Width="525" TitleTextAlignment="Center">
   <Grid>
      <Grid.RowDefinitions>
         <RowDefinition Height="auto" />
         <RowDefinition Height="*" />
      </Grid.RowDefinitions>
      <syncfusion:Ribbon>
      </syncfusion:Ribbon> 
   </Grid>
</syncfusion:RibbonWindow>
```


KB article - [How to load icon at TopLeft position of WPF RibbonWindow?](https://www.syncfusion.com/kb/10244/how-to-set-icon-at-the-topleft-position-in-wpf-ribbonwindow)
