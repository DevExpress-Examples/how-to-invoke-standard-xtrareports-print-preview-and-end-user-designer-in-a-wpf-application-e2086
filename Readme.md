<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfXtraReports/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfXtraReports/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfXtraReports/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfXtraReports/MainWindow.xaml.vb))
<!-- default file list end -->
# How to invoke standard XtraReports Print Preview and End-User Designer in a WPF application

# In WPF applications, use our [Document Preview](https://docs.devexpress.com/WPF/DevExpress.Xpf.Printing.DocumentPreviewControl) and the [End-User Report Designer](https://docs.devexpress.com/XtraReports/114104/create-end-user-reporting-applications/wpf-reporting/end-user-report-designer). See [WPF Reporting](https://docs.devexpress.com/XtraReports/9830/create-end-user-reporting-applications/wpf-reporting) for more information.

[Original message]
<p>The following example demonstrates how to preview and edit reports, created by the XtraReports suite, in a WPF application.<br /><br /><strong>Important note: </strong>the use of this example requires the WinForms part of our Reporting tools that is not included into WPF subscription. If you wish to use this functionality, it is required to own WinForms, Reporting, DXperience, or Universal subscription.</p>


<h3>Description</h3>

<p>In this example, an XtraReport class descendant has been added to a WPF application. This report contains two simple labels, which display data from a report&#39;s data source populated from the <strong>Contacts.mdb</strong> file on a local disk.</p><p>To display a report&#39;s Print Preview, call the <strong>ShowPreview</strong> or <strong>ShowPreviewDialog</strong> method of a <strong>ReportPrintTool</strong> in a window&#39;s code behind. To run the End-User Report Designer, call the <strong>ShowDesigner</strong> or <strong>ShowDesignerDialog</strong> method of a <strong>ReportDesignTool</strong>.</p>

<br/>


