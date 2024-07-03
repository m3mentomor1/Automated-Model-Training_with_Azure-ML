<div align="center">
  <h1>Automated Model Training with Azure ML Studio</h1>
</div>

**1. Create a workspace:**

> ![Workspace](https://github.com/m3mentomor1/Automated-Model-Training_with_Azure-ML-Studio/assets/95956735/efce2078-305c-49b5-acf6-219346e1dcd2)

- Click ``Create workspace``.<br><br>
- In the **Name** section, enter a name for your workspace. (***Note:** You can choose any name, but for this project, it will be named "Demo".*)<br><br>
- In the **Resource group** section, select an existing resource group from your Azure account or create a new one by clicking ``Create new``. This resource group will store the instance for your Azure ML Studio workspace.<br><br>
- In the **Region** section, choose the region where you want your workspace to be deployed. (***Note:** Select a region based on accessibility and availability. For this project, it will be deployed in "East US 2" due to its high availability.*)<br><br>
- Click ``Create``.

<br>

**2. Upload a dataset:**


> ![Workspace](https://github.com/m3mentomor1/Automated-Model-Training_with_Azure-ML-Studio/assets/95956735/efce2078-305c-49b5-acf6-219346e1dcd2) (***Note:** For this project, we will use this [dataset](https://github.com/m3mentomor1/Automated-Model-Training_with_Azure-ML-Studio/blob/main/bankmarketing_train.csv).*)

- In the **Assets** section, go to **Data**.<br><br>
- In the **Data** page, click ``+ Create``.<br><br>
- In the **Name** section, enter a name for your data asset (***Note:** You can choose any name, but for this project, it will be named "bankmarketing".*). Next, in the **Type** section, select the type of data stored in your dataset. (***Note:** For this project, the type of data we'll use is "Tabular".*). After that, click ``Next``.<br><br>
- Select the source from which your dataset will be imported by choosing a source for your data asset. (***Note:** For this project, we'll select "From local files".*). After that, click ``Next``.<br><br>
- In the **Datastore type** section, select the type of storage where you will store your dataset. (***Note:** For this project, we'll use the default, which is "Azure Blob Storage".*).

<br>

**3. Create an automated Machine Learning job:** 


 


 







