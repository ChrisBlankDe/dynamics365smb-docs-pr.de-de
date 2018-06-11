---
title: "Berichterstattung für Business Central in Power BI | Microsoft Docs einrichten"
description: "Sie können Ihre Daten in Financials als Datenquelle in Power BI bereitstellen und leistungsstarke Berichte über den Zustand des Geschäftes erstellen."
author: edupont04
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: business intelligence, KPI, Odata, Power App, SOAP, analysis
ms.date: 04/03/2018
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 9cad9c7e2b54506e60af7d38d42f413599a44d01
ms.openlocfilehash: 4e25432fe5f21f29b9533c8c909e58bf24f0eb7a
ms.contentlocale: de-de
ms.lasthandoff: 04/03/2018

---
# <a name="using-included365finlongmdincludesd365finlongmdmd-as-power-bi-data-source-for-building-reports"></a><span data-ttu-id="916b9-103">[!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Power BI als Datenquelle für das Erstellen von Berichten nutzen</span><span class="sxs-lookup"><span data-stu-id="916b9-103">Using [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] as Power BI Data Source for Building Reports</span></span>
<span data-ttu-id="916b9-104">Sie können Ihre [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Daten zur Verfügung stellen als Datenquelle in Power BI und leistungsstarke Berichte über den Zustand des Geschäftes erstellen.</span><span class="sxs-lookup"><span data-stu-id="916b9-104">You can make your [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] data available as a data source in Power BI and build powerful reports of the state of your business.</span></span>  

<span data-ttu-id="916b9-105">Sie müssen ein gültiges Konto mit [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] mit Power BI haben.</span><span class="sxs-lookup"><span data-stu-id="916b9-105">You must have a valid account with [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] and with Power BI.</span></span> <span data-ttu-id="916b9-106">Zudem müssen Sie [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) herunterladen.</span><span class="sxs-lookup"><span data-stu-id="916b9-106">Also, you must download [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).</span></span>  

## <a name="to-add-included365finlongmdincludesd365finlongmdmd-as-a-data-source-in-power-bi-desktop"></a><span data-ttu-id="916b9-107">Um [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] als Datenquelle in Power BI Desktop hinzufügen</span><span class="sxs-lookup"><span data-stu-id="916b9-107">To add [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] as a data source in Power BI Desktop</span></span>
1. <span data-ttu-id="916b9-108">In Power BI Desktop im linken Navigationsbereich, wählen Sie **Daten abrufen** aus.</span><span class="sxs-lookup"><span data-stu-id="916b9-108">In Power BI Desktop, in the left navigation pane, choose **Get Data**.</span></span>
2. <span data-ttu-id="916b9-109">Im Fenster **Daten abrufen** wählen Sie **Onlineservices** aus, wählen Sie **Microsoft Dynamics 365 Business Central** und dann die Schaltfläche **Verbinden** aus.</span><span class="sxs-lookup"><span data-stu-id="916b9-109">In the **Get Data** window, choose **Online Services**, choose **Microsoft Dynamics 365 Business Central**, and then choose the **Connect** button.</span></span>
3. <span data-ttu-id="916b9-110">Power BI zeigt einen Assistenten an, der Sie durch den [Verbindungsvorgang](across-how-to-connect-powerbi-dynamics-365-content-packs-help.md) führt.</span><span class="sxs-lookup"><span data-stu-id="916b9-110">Power BI displays a wizard that will guide you through the [connection process](across-how-to-connect-powerbi-dynamics-365-content-packs-help.md).</span></span> <span data-ttu-id="916b9-111">Sie werden aufgefordert, sich beim Service anzumelden.</span><span class="sxs-lookup"><span data-stu-id="916b9-111">You will be prompted to sign into the service.</span></span> <span data-ttu-id="916b9-112">Wählen Sie **Anmelden** und wählen Sie das Konto aus, bei dem Sie sich anmelden möchten.</span><span class="sxs-lookup"><span data-stu-id="916b9-112">Select **Sign in** and choose the account you would like to sign in as.</span></span> <span data-ttu-id="916b9-113">Dieses sollte das gleiche Konto sein, bei dem Sie sich bei [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] anmelden.</span><span class="sxs-lookup"><span data-stu-id="916b9-113">This should be the same account you sign into [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] with.</span></span>
4. <span data-ttu-id="916b9-114">Klicken Sie auf die Schaltfläche **Verbinden** zum Fortfahren.</span><span class="sxs-lookup"><span data-stu-id="916b9-114">Choose the **Connect** button to continue.</span></span> <span data-ttu-id="916b9-115">Der Power BI Assistent zeigt eine Liste der Microsoft [!INCLUDE[d365fin](includes/d365fin_md.md)]-Unternehmen und -Datenquellen an.</span><span class="sxs-lookup"><span data-stu-id="916b9-115">The Power BI wizard shows a list of Microsoft [!INCLUDE[d365fin](includes/d365fin_md.md)] companies and data sources.</span></span> <span data-ttu-id="916b9-116">Diese Datenquelle ist für alle Webdienste, die Sie von jedem Unternehmen in Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] veröffentlicht haben.</span><span class="sxs-lookup"><span data-stu-id="916b9-116">These data source represent all the web services that you have published from each company in Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)].</span></span>
5. <span data-ttu-id="916b9-117">Sie können einen neuen Webdienst URL in [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] erstellen, indem Sie die **Erstellen Dataset** Aktion der Seite **Webdienste** nutzen, indem Sie die unterstütze Hilfe **Bericht einrichten** verwenden oder die Aktion **Bearbeiten in Excel** in einer beliebigen Liste wählen.</span><span class="sxs-lookup"><span data-stu-id="916b9-117">Alternatively, create a new web service URL in [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] by using the **Create Data Set** action in the **Web Services** page, using the **Set Up Reporting** Assisted Setup guide, or by choosing the **Edit in Excel** action in any lists.</span></span>
6. <span data-ttu-id="916b9-118">Geben Sie die Daten an, die Sie Ihrem Datenmodell hinzufügen möchten, und wählen Sie dann die Schaltfläche **Laden** aus.</span><span class="sxs-lookup"><span data-stu-id="916b9-118">Specify the data you want to add to your data model, and then choose the **Load** button.</span></span>
7. <span data-ttu-id="916b9-119">Wiederholen Sie die vorherigen Schritte, um zusätzliche Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] oder andere Daten Ihrem Power BI-Datenmodell hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="916b9-119">Repeat the previous steps to add additional Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)], or other data, to your Power BI data model.</span></span>

