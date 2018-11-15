<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/HowToBindToMDB/MainWindow.xaml) (VB: [MainWindow.xaml.vb](./VB/HowToBindToMDB/MainWindow.xaml.vb))
* [MainWindow.xaml.cs](./CS/HowToBindToMDB/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/HowToBindToMDB/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Bind a PivotGrid to an MS Access Database


<p>The following example demonstrates how to bind the DXPivotGrid control to a View in the NWind.mdb database that is shipped with the installation. The control is used to analyze sales per countries, customers, product categories and years.</p><p>The example was created in four steps:<br />
1. A typed dataset is created from the database at design time.<br />
2. An instance of the SalesPersonDataTable and SalesPersonTableAdapter objects is created.<br />
3. The PivotGridControl is bound to the SalesPersonDataTable instance via the PivotGridControl.DataSource property.<br />
4. The table is filled with data in the Window_Loaded event handler.</p>

<br/>


