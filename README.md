# Mindee Microsoft RPA (Robotic Process Automation) Integration

- [Mindee Microsoft RPA (Robotic Process Automation) Integration](#mindee-microsoft-rpa-robotic-process-automation-integration)
  - [Integration Overview](#integration-overview)
    - [SharePoint Online](#sharepoint-online)
      - [Configuration](#configuration)
    - [Power Automate Flow](#power-automate-flow)
      - [Configuration](#configuration-1)
      - [Testing](#testing)

## Integration Overview

### SharePoint Online

#### Configuration

You first need to enable document and list templates on your site (required for modern sites only). To do so, use the following steps:

1. On Windows, open up a SharePoint Online Management PowerShell (install it at https://www.microsoft.com/en-us/download/details.aspx?id=35588)
2. Connect to your tenant using Connect-SPOService (using your https://tenant**-admin**.sharepoint.com as the Url)
3. Run the following: `Set-SPOSite "https://tenant.sharepoint.com/sites/yoursite -DenyAddAndCustomizePages 0`

### Power Automate Flow

#### Configuration

#### Testing
