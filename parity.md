<h1>Sovereign Cloud Parity</h2>

Currently Azure Machine Learning is deployed into two sovereign clouds: 1) USGOV with regions US-Arizona + US-Virginia, and 2) Azure China in region: China-East-2. We aim to provide maximum parity between our sovereign and commercial clouds. 

All Azure Machine Learning features will be available in Sovereign clouds within 30 days of GA (general availability) of our commercial cloud. We also currently enable a select number of preview features in our sovereign cloud as well.  Below display the current parity differences between our sovereign and commercial clouds.



<h2>USGOV Parity</h2>	

| FEATURES                                                                   | Commercial Status | USGOV Availability    |-------------|
|----------------------------------------------------------------------------|----------------------|--------------------|-------------|
| <h4>Automated machine learning</h4>                                        |                      | <h4>US-Virginia</h4>        |<h4>US-Arizona</h4>|
| Create and run experiments in notebooks                                    | GA                   | YES                | YES         |
| Create and run experiments in studio web experience                        | Public Preview       | YES                | YES         |
| Industry-leading forecasting capabilities                                  | GA                   | YES                | YES         |
| Support for deep learning and other advanced learners                      | GA                   | YES                | YES         |
| Large data support (up to 100 GB)                                          | Public Preview       | YES                | YES         |
| Azure Data bricks Integration                                              | GA                   | NO                 | NO          |
| SQL, CosmosDB and HDInsight integrations                                   | GA                   | YES                | YES         |
| <h4>Machine Learning pipelines</h4>                                        |                      | <h4>US-Virginia </h4>        |<h4> US-Arizona</h4>|  
| Create, run and publish pipelines using the Azure ML SDK                   | GA                   | YES                | YES         |
| Create pipeline endpoints using the Azure ML SDK                           | GA                   | YES                | YES         |
| Create, edit and delete scheduled runs of pipelines using the Azure ML SDK | GA                   | YES*               | YES*        |
| View pipeline run details in studio                                        | GA                   | YES                | YES         |
| Create, run, visualize and publish pipelines in Azure ML designer          | Public Preview       | YES                | YES         |
| Azure Data bricks Integration with ML Pipeline                             | GA                   | NO                 | NO          |
| Create pipeline endpoints in Azure ML designer                             | Public Preview       | YES                | YES         |
| <h4>Integrated notebooks </h4>                                             |                      | <h4>US-Virginia </h4>        |<h4>US-Arizona</h4>|
| Workspace notebook and file sharing                                        | GA                   | YES                | YES         |
| R and Python support                                                       | GA                   | YES                | YES         |
| Virtual Network support                                                    | Public Preview       | NO                 | NO          |
| <h4>Compute instance </h4>                                                 |                      | <h4>US-Virginia  </h4>       |<h4>US-Arizona</h4>|
| Managed compute Instances for integrated Notebooks                         | GA                   | YES                | YES         |
| Jupyter, JupyterLab Integration                                            | GA                   | YES                | YES         |
| Virtual Network (VNet) support                                             | Public Preview       | YES                | YES         |
| <h4>SDK support    </h4>                                                   |                      | <h4>US-Virginia  </h4>       |<h4>US-Arizona</h4>|
| R SDK support                                                              | Public Preview       | YES                | YES         |
| Python SDK support                                                         | GA                   | YES                | YES         |
| <h4>Security   </h4>                                                       |                      | <h4>US-Virginia</h4>         |<h4>US-Arizona </h4>|
| Virtual Network (VNet) support for training                                | GA                   | YES                | YES         |
| Virtual Network (VNet) support for inference                               | GA                   | YES                | YES         |
| Scoring endpoint authentication                                            | Public Preview       | YES                | YES         |
| Workplace Private link                                                     | Public Preview       | NO                 | NO          |
| ACI behind Vnet                                                            | Public Preview       | NO                 | NO          |
| ACR behind Vnet                                                            | Public Preview       | NO                 | NO          |
| Private IP of AKS cluster                                                  | Public Preview       | NO                 | NO          |
| <h4>Compute </h4>                                                          |                      | <h4>US-Virginia </h4>       | <h4>US-Arizona </h4> |
| quota management across workspaces                                         | GA                   | YES                | YES         |
|<h4> Data for machine learning</h4>                                         |                      | <h4>US-Virginia</h4>        | <h4>US-Arizona </h4> |
| Create, view or edit datasets and datastores from the SDK                  | GA                   | YES                | YES         |
| Create, view or edit datasets and datastores from the UI                   | GA                   | YES                | YES         |
| View, edit or delete dataset drift monitors from the SDK                   | Public Preview       | YES                | YES         |
| View, edit or delete dataset drift monitors from the UI                    | Public Preview       | YES                | YES         |
| <h4>ML Lifecycle  </h4>                                                    |                      | <h4>US-Virginia</h4>        | <h4>US-Arizona </h4> |
| Model profiling                                                            | GA                   | YES                | PARTIAL     |
| The Azure DevOps extension for Machine Learning & the Azure ML CLI         | GA                   | YES                | YES         |
| FPGA based Hardware Accelerated Models                                     | GA                   | NO                 | NO          |
| Visual Studio Code integration                                             | Public Preview       | NO                 | NO          |
| Event Grid integration                                                     | Public Preview       | NO                 | NO          |
| Integrate Azure Stream Analytics with Azure Machine Learning               | Public Preview       | NO                 | NO          |
| <h4>Labelling </h4>                                                        |                      | <h4>US-Virginia</h4>        | <h4>US-Arizona</h4>  |
| Labelling Project Management Portal                                        | GA                   | YES                | YES         |
| Labeller Portal                                                            | GA                   | YES                | YES         |
| Labelling using private workforce                                          | GA                   | YES                | YES         |
| ML assisted labeling (Image classification and Object detection)           | Public Preview       | YES                | YES         |
| <h4>Responsible ML   </h4>                                                 |                      | <h4>US-Virginia  </h4>      | <h4>US-Arizona</h4>  |
| Explainability in UI                                                       | Public Preview       | NO                 | NO          |
| Differential privacy WhiteNoise toolkit                                    | OSS                  | NO                 | NO          |
| custom tags in Azure Machine Learning to implement datasheets              | GA                   | NO                 | NO          |
| Fairness AzureML Integration                                               | Public Preview       | NO                 | NO          |
| Interpretability  SDK                                                      | GA                   | YES                | YES         |
| <h4>Training  </h4>                                                        |                      | <h4>US-Virginia  </h4>      | <h4>US-Arizona </h4> |
| Experimentation log streaming                                              | GA                   | YES                | YES         |
| Reinforcement Learning                                                     | Public Preview       | NO                 | NO          |
| Experimentation UI                                                         | GA                   | YES                | YES         |
| .NET integration ML.NET 1.0                                                | GA                   | YES                | YES         |
| <h4>Inference </h4>                                                        |                      | <h4>US-Virginia </h4>       | <h4>US-Arizona </h4> |
| Batch inferencing                                                          | GA                   | YES                | YES         |
| Data Box Edge with FPGA                                                    | Public Preview       | NO                 | NO          |
| <h4>Other </h4>                                                            |                      |<h4> US-Virginia</h4>        | <h4>US-Arizona</h4>  |
| Open Datasets                                                              | Public Preview       | YES                | YES         |
| Custom Cognitive Search                                                    | Public Preview       | YES                | YES         |
| Many Models                                                                | Public Preview       | NO                 | NO          |

