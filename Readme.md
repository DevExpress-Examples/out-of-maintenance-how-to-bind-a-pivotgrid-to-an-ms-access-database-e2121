<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128578383/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2121)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/HowToBindToMDB/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/HowToBindToMDB/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/HowToBindToMDB/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/HowToBindToMDB/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Bind a PivotGrid to an MS Access Database


<p>The following example demonstrates how to bind the DXPivotGrid control to a View in the NWind.mdb database that is shipped with the installation. The control is used to analyze sales per countries, customers, product categories and years.</p><p>The example was created in four steps:<br />
1. A typed dataset is created from the database at design time.<br />
2. An instance of the SalesPersonDataTable and SalesPersonTableAdapter objects is created.<br />
3. The PivotGridControl is bound to the SalesPersonDataTable instance via the PivotGridControl.DataSource property.<br />
4. The table is filled with data in the Window_Loaded event handler.</p>

<br/>


