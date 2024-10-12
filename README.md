# AI-Governance

# AI-Governance

This repository contains Azure Resource Manager (ARM) templates for deploying various Azure services with private endpoints. These templates provide locked down methods of deploying Azure OpenAI installations, ensuring secure and restricted access to the services. The templates are organized into different directories based on the services they configure.

## AI Templates

### [OpenAI-PrivateEndpoints](OpenAI-PrivateEndpoints/AzureOpenAI_PrivateEndpoint.json)
This template deploys an Azure OpenAI service with a private endpoint. It includes configurations for network access restrictions and system-assigned identity.

### [OpenAI-AISearch-Storage-PrivateEndpoints](OpenAI-AISearch-Storage-PrivateEndpoints/OpenAI-AISearch-Storage-PrivateEndpoints.json)
This template deploys Azure AI Search and Storage services with private endpoints. It includes parameters for specifying the location, subnet ID, and service names.

### [OpenAI-AISearch-Storage-WebApp-PrivateEndpoints](OpenAI-AISearch-Storage-WebApp-PrivateEndpoints/OpenAI-AISearch-Storage-WebApp-PrivateEndpoints.json)
This template deploys Azure AI Search, Storage, and Web App services with private endpoints. It includes configurations for the App Service Plan and private endpoint connections.

### [OpenAI-AISearch-Storage-WebApp-AzureFrontDoor-PrivateEndpoint](OpenAI-AISearch-Storage-WebApp-AzureFrontDoor-PrivateEndpoint/OpenAI-AISearch-Storage-WebApp-AzureFrontDoor-PrivateEndpoint.json)
This template deploys Azure AI Search, Storage, Web App services, and Azure Front Door with private endpoints. It includes configurations for load balancing, endpoint connections, and service names.

### [OpenAI-AiSearch-Storage-WebApp-AFD-Monitoring](OpenAI-AiSearch-Storage-WebApp-AFD-Monitoring/OpenAI-AiSearch-Storage-WebApp-AFD-Monitoring.json)
This template deploys Azure AI Search, Storage, Web App services, and Azure Front Door with private endpoints, along with a Log Analytics workspace for monitoring. It includes configurations for diagnostic settings to ensure all services send logs and metrics to the Log Analytics workspace.

## Usage

Each template is designed to be deployed independently. Ensure you have the necessary permissions and prerequisites before deploying the templates. Refer to the metadata descriptions within each template for detailed information on the parameters and resources.