<
<
<


|USGOV SCENARIOS:||||
|----------------------------------------------------------------------------|----------------------|--------------------|-------------|
|<h4>General Security Setup</h4>                                                     | <h4>US-Virginia</h4> | <h4>US-Arizona</h4>| <h4>GOV Limitations </h4> |
| Private network communication between services                                     | NO | NO | No Private Link right now for USGOV | 
| "Disable/control internet access (inbound and outbound) and specific VNet          | PARTIAL| PARTIAL	| ACR behind vnet are not avaible in UGOV - double checking on ACI | 
| placement for all associated resources/services"                                   | YES | YES |  |
| Encryption at-rest and in-transit.                                                 | YES | YES |  |
| Root and SSH access to compute resources.                                          | YES | YES |  |
| "Maintain the security of deployed systems (instances, endpoints, etc.), including endpoint protection, patching, and logging." |  PARTIAL|	PARTIAL	|ACI behind vnet and private endpoint currently not available |                                  
| Control (disable/limit/restrict) the use of ACI/AKS integration                    | PARTIAL|	PARTIAL	|ACI behind vnet and private endpoint currently not available|
| Role Based Access Control (RBAC) - Custom Role Creations                           | YES | YES |  |
| "Control access to ACR images used by ML Service (Azure provided/maintained versus custom)."  |PARTIAL|	PARTIAL	| ACR behind private endpoint and vnet not supported in USGOV |
| <h4>General Machine Learning Service Usage </h4>                                   | <h4>US-Virginia</h4> | <h4>US-Arizona</h4>| <h4>GOV Limitations </h4> |
| "Ability to have a development environment to build a model, train that model, host it as an endpoint, and consume it via a webapp. "     | YES | YES |  |
| Ability to pull data from ADLS (Data Lake Storage)                                 |YES | YES |  |
| Ability to pull data from Azure Blob Storage                                       |YES | YES |  |



