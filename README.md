<p align="center">
<img src="https://github.com/ColtonTrauCC/vm-network/assets/147654000/2cb238ff-4e46-4a75-8967-7ef5d124ab74" height="15%" width="15%" alt="Microsoft Azure logo"/>
</p>

<h1 align = "center">Basics of Azure Portal</h1>
This tutorial goes over how to use Microsoft Azure Portal as well as how to create/manage Resource Groups and Storage Accounts within Azure Portal.

<br />

<h2>Environments and Technologies Used</h2>

<ul>
  <li>Microsoft Azure Portal</li>
</ul>

</br>

<h2>List of Prerequisites</h2>
<ul>
  <li>Microsoft Azure Account and Subscription</li>
  <ul>
    <li><a href ="https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/mca-section-invoice#link-a-new-subscription">Free $200 Subscription Here</a></li>
  </ul>
</ul>

<br />

<h2>Essentials</h2>

<h3>Navigating Azure Portal</h3>

<p>
  <ul>
  <li>Upon logging into Azure Portal, the first page you should see is always the <b>Home Page</b></li> 
  <li>The Home Page offer multiple ways to access the Azure Portal's resources, one being the <b>Search Bar</b> at the top center and notable headings</li>
    <ul>
      <li><b>Azure Services</b> - The Services in Azure Portal that updates with most recent Resources used; all of Azure Portal's Services can be located on a seperate page by going to <i>More Services</i></li>
      <li><b>Resources</b> - A listing that displays and updates whenever Resources (<i>Resource Groups, Virtual Machines, Network Security Groups, etc.</i>) are created or recently modified</li>
      <li><b>Navigate</b> - A quality of life heading allowing users to easily navigate to the essentials of their account, notably Resources and Subscriptions</li>
      <li><b>Tools</b> - Heading that offers quick links to the infastructure and cost of the resources used in Azure as well as the online course <b>Microsoft Learn</b> for further education how to use Microsoft Azure</li>
      <li><img src ="https://github.com/ColtonTrauCC/azure-portal/assets/147654000/0efa1c1f-76d3-48ce-82a9-a86872e80418" width = 80% height = 80% /></li>
    </ul>
  </ul>
</p>

<br/>

<h3>Creating a Resource Group</h3>

<p>
  <ul>
    <li>Resource Groups serves as the base for many of Microsoft Azure's services and tools. To use Virtual Machines or Network Security Groups, you need a Resource Group.</li>
    <li>Head to the <b>Resource groups</b> page and click on <b>create</b></li>
    <li>Resource Groups have 3 fields for creation</li>
    <ul>
      <li><b>Basics</b> - Tab where you enter the name of your Resource Group and <b>Subscription</b> it is linked to for billing upon the use of Resources in that Group</li>
      <li><b>Tags</b> - Simple organizational tool for managing resources and view consolidated billing by applying the same tag to multiple resources and resource groups</li>
      <li><b>Review + Create</b> - Validation processing to check if credentials (notably a name) are filled and the Subscription is usable</li>
    </ul>
    <li>After validation passed, click on <b>Create</b> in the bottom and your Resource Group is created. Note: based on server speed and Internet connection, Resources and Resource Groups will take some time to deploy, take note of the <b>notification bell</b> at the top right to see when deployment is complete</li>
    <ul>
      <li><img src ="https://github.com/ColtonTrauCC/azure-portal/assets/147654000/523ad6cf-b830-4a49-9970-3d9edcf99171" width = 80% height = 80% /></li>
    </ul>
  </ul>
</p>

<br />

<h3>Creating and using the Storage Account</h3>

<p>
  <ul>
    <li>The <b>Storage Account</b> is a Resource in Microsoft Azure that serves as a general 500 TB storage unit for data in the cloud, more information <a href ="https://azure.microsoft.com/en-us/products/category/storage/">here</a></li>
    <li>First, have a simple image or txt file on hand for uploading</li>
    <li>Head to the <b>Storage account</b> page and click on <b>create</b></li>
    <li>Storage Accounts have multiple fields for creation</li>
    <ul>
      <li><b>Basics</b> - What Resourc Group the Resource will be in and instance details for the name of the storage account and determining performance</li>
      <li><b>Advanced</b> - Offers more complex options such as adjusting the security and protocols; some options are not available depending on your storage account's instance details from Basics</li>
      <li><b>Networking</b> - Connectivity and Routing options</li>
      <li><b>Data Protection</b> - Enables how data is recovered and tracked in storage</li>
      <li><b>Encryption</b> - Determines how data is encrpted, uses Microsoft-managed keys by default</li>
      <li><b>Tags</b> - Same as creation of tags in Resource Group creation</li>
      <li><b>Review</b> - checking validation and overview of the Resource's information</li>
    </ul>
    <li>After inputting information, click on <b>Create</b> to create the resource and wait for deployment to finish</li>
    <li>Now to store data in the Storage Account, we need to create a <b>container</b> by going to the Storage Account you made and navigating to <b>Containers</b> under <b>Data Storage</b>. Click on <b>(Plus Sign) Container</b> and enter information in the window on the right</li>
    <ul>
      <li><img src= "https://github.com/ColtonTrauCC/azure-portal/assets/147654000/ff9d532a-eb33-4a0f-a9be-709cd8a5b06b" /></li>
    </ul>
    <li>Through here it's self explanitory as you use the <b>Upload</b> icon in the container to upload files in selected container. If your file is a coding language or txt file, you can edit its information through Azure</li>
  </ul>
</p>

<br />

<h2>Clean Up</h2>

<p>
  <ul>
    <li>If no longer used, it is best to delete Resource Groups and it Resource to prevent billing from stacking up.</li>
    <li>Head to the Resource Group and select <b>Delete</b> to open a window on the right. Deletion of the Resource Group require verification by entering its name, it's also convenient since it deletes all resources in that group</li>
    <ul>
      <li><img src ="https://github.com/ColtonTrauCC/azure-portal/assets/147654000/6d0f216d-f7fb-4409-98d0-aa7bb4d9c7b6"/></li>
    </ul>
  </ul>
</p>
