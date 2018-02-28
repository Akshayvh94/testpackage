## **Scenario 2 - Setting up the Jenkins VM**

 To configure Jenkins, the Jenkins VM image available on the Azure MarketPlace will be used. This will install the latest stable Jenkins version on a Ubuntu Linux VM along with the tools and plugins configured to work with Azure.

 1. [Click here to open the Azure portal](https://portal.azure.com) and maximize the browser window

 1. In the **Email or phone** field, enter **<inject key="AzureAdUserEmail" />** and click **Next**

 1. In the **Password** field, enter **<inject key="AzureAdUserPassword" />**

 1. Click **Sign in**

 1. You _may_ encounter a popup entitled **Stay signed in?** with buttons for **No** and **Yes** - Choose **No**

 1. You _may_ encounter a popup entitled **Welcome to Microsoft Azure** with buttons for **Start Tour** and **Maybe Later** - Choose **Maybe Later**

 1. Click on **+ Create a reaource** on the left side blade, search for **Jenkins**.

 1. Select **Jenkins** in the search result blade

 1. In **Everything** blade, select first result **Jenkins** and click on **Create** button

 1. In **Create Jenkins** blade **Configure Basic Setting** would be selected

 1. In Name field Enter **jenkins**

 1. In User Name field Enter **jenkinsadmin**. 
 
 1. Make sure that Authentication Type is selected to **Password**

 1. In Password field enter **P2ssw0rd@123**. Enter the same in Confirm Password filed.

 1. Make sure that subscription field is set to **Visual Studio Enterprise**

 1. Select Resource Group **Use Existing**

 1. Select location **South Central US**

 1. Once ypu filled all the fields, click on **OK***

 1. On additional setting tab select the size **Standasr DS2 V2**

 1. Select VM Disk Type to **HDD**

 1. Fill the Domain Name Label **jenkisndomain**. if the domain is not available append the name with some digits.
1.  Leave the rest of the field as it is and click on *OK*

1. On the Integration Setting Tab, make sure that Service Principal Integration is set to **Auto(MSI)** and Enable Cloud Agent set to **VM**

1. On the summary ta make sure that all the details are corrcet. Click on **OK**

1. On the Buy tab, read the agreement and click on **Create** button.

1. Jenkis VM will be provisoined.
