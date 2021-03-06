---
title: Publish to Azure App Service
ms.custom: ""
ms.date: 06/22/2018
ms.technology: vs-ide-deployment
ms.topic: "quickstart"
helpviewer_keywords:
  - "deployment, website"
ms.assetid: fc82b1f1-d342-4b82-9a44-590479f0a895
author: mikejo5000
ms.author: mikejo
manager: douge
ms.workload:
  - "azure"
---
# Publish a Web app to Azure App Service using Visual Studio

You can use the **Publish** tool to publish ASP.NET, ASP.NET Core, Node.js, and .NET Core apps to Azure App Service or Azure App Service Linux (using containers). For Python apps, follow the steps on [Python - Publish to Azure App Service](../python/publishing-python-web-applications-to-azure-from-visual-studio.md).

[!INCLUDE [quickstart-prereqs-azure](includes/quickstart-prereqs-azure.md)]

## Publish to Azure App Service

1. In Solution Explorer, right-click the project and choose **Publish** (or use the **Build** > **Publish** menu item).

    ![The Publish command on the project context menu in Solution Explorer](../deployment/media/quickstart-publish.png "Choose Publish")

1. If you have previously configured any publishing profiles, the **Publish** pane appears, in which case select **Create new profile**.

1. In the **Pick a publish target** dialog box, choose **App Service**.

    ![Choose Azure App Service](../deployment/media/quickstart-publish-azure.png "Choose Azure App Service")

1. Select **Publish**. The **Create App Service** dialog box appears. Sign in with you Azure account, if necessary, then the default app service settings populate the fields.

    ![Create App Service](../deployment/media/quickstart-publish-settings-app-service.png "Create Azure App Service")

1. Select **Create**. Visual Studio deploys the app to your Azure App Service, and the web app loads in your browser. The project properties **Publish** pane shows the site URL and other details.

    ![Publish property pane showing a profile summary](../deployment/media/quickstart-publish-app-service-summary.png)

## Next steps

In this quickstart, you learned how to use Visual Studio to create a publishing profile for deployment to Azure. You can also configure a publishing profile by importing publish settings from Azure App Service.

> [!div class="nextstepaction"]
> [Import publish settings and deploy to Azure](tutorial-import-publish-settings-azure.md)
