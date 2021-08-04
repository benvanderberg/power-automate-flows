# webform-list-to-excel
This flow uses Adobe Sign connector and an HTTP connector to make a call to the Adobe Sign API to get the list of Web Forms and write it to an Excel spreadsheet.

## Installation
1. Go to [Microsoft Power Automate](https://flow.microsoft.com) and click on **My flows**.
2. Click on **Import**.
3. Select the *webform-list-to-excel.zip* file.
4. Click on the Configuration Wrench icon to configure the *Excel Online (Business) connector*.
5. Choose your connection.
6. Click **Save**.
7. Click **Import**.
8. Click on **My flows**.
9. Click on *Get Web Form ID* flow.
10. Click on **Turn On**.
11. Click on **Edit**.


### Configure integration key variable
1. When editing the flow, expand the **integrationKey** action.
2. Set the integration key for your account. 

If you don't have an integration key, you can learn how to get one [here](https://helpx.adobe.com/sign/kb/how-to-create-an-integration-key.html).

### Configure Excel file
In order to import values into an Excel file, you will need to have your Excel file have a table in it. You can learn how to create a table [here](https://support.microsoft.com/en-us/office/create-a-table-in-excel-bf0ce08b-d012-42ec-8ecf-a2259c9faf3f).

Some of the recommended columns are the following:
- ID
- URL
- Modified Date
- Status
- Group ID

To configure your Excel file, do the following:
1. Expand the *Apply to each* action.
2. Expand the *Add a row into a table*.
3. Set the following for where your Excel is located:
   *  Location
   *  Document Library
   *  File
   *  Table
4. Click **Save** in the top right corner.

### Run flow
If you are in the editing mode, click **Test** > **Manually** and then click the **Test** button. When prompted, click **Continue**.