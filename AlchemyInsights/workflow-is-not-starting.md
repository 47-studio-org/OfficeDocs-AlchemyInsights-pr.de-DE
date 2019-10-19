---
title: Workflow wird nicht gestartet
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: 2d85dcf9111d48cb529c583c733823b404eb3188
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2019
ms.locfileid: "36738088"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="aef3f-102">Workflow wird nicht gestartet</span><span class="sxs-lookup"><span data-stu-id="aef3f-102">Workflow is not starting</span></span>

- <span data-ttu-id="aef3f-103">SharePoint 2010-und SharePoint 2013-Workflows werden nicht gestartet.</span><span class="sxs-lookup"><span data-stu-id="aef3f-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="aef3f-104">Wenn Ihr Workflow nicht gestartet wird, kann es zu einem temporären Dienst Problem kommen, bei dem Benutzer gelegentlich Verzögerungen mit dem Workflowfortschritt auftreten können.</span><span class="sxs-lookup"><span data-stu-id="aef3f-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="aef3f-105">Überprüfen Sie das [Dienststatus-Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) , um zu sehen, ob Ihre Organisation betroffen ist.</span><span class="sxs-lookup"><span data-stu-id="aef3f-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="aef3f-106">Wenn seit dem ersten Auftreten dieses Problems mehr als 24 Stunden vergangen sind, melden Sie sich ein Support Ticket an.</span><span class="sxs-lookup"><span data-stu-id="aef3f-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="aef3f-107">In vielen Fällen arbeiten wir bereits an einer Lösung.</span><span class="sxs-lookup"><span data-stu-id="aef3f-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="aef3f-108">Geben Sie uns mindestens 24 Stunden, um eine Lösung zu vervollständigen.</span><span class="sxs-lookup"><span data-stu-id="aef3f-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="aef3f-109">SharePoint 2010-Workflows werden beim Start verzögert.</span><span class="sxs-lookup"><span data-stu-id="aef3f-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="aef3f-110">Dies tritt auf, wenn der Workflow in großen Batches ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="aef3f-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="aef3f-111">(beispielsweise, wenn mehrere Elemente gleichzeitig hinzugefügt werden).</span><span class="sxs-lookup"><span data-stu-id="aef3f-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="aef3f-112">Workflows sind nicht für die Ausführung in Echtzeit vorgesehen, daher ist eine Verzögerung das Entwurfsverhalten.</span><span class="sxs-lookup"><span data-stu-id="aef3f-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="aef3f-113">Wenn es sich bei dem Workflow um eine komplexe eXtensible Object Markup Language (XMol) handelt, kann die Kompilierung langsam sein.</span><span class="sxs-lookup"><span data-stu-id="aef3f-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="aef3f-114">Lesen Sie [diesen](https://support.microsoft.com//kb/3043697) Artikel.</span><span class="sxs-lookup"><span data-stu-id="aef3f-114">Check [this](https://support.microsoft.com//kb/3043697) article.</span></span>

    - <span data-ttu-id="aef3f-115">Sie sollten den Workflow vereinfachen oder ihn mit dem Microsoft SharePoint 2013 Workflow Platt Form neu entwerfen.</span><span class="sxs-lookup"><span data-stu-id="aef3f-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="aef3f-116">Wenn Ihr Workflowverlauf groß geworden ist, können Sie die Elemente löschen oder eine neue Verlaufsliste erstellen.</span><span class="sxs-lookup"><span data-stu-id="aef3f-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="aef3f-117">Weitere Informationen: [Workflow Verlauf löschen](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="aef3f-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="aef3f-118">Verwandte Themen</span><span class="sxs-lookup"><span data-stu-id="aef3f-118">Related topics</span></span>
<span data-ttu-id="aef3f-119">Möchten Sie Microsoft Flow in SharePoint Online testen?</span><span class="sxs-lookup"><span data-stu-id="aef3f-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="aef3f-120">Fluss erstellen</span><span class="sxs-lookup"><span data-stu-id="aef3f-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="aef3f-121">SharePoint und Flow</span><span class="sxs-lookup"><span data-stu-id="aef3f-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


