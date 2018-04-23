# How to: Bind a Pivot Grid to an Embedded XML File


<p>The following example demonstrates how to bind a pivot grid to an embedded XML file.</p><p>In this example, an XML file that contains data from the Northwind database is embedded into a Silverlight application. The System.Xml.Serialization.XmlSerializer object is used to parse this file and create a collection of data items. Then the pivot grid is bound to data by assigning this collection to the PivotGridControl.DataSource property. In the markup, four pivot grid fields are created, mapped to data fields using the PivotGridField.FieldName property and put into the appropriate pivot grid areas via the PivotGridField.Area property.</p><p>Classes that define a data item and a data item collection are declared in a separate file. The name and member set of the data item class match the declaration of the corresponding data element in the XML schema.</p><br />


<br/>


