# Use-an-Apache-Spark-notebook-in-a-pipeline
In this exercise, we're going to create an Azure Synapse Analytics pipeline that includes an activity to run an Apache Spark notebook..
# Lab11 - Use an Apache Spark Notebook in a Pipeline

In this lab, you will create a pipeline in **Azure Synapse Analytics** that includes an activity to run an **Apache Spark notebook**. This allows you to automate and schedule data processing tasks using Synapse Pipelines.

---

## 📌 Objective

- Learn how to run Apache Spark notebooks within Synapse Pipelines  
- Automate and orchestrate data processing workflows  
- Integrate notebooks into a production-ready pipeline system

---

## 🛠️ Prerequisites

- An active Azure account
- Azure Synapse Analytics workspace
- A pre-created or existing Spark Notebook
- Permissions to create and manage pipelines

---

## 📋 Steps

### 1. Prepare the Spark Notebook
- Open **Azure Synapse Studio**.
- Navigate to the **Develop** hub and create a new **Notebook**, or use an existing one.
- The notebook should include data read, transformation, or visualization logic.
- Save the notebook and ensure it runs successfully.

### 2. Create a Pipeline
- Go to the **Integrate** hub.
- Click on **+** > **Pipeline** to create a new pipeline.

### 3. Add a Notebook Activity
- Drag a **Notebook** activity into the pipeline canvas.
- In the activity settings:
  - **Notebook**: Select the notebook you prepared earlier.
  - **Spark pool**: Choose the Spark pool where the notebook will run.
  - Set any required parameters if your notebook uses them.

### 4. Save and Publish the Pipeline
- Click **Save** to store the pipeline.
- Then click **Publish All** to apply the changes.

### 5. Trigger the Pipeline
- Manually trigger the pipeline or set up a trigger for scheduled execution.
- Monitor the pipeline run to ensure the notebook executes as expected.

---

## ✅ Expected Outcome

- The Apache Spark notebook is successfully triggered from the Synapse pipeline
- Data processing steps in the notebook complete without errors
- Run history shows successful execution and output logs

---

## Screenshots

![Lab11](https://github.com/user-attachments/assets/721c4c32-589b-42b7-8b0b-4e06af722a3d)
![Lab11saved](https://github.com/user-attachments/assets/50d68573-020b-498d-bcf5-28babfafa7ae)
![Lab11saved2](https://github.com/user-attachments/assets/c67f43fd-e6cf-43d3-bcbd-33b4e3c94307)
![lab11format](https://github.com/user-attachments/assets/b2006d24-d362-4c81-89a2-907914eaa6c9)
![lab11format2](https://github.com/user-attachments/assets/ea73e8d6-c189-4d71-b1ea-54a8791657a2)
![lab11clear](https://github.com/user-attachments/assets/3e30a217-3266-4e73-978d-6e4849f102db)
![lab11cell1](https://github.com/user-attachments/assets/eeda5cac-ae56-48d7-9044-d919735f7348)
![lab11cell2](https://github.com/user-attachments/assets/de1af2ab-c4a1-47b1-8043-735869ce4481)
![lab11pipline](https://github.com/user-attachments/assets/3c326efc-7b09-4d33-8ea9-62513fe98552)
![lab11pipline2](https://github.com/user-attachments/assets/40a98737-8323-4251-8df8-1f347d79e457)
![lab11pipelineruns](https://github.com/user-attachments/assets/ce6fb007-7f7e-4277-a25a-12b6c738e616)
![lab11pipelineruns2](https://github.com/user-attachments/assets/1b3dd0a5-52ae-4dbe-a24a-f698ded9fb8e)
![lab11pipelineruns3](https://github.com/user-attachments/assets/c0e3b683-edc8-4d56-9c97-651d419528d2)