<h2>Additional USGOV Limitations:</h2>
<ol>
<li>	*For Compute instances, feature “refresh token lasting more than 24 hours” is not available in USGOV. </li>
<li>	*Model Profiling does not support 4 CPU in USGov-Arizona.   </li>
<li>	*Sample notebook may not work, if it needs access to public data in USGOV.</li>
<li>	*GOV IPS: For Sovereign Clouds, The CLI command for [Vnet/Forced tunneling](http://https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-virtual-network "Vnet/Forced tunneling") does not return IP ranges: please use the [list](https://www.microsoft.com/en-us/download/details.aspx?id=57063) which contains the IPs for USGOV cloud.</li>
<li> *For scheduled pipelines, we also provide a blob based trigger mechanism. This mechanism is not supported for CMK workspaces. . For enabling blob based trigger for CMK workspaces, user has to do additional setup which is documented here: https://docs.microsoft.com/en-us/azure/machine-learning/how-to-trigger-published-pipeline</li>
 <li> *FireWalls: When using USGOV - make sure to add additional hosts in their firewall setting: For Arizona use:  "usgovarizona.api.ml.azure.us", for Virginia use: "usgovvirginia.api.ml.azure.us". Also double check - "graph.windows.net" is added as well. </li>
</ol>

<h2>China Parity</h2>	

| FEATURES                                                                   | Commercial Status | China Availability|-------------|
|----------------------------------------------------------------------------|------------------|--------------------|-------------|
| <h4>Automated machine learning</h4>                                        |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Create and run experiments in notebooks                                    | GA               | YES       | N/A        |
| Create and run experiments in studio web experience                        | Public Preview   | YES       | N/A        |
| Industry-leading forecasting capabilities                                  | GA               | YES       | N/A        |
| Support for deep learning and other advanced learners                      | GA               | YES       | N/A        |
| Large data support (up to 100 GB)                                          | Public Preview   | YES       | N/A        |
| Azure Data bricks Integration                                              | GA               | NO        | N/A        |
| SQL, CosmosDB and HDInsight integrations                                   | GA               | YES       | N/A        |
| <h4>Machine Learning pipelines</h4>                                        |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Create, run and publish pipelines using the Azure ML SDK                   | GA               | YES       | N/A        |
| Create pipeline endpoints using the Azure ML SDK                           | GA               | YES       | N/A        |
| Create, edit and delete scheduled runs of pipelines using the Azure ML SDK | GA               | YES       | N/A        |
| View pipeline run details in studio                                        | GA               | YES       | N/A        |
| Create, run, visualize and publish pipelines in Azure ML designer          | Public Preview   | YES       | N/A        |
| Azure Data bricks Integration with ML Pipeline                             | GA               | NO        | N/A        |
| Create pipeline endpoints in Azure ML designer                             | Public Preview   | YES       | N/A        |
| <h4>Integrated notebooks</h4>                                              |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Workspace notebook and file sharing                                        | GA               | YES       | N/A        |
| R and Python support                                                       | GA               | YES       | N/A        |
| Virtual Network support                                                    | Public Preview   | NO        | N/A        |
| <h4>Compute instance</h4>                                                  |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Managed compute Instances for integrated Notebooks                         | GA               | NO        | N/A        |
| Jupyter, JupyterLab Integration                                            | GA               | YES       | N/A        |
| Virtual Network (VNet) support                                             | Public Preview   | YES       | N/A        |
| <h4>SDK support</h4>                                                       |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| R SDK support                                                              | Public Preview   | YES       | N/A        |
| Python SDK support                                                         | GA               | YES       | N/A        |
| <h4>Security</h4>                                                          |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Virtual Network (VNet) support for training                                | GA               | YES       | N/A        |
| Virtual Network (VNet) support for inference                               | GA               | YES       | N/A        |
| Scoring endpoint authentication                                            | Public Preview   | YES       | N/A        |
| Workplace Private link                                                     | Public Preview   | NO        | N/A        |
| ACI behind Vnet                                                            | Public Preview   | NO        | N/A        |
| ACR behind Vnet                                                            | Public Preview   | NO        | N/A        |
| Private IP of AKS cluster                                                  | Public Preview   | NO        | N/A        |
| <h4>Compute</h4>                                                           |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| quota management across workspaces                                         | GA               | YES       | N/A        |
| <h4>Data for machine learning</h4>                                         |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Create, view or edit datasets and datastores from the SDK                  | GA               | YES       | N/A        |
| Create, view or edit datasets and datastores from the UI                   | GA               | YES       | N/A        |
| View, edit or delete dataset drift monitors from the SDK                   | Public Preview   | YES       | N/A        |
| View, edit or delete dataset drift monitors from the UI                    | Public Preview   | YES       | N/A        |
| <h4>ML Lifecycle</h4>                                                      |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Model profiling                                                            | GA               | PARTIAL   | N/A        |
| The Azure DevOps extension for Machine Learning & the Azure ML CLI         | GA               | YES       | N/A        |
| FPGA based Hardware Accelerated Models                                     | GA               | NO        | N/A        |
| Visual Studio Code integration                                             | Public Preview   | NO        | N/A        |
| Event Grid integration                                                     | Public Preview   | YES       | N/A        |
| Integrate Azure Stream Analytics with Azure Machine Learning               | Public Preview   | NO        | N/A        |
| <h4>Labelling</h4>                                                         |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Labelling Project Management Portal                                        | GA               | YES       | N/A        |
| Labeller Portal                                                            | GA               | YES       | N/A        |
| Labelling using private workforce                                          | GA               | YES       | N/A        |
| ML assisted labeling (Image classification and Object detection)           | Public Preview   | YES       | N/A        |
| <h4>Responsible ML</h4>                                                    |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Explainability in UI                                                       | Public Preview   | NO        | N/A        |
| Differential privacy WhiteNoise toolkit                                    | OSS              | NO        | N/A        |
| custom tags in Azure Machine Learning to implement datasheets              | GA               | NO        | N/A        |
| Fairness AzureML Integration                                               | Public Preview   | NO        | N/A        |
| Interpretability  SDK                                                      | GA               | YES       | N/A        |
| <h4>Training</h4>                                                          |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Experimentation log streaming                                              | GA               | YES       | N/A        |
| Reinforcement Learning                                                     | Public Preview   | NO        | N/A        |
| Experimentation UI                                                         | GA               | YES       | N/A        |
| .NET integration ML.NET 1.0                                                | GA               | YES       | N/A        |
| <h4>Inference</h4>                                                         |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Batch inferencing                                                          | GA               | YES       | N/A        |
| Data Box Edge with FPGA                                                    | Public Preview   | NO        | N/A        |
| <h4>Other</h4>                                                             |                  | <h4>CH-East 2</h4> | <h4>CH-North 3</h4> |
| Open Datasets                                                              | Public Preview   | YES       | N/A        |
| Custom Cognitive Search                                                    | Public Preview   | YES       | N/A        |
| Many Models                                                                | Public Preview   | NO        | N/A        |



<h2> *Additional China Limitations:</h2>
<ol>
<li>	*Azure China has limited VM SKU, especially for GPU SKU, only has NCv3 family (V100) </li>
<li>	*REST API Endpoint is different from public Azure:   </li>
<li>	*Sample notebook may not work, if it needs access to public data in USGOV.</li>
<li>	*For Sovereign Clouds, The CLI command for  [Vnet/Forced tunneling](http://https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-virtual-network "Vnet/Forced tunneling") does not return IP ranges: please use this [list](https://www.microsoft.com/en-in/download/details.aspx?id=57062) contains the IP Ranges for China Sovereign clouds.</li>
<li> *Azure Machine Learning compute instances preview is not supported in a workspace where Private Link is enabled for now, but CI will be supported in the next deployment for the service expansion to all AML regions.</li>
  
</ol>



|                  | Commercial                                 | China-Government                           |
|------------------|--------------------------------------------|--------------------------------------------|
| Management plane | https://management.azure.com/              | https://management.chinacloudapi.cn/       |
| Data plane       | https://{location}.experiments.azureml.net | https://{location}.experiments.ml.azure.cn |
| AAD              | https://login.microsoftonline.com          | https://login.chinacloudapi.cn             |
