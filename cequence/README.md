# Cequence

## Overview

This integration provides Cequence Security customers with a preconfigured dashboard to view all of their API Runtime Inventory and Threat Detection log data within Datadog. This enables in-depth insights into your API Security posture. The log data export configuration must take place within your [Cequence Security Unified Platform][3].

## Setup

No configuration is needed to install the Cequence Datadog dashboard.

1. Log in to Datadog.
2. Navigate to [Integrations][7].
3. Search for Cequence.
4. Highlight the integration and Click **+ Install**.


### Cequence Configuration

1. Generate a new Integration API Key in [Datadog][4].
2. Use the [Datadog Integration Overview][3] article in the Cequence documentation to configure your Cequence Platform to export logs to Datadog.
 - Configure your Data Export to use the following Datadog API ingest URL. This is necessary for the functionality of this integration.  
   `https://http-intake.logs.datadoghq.com/api/v2/logs?ddsource=cequence`


## Data Collected
All Datadog access and export data is configured on the Cequence UAP Platform. The Cequence Platform exports these logs to Datadog.

### API Sentinel Detection Events

API Sentinel can be configured to export all API Runtime events from the Cequence Platform to Datadog.

### API Spartan Detection Events

API Spartan can be configured to export all Detection events from the Cequence Platform to Datadog.

### API Spartan Mitigation Events

API Spartan can be configured to export all Mitigation events from the Cequence Platform to Datadog.

## Troubleshooting

Need help? Contact [Cequence support][8].

[1]: https://docs.datadoghq.com/help/
[2]: https://www.cequence.ai/
[3]: https://helpdesk.cequence.ai/hc/en-us/articles/8614818269079-Cequence-UAP-Logging-to-Datadog-Log-Management-Overview
[4]: https://app.datadoghq.com/organization-settings/api-keys
[5]: mailto:support@cequence.ai
[6]: https://helpdesk.cequence.ai/hc/en-us/articles/8614818269079-Cequence-UAP-Logging-to-Datadog-Log-Management-Overview6
[7]: https://app.datadoghq.com/integrations
[8]: https://helpdesk.cequence.ai/hc/en-us
