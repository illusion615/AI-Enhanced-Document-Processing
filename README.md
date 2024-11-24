# AI-Enhanced-Document-Processing
Power Platform Solution - AI Enhanced Document Processing
## Solution features
- Monitoring multiple channels to capture incoming document, including email body, email attachment, SharePoint folder
- Recognize business data(order, invoice, etc.) from unpredictable format content without massive sample tagging and training
## Prequists
- PCF support enabled in the environment
- Premium license is required(Power Apps)
- Available AI Builder credit is required
- Creator Kit(The latest version can be download here: https://learn.microsoft.com/en-us/power-platform/guidance/creator-kit/overview)
- Markdown Viewer(The latest version can be download here: https://github.com/megel/PCF-MarkDownViewer)

## Setup
- Download the required component from the release
- Import solution in below sequence:
    1. PowerPlatformAIBase.zip
    2. OrderEntryAssistant.zip

## Configuration & Test
- Create your default processing setting
- Send email with desired information in body or in attachment
- Wait for the result