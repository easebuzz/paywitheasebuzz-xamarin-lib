# paywitheasebuzz-xamarin-lib
Xamarin integration kit for pay with easebuzz pay.easebuzz.in


# Basic steps to integrate PaywithEaseBuzz payment kit for xamarin.

 1. Download and install EasebuzzAndroidBinding in your xamarin project.<br/>
	- Add binding library reference into reference section of android app.

 2. Install following native androidx dependencies using Xamarin Package Manager Commands.<br/>
	(Package Manager console can be found in Tools->NuGet Package Manage - > Package Manager Console) <br/>
 	Execute below commands on Package Manager Console <br/>

		- Install-Package Xamarin.Google.Android.Material -Version 1.3.0
		- Install-Package Square.OkHttp -Version 2.7.5.1
		- Install-Package Xamarin.AndroidX.MultiDex -Version 2.0.1.10
		- Install-Package Square.OkHttp.UrlConnection -Version 2.7.5.1
		- Install-Package Xamarin.Android.SquareUp.Retrofit2 -Version 2.9.0
		- Install-Package Square.Retrofit2.ConverterGson -Version 2.9.0
		- Install-Package Xamarin.GooglePlayServices.Auth -Version 119.2.0.2
		- Install-Package Xamarin.GooglePlayServices.Auth.Api.Phone -Version 117.5.1.2

                                         
 3. Sample Integration code

##### The step by step detailed procedure to integrate the kit is mentioned in the documentation.pdf file. You can download it from 
  https://github.com/easebuzz/paywitheasebuzz-xamarin-lib/blob/master/documentation.pdf.

               
