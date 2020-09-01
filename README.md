# paywitheasebuzz-xamarin-lib
Xamarin integration kit for pay with easebuzz pay.easebuzz.in


# Basic steps to integrate PaywithEaseBuzz payment kit for xamarin.

 1. Bind peb-lib.aar file in your Xamarin project using the below step's.<br/>

	- Create a new Bindings Library project starting with the Android Bindings Library template.
	- Add the AAR file to the project.
	- Set the Build Action to LibraryProjectZip of AAR file.
	- Choose a target framework that the AAR supports.
	- Build the Bindings Library.

 2. Install following native android dependencies using Xamarin Package Manager Commands.<br/>
	(Package Manager console can be found in Tools->NuGet Package Manage - > Package Manager Console) <br/>
 	Execute below commands on Package Manager Console <br/>

                - Install-Package Square.Retrofit2 -Version 2.4.0.1,
                - Install-Package Square.OkHttp -Version 2.4.0,
                - Install-Package Square.OkHttp.UrlConnection -Version 2.7.5.1 
		- Install-Package Square.Retrofit2.ConverterGson -Version 2.4.0.1 

  ## Note:
  Add below line into Name of Android binding library →  Transforms -> Metadata.xml <br/>
	
	<remove-node path="/api/package[@name='helper']/class[@name='PWEDownloadImageManager']" />
        <remove-node path="/api/package[@name='datamodels']/class[@name='DiscountCodeDataModel']"/>
        <remove-node path="/api/package[@name='custom_ui_components.loader']/class[@name='PWELoaderAnimation.10']"/>
        <remove-node path="/api/package[@name='custom_ui_components.loader']/class[@name='PWELoaderAnimation.11']"/>
	
                                         
 3. Sample Integration code

##### The step by step detailed procedure to integrate the kit is mentioned in the documentation.pdf file. You can download it from 
  https://github.com/easebuzz/paywitheasebuzz-xamarin-lib/blob/master/documentation.pdf.

               
