---
title: Download Product Files
page_title: Download Product Files
description: This article will demonstrate how you can navigate through your account to download Telerik UI for WPF assemblies, examples, etc.
slug: download-product-files-wpf
tags: download, files, installation
published: True
position: 2
site_name: WPF
---

# Download Product Files

When you have an active trial or developer license, you can download the following files:

* Standalone installation
* Assemblies and themes only
* Latest internal builds
* Documentation files
* Old versions
* Source code – available only with a developer license

>Check the [Trial License Limitations]({%slug installation-installing-license-limitations-wpf%}) topic for more details on the available licenses.

In order to download these you need to take the following steps:

1. Log into your [Telerik account](https://www.telerik.com/account/).

2. Click on the __Downloads__ tab:

	![{{ site.framework_name }} Progress Site Downloads Tab](images/Download_product_files_0.png)

3. Select __Telerik UI for WPF__ product title:
	
	![{{ site.framework_name }} Progress Site Telerik UI for WPF Product Title](images/Download_product_files_1.png)

4. The next page allows you to download the Automatic Installation msi file, DLLs and themes, PDB files, NuGet Packages, documentation files, and Source code. 

	![{{ site.framework_name }} Progress Site Telerik UI for WPF Product Page](images/Download_product_files_2.png)

Below you could find a list of the available files:

>[license] could be Trial or Dev depending on the license you have.

>[version] is replaced with the version the file corresponds to.

### Installation

* Telerik_UI_for_WPF_[version]_[license].msi&mdash;Automatic installation, check [Installing Telerik UI for WPF from MSI file]({%slug installation-installing-from-msi-wpf%}) for more details.

### Other Setup Files

* Telerik_UI_for_WPF_[version]_[license]_Hotfix.zip&mdash;Used for manual installation, for more details check [Installing Telerik UI for WPF from ZIP file]({%slug installation-installing-from-zip-wpf%}).
* Telerik_UI_for_WPF_[version]_Themes.zip&mdash;Contains two folders containing the default styles and templates for the controls when using the [Xaml and NoXaml]({%slug xaml-vs-noxaml%}) binaries. You need to use the resources from the `Themes.Xaml` folder when using the [StyleManager]({%slug styling-apperance-implicit-styles-overview%}#setting-a-theme-using-stylemanager) approach for theming the controls and the ones from `Themes.NoXaml` when using [implicit styles]({%slug styling-apperance-implicit-styles-overview%}#setting-a-theme-using-implicit-styles).
* Telerik_UI_for_WPF_[version]_[license]_PDBs.zip
* Telerik_UI_for_WPF_[version]\_NuGet_Xaml_[license].zip
* Telerik_UI_for_WPF_[version]\_NuGet_NoXaml_[license].zip 
* Telerik_UI_for_WPF_[version]\_NuGet_Separate_Packages_Xaml_[license].zip
* Telerik_UI_for_WPF_[version]\_NuGet_Separate_Packages_NoXaml_[license].zip 

In versions prior Q1 2024, there is a .zip file with digitally signed version of the Telerik assembles - __Telerik_UI_for_WPF_[version]_[license]_Hotfix_DIGITALLY_SIGNED.zip__. With the Q1 2024 release __all Telerik dlls are digitally signed__ and there is no need of a separate package, which is why this .zip is no longer distributed.

>Check [Setting a theme]({%slug styling-apperance-implicit-styles-overview%}) topic for more information on the Xaml and NoXaml binaries.

>tip Check [Installing UI from a Nuget package]({%slug nuget-installation%}) for more details on using the provided packages.

### Documentation

This section contains the offline documentation as well as the ApiReference (both as CHM and Help3) of Telerik UI for WPF and [DocumentProcessing](https://docs.telerik.com/devtools/document-processing/introduction) products.

* Telerik_UI_for_WPF_Documentation_Help3_[version].zip
* Telerik_UI_for_WPF_Documentation_[version].chm
* Telerik_UI_for_WPF_ApiReference_[version].chm
* Telerik_Document_Processing_Documentation_[version].chm
* Telerik_Document_Processing_ApiReference_[version].chm
* Telerik_Document_Processing_Documentation_Help3_[version].zip
* Telerik_Document_Processing_ApiReference_Help3_[version].zip
* Telerik_UI_for_WPF_ApiReference_Help3_[version].zip

### Resources

You could download the complete source code of the [WPF Demos application]({%slug installing-wpf-demos %}) as well as the provided sample applications.

* Telerik_UI_for_WPF_[version]_Demos.zip
* ColorThemeGenerator_WPF_[license]_[version]_SourceCode.zip
* CRM_WPF_[license]_[version]_SourceCode.zip
* ERP_WPF_[license]_[version]_SourceCode.zip
* OutlookInspiredApp_WPF_[version]_SourceCode.zip

### Source Code

* Telerik_UI_for_WPF_Source_[version].zip&mdash;Complete source code of the Telerik UI for WPF product, available only with Developer license. With the 2023 R2 release, this .zip file will no longer contain the Telerik Document Processing product in it.
* Telerik_UI_for_WPF_[Version]_DPL_Source.zip&mdash;Complete source code of the Telerik Document Processing product, available only with Developer license.

## Available versions

From the __Versions__ dropdown you can select an older version to download:

![{{ site.framework_name }} Progress Site Telerik UI for WPF Available Versions](images/Download_product_files_3.png)

>important Please note that if you do not see the desired version you can contact our [sales team](mailto:sales@telerik.com) and they will enable the version for download.

## See Also

 * [Installing Telerik UI for WPF from MSI File]({%slug installation-installing-from-msi-wpf%})

 * [Installing Telerik UI for WPF from ZIP File]({%slug installation-installing-from-zip-wpf%})

 * [Installing Telerik UI for WPF from a NuGet package]({%slug nuget-installation%})
