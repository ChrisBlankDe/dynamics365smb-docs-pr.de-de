---
title: "Inventurerfassung – Inventurzählung"
description: "Nach dem Erstellen eines Inventurauftrags und nach der Eingabe der Inventurauftragszeilen kann die eigentliche Inventur durchgeführt werden. In diesem Zusammenhang können die Inventurerfassungsbelege verwendet werden."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b34f276a764f0e828fbc1f015429df9852242a4c
ms.openlocfilehash: 79d3c6dae80afbac4ac77eadbce8b3e376c37c8a
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="physical-inventory-recording---counting-physical-inventory"></a><span data-ttu-id="3d74e-104">Inventurerfassung – Inventurzählung</span><span class="sxs-lookup"><span data-stu-id="3d74e-104">Physical Inventory Recording - Counting Physical Inventory</span></span>
<span data-ttu-id="3d74e-105">Nach dem Erstellen eines Inventurauftrags und nach der Eingabe der Inventurauftragszeilen kann die eigentliche Inventur durchgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="3d74e-105">After you have created a physical inventory order and after you have entered the physical inventory order lines, you can take the physical inventory.</span></span> <span data-ttu-id="3d74e-106">In diesem Zusammenhang können die Inventurerfassungsbelege verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d74e-106">Therefore you can use the physical inventory recording documents.</span></span>  

<span data-ttu-id="3d74e-107">Eine Inventurerfassung bezieht sich immer nur auf einen Inventurauftrag.</span><span class="sxs-lookup"><span data-stu-id="3d74e-107">A physical inventory recording is related to only one physical inventory order.</span></span> <span data-ttu-id="3d74e-108">Ein Inventurauftrag kann hingegen mit mehr als einer Inventurerfassung verknüpft sein.</span><span class="sxs-lookup"><span data-stu-id="3d74e-108">A physical inventory order may have relations to more than one physical inventory recordings.</span></span>  

<span data-ttu-id="3d74e-109">Jede Inventurerfassung setzt sich aus einem Inventurerfassungskopf und einer Reihe von Inventurerfassungszeilen zusammen.</span><span class="sxs-lookup"><span data-stu-id="3d74e-109">A physical inventory recoding consists of a physical inventory recording header and a number of physical inventory recording lines.</span></span> <span data-ttu-id="3d74e-110">Der Inventurerfassungskopf enthält die Informationen, die für alle Inventurerfassungszeilen gültig sind.</span><span class="sxs-lookup"><span data-stu-id="3d74e-110">The physical inventory recording header contains the information, that are common for all physical inventory recording lines.</span></span>  

<span data-ttu-id="3d74e-111">Die Zeilen enthalten die Artikel, die Lagerorte, die Lagerplätze und die erfassten Mengen.</span><span class="sxs-lookup"><span data-stu-id="3d74e-111">This lines contain the items, locations, bins and the recorded quantities.</span></span>  

<span data-ttu-id="3d74e-112">Diese können manuell oder von der Anwendung automatisch erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="3d74e-112">You can create lines manually or you can have the program to create new physical inventory recordings automatically.</span></span> <span data-ttu-id="3d74e-113">Es können Inventurerfassungslisten gedruckt werden.</span><span class="sxs-lookup"><span data-stu-id="3d74e-113">You can print physical inventory recording lists.</span></span>  

<span data-ttu-id="3d74e-114">Durch Festlegen des Status auf "Beendet" teilen Sie der Anwendung mit, dass die aktuelle Inventurerfassung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3d74e-114">By setting the Status to finished, you tell the program, that the current physical inventory recording has been finished.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="3d74e-115">Beim Abschluss der aktuellen Inventurerfassung weist die Anwendung jeder Inventurerfassungszeile eine Zeile des zugehörigen Inventurauftrags zu.</span><span class="sxs-lookup"><span data-stu-id="3d74e-115">When you finish the current physical inventory recording, the program assigns every physical inventory recording line to one line of the related physical inventory order.</span></span> <span data-ttu-id="3d74e-116">Die Anwendung weist jeweils Inventurauftragszeilen mit den gleichen Werten in den 4 Feldern  Artikelnr.,  Variantencode,  Lagerortcode und  Lagerplatzcode wie in der Inventurerfassungszeile zu.</span><span class="sxs-lookup"><span data-stu-id="3d74e-116">The program assigns this physical inventory order lines with the same values in the 4 fields Item No., Variant Code, Location Code and Bin Code like in the physical inventory recording line.</span></span>  
>   
>  <span data-ttu-id="3d74e-117">Wenn keine entsprechende Inventurauftragszeile vorhanden ist, fügt die Anwendung beim Abschluss der Inventurerfassung automatisch eine neue Zeile hinzu.</span><span class="sxs-lookup"><span data-stu-id="3d74e-117">If there is no such physical inventory order line the program will automatically insert a new line when finishing the physical inventory recording.</span></span> <span data-ttu-id="3d74e-118">Die Anwendung kennzeichnet diese Zeile durch Aktivierung des Kontrollkästchens Ohne Auftrag erfasst in der jeweiligen Inventurauftragszeile.</span><span class="sxs-lookup"><span data-stu-id="3d74e-118">The program will note this by placing a check mark in the field Recorded without Order on the physical inventory order line.</span></span>  
>   
>  <span data-ttu-id="3d74e-119">Ist mehr als eine entsprechende Inventurauftragszeile vorhanden, wird eine Fehlermeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="3d74e-119">If there are more than one such physical inventory order lines, an error message appears.</span></span> <span data-ttu-id="3d74e-120">In diesem Fall können Sie die Anwendung anweisen, die doppelten Zeilen anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="3d74e-120">You can have the program to show you the duplicate lines.</span></span>  

## <a name="see-also"></a><span data-ttu-id="3d74e-121">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="3d74e-121">See Also</span></span>  
 <span data-ttu-id="3d74e-122">[So erstellen Sie eine physische Inventurerfassung](how-to-create-a-physical-inventory-recording.md) </span><span class="sxs-lookup"><span data-stu-id="3d74e-122">[Create a Physical Inventory Recording](how-to-create-a-physical-inventory-recording.md) </span></span>  
 <span data-ttu-id="3d74e-123">[So schließen Sie eine Inventurerfassung ab](how-to-finish-a-physical-inventory-recording.md) </span><span class="sxs-lookup"><span data-stu-id="3d74e-123">[Finish a Physical Inventory Recording](how-to-finish-a-physical-inventory-recording.md) </span></span>  
 <span data-ttu-id="3d74e-124">[So zeigen Sie doppelte Inventurauftragszeilen an](how-to-view-duplicate-physical-inventory-order-lines.md) </span><span class="sxs-lookup"><span data-stu-id="3d74e-124">[View Duplicate Physical Inventory Order Lines](how-to-view-duplicate-physical-inventory-order-lines.md) </span></span>  
 [<span data-ttu-id="3d74e-125">Inventurauftragszeilen mit Artikelverfolgungszeilen</span><span class="sxs-lookup"><span data-stu-id="3d74e-125">Physical Inventory Order Lines With Item Tracking Lines</span></span>](physical-inventory-order-lines-with-item-tracking-lines.md)
