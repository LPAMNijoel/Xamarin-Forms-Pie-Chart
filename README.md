# Xamarin-Forms-Pie-Chart

 Enrich your mobile application with Pie Charts.
  
Supported platforms:

      1) Xamarin for Android
      2) Windows Phone Silverlight
      3) Windows Phone RT
      4) Windows Store
      iOS is not supported yet!
      
<img src="https://github.com/HoussemDellai/Xamarin-Forms-Pie-Chart/blob/master/Screenshots/CrossPieCharts_screenshot.png?raw=true"/>

To add a Pie Chart control from your Xamarin Forms project (XAML or CSharp):

var crossPieChartView = new CrossPieChartView<br/>
{<br/>
&nbsp;			Progress = 60,<br/>
&nbsp;  		ProgressColor = Color.Green,<br/>
&nbsp;  		ProgressBackgroundColor = Color.Gray,<br/>
&nbsp;  		StrokeThickness = Device.OnPlatform(10, 20, 80),<br/>
&nbsp;  		Radius = Device.OnPlatform(100, 180, 160),<br/>
&nbsp;  		BackgroundColor = Color.White<br/>
};<br/>
                       
Here is a video that shows how to install and use the plugin : https://www.youtube.com/watch?v=9alb3AFHkRs

The nuget package is available at : https://www.nuget.org/packages/Xam.FormsPlugin.CrossPieChart/

This plugin was built developed using existing work from:

James Montemagno : https://github.com/jamesmontemagno/MonoDroidToolkit/wiki/HoloCircularProgressBar/

Timo Korinth : http://timokorinth.de/creating-circular-progress-bar-wpf-silverlight/
