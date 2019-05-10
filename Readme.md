<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/IExternalAppointmentCompareSample/Form1.cs) (VB: [Form1.vb](./VB/IExternalAppointmentCompareSample/Form1.vb))
* [MyAppointmentComparer.cs](./CS/IExternalAppointmentCompareSample/MyAppointmentComparer.cs) (VB: [MyAppointmentComparer.vb](./VB/IExternalAppointmentCompareSample/MyAppointmentComparer.vb))
<!-- default file list end -->
# How to sort Appointments with the same time interval


--------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------
SchedulerControl supports the  <a href="https://www.devexpress.com/subscriptions/new-2019-1.xml#xtrascheduler"><u>custom sorting and groping functionality</u></a> starting with version 19.1. You can find more about this functionality in the <a href="http://newdoc.devexpress.devx/WindowsForms/1753/controls-and-libraries/scheduler/appointments?v=19.1#group-and-sort-appointments"><u>Group and Sort Appointments</u></a> documentation and test it using this <a href="dxdemo://Win/XtraScheduler/MainDemo/TimelineViewModule"><u>Demo</u></a>. Please note that this demo requires installation of WinForms Subscription v19.1, which can be downloaded there: <a href="https://www.devexpress.com/ClientCenter/DownloadManager/"><u>Download</u></a>.
---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------

<p>This example illustrates how to sort Appointments with the same time interval. This can be useful if you wish to sort all-day appointments (or daily appointments with the same Start and End values) by your custom rule.</p><p>This functionality may be introduced by implementing a custom <strong>DevExpress.XtraScheduler.Services.Internal.IExternalAppointmentCompareService</strong> service.</p>

<br/>


