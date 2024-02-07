Filter(SalesData;ThisRecord.Item=txt_Filter.Text)

Filter(SalesData;txt_Filter.Text in ThisRecord.Item)

Filter(SalesData;(txt_Filter.Text in ThisRecord.Item)&&(dd_Region.Selected.Value=ThisRecord.Region))


Filter(SalesData;(txt_Filter.Text in ThisRecord.Item)&&(ThisRecord.Region in cb_Region.SelectedItems))