> [!NOTE]  
> <span data-ttu-id="916b9-120">Sobald Sie sich erfolgreich mit Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] verbunden haben, werden Sie nicht mehr aufgefordert, sich anzumelden.</span><span class="sxs-lookup"><span data-stu-id="916b9-120">Once you have successfully connected to Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)], you will not be prompted again to sign in.</span></span>

<span data-ttu-id="916b9-121">Sobald die Daten geladen sind, erscheinen Sie in der rechten Navigation auf der Seite.</span><span class="sxs-lookup"><span data-stu-id="916b9-121">Once the data is loaded it will appear in the right navigation on the page.</span></span> <span data-ttu-id="916b9-122">Zu diesem Zeitpunkt haben Sie Ihre Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)]-Daten erfolgreich verbunden und sind bereit, Ihren Power BI-Bericht zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="916b9-122">At this point, you have successfully connected to your Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] data and are ready to begin building your Power BI report.</span></span> 

<span data-ttu-id="916b9-123">Bevor Sie Ihren Bericht erstellen, empfiehlt es sich, die Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)]-Designdatei zu importieren.</span><span class="sxs-lookup"><span data-stu-id="916b9-123">Before building your report, we recommend that you import the Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] theme file.</span></span>  <span data-ttu-id="916b9-124">Die Designdatei erstellt eine Farbpalette, damit Sie Berichte im selben Farbstil erstellen können, wie bei den Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)]-Inhaltspacks, ohne benutzerdefinierte Farben für jede Grafik definieren zu müssen.</span><span class="sxs-lookup"><span data-stu-id="916b9-124">The theme file will create a color palette so that you can build reports with the same color styling as the Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] content packs without requiring you to define custom colors for each visual.</span></span>

<span data-ttu-id="916b9-125">Weitere Informationen finden Sie in der [Power BI Dokumentation](https://powerbi.microsoft.com/documentation/powerbi-landing-page/).</span><span class="sxs-lookup"><span data-stu-id="916b9-125">For more information, see the [Power BI documentation](https://powerbi.microsoft.com/documentation/powerbi-landing-page/).</span></span>

## <a name="see-also"></a><span data-ttu-id="916b9-126">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="916b9-126">See Also</span></span>
[<span data-ttu-id="916b9-127">Business Intelligence</span><span class="sxs-lookup"><span data-stu-id="916b9-127">Business Intelligence</span></span>](bi.md)  
[<span data-ttu-id="916b9-128">Erste Schritte</span><span class="sxs-lookup"><span data-stu-id="916b9-128">Getting Started</span></span>](product-get-started.md)  
[<span data-ttu-id="916b9-129">Geschäftsdaten aus anderen Finanzsystemen importieren</span><span class="sxs-lookup"><span data-stu-id="916b9-129">Importing Business Data from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="916b9-130">[Einrichten [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md) </span><span class="sxs-lookup"><span data-stu-id="916b9-130">[Setting Up [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md) </span></span>  
[<span data-ttu-id="916b9-131">Finanzen</span><span class="sxs-lookup"><span data-stu-id="916b9-131">Finance</span></span>](finance.md)  
<span data-ttu-id="916b9-132">[Power BI mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](across-how-to-connect-powerbi-dynamics-365-content-packs-help.md) verbinden</span><span class="sxs-lookup"><span data-stu-id="916b9-132">[Connecting Power BI to [!INCLUDE[d365fin](includes/d365fin_md.md)]](across-how-to-connect-powerbi-dynamics-365-content-packs-help.md)</span></span>  
