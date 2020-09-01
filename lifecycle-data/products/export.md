---
title: Експорт даних життєвого циклу
description: Експорт відомостей про життєвий цикл продуктів
ms.date: 08/21/2020
layout: ContentPage
ms.openlocfilehash: 56cab0b1a87b24a963dd5c252a0199dfabb08767
ms.sourcegitcommit: 37ac01a1d5492bb2bf54cbd018ea34074db8c998
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/01/2020
ms.locfileid: "940978"
---
# <a name="lifecycle-data-export"></a><span data-ttu-id="00b68-103">Експорт даних життєвого циклу</span><span class="sxs-lookup"><span data-stu-id="00b68-103">Lifecycle data export</span></span>

> [!IMPORTANT]
> <span data-ttu-id="00b68-104">Ця сторінка знаходиться в стадії розробки.</span><span class="sxs-lookup"><span data-stu-id="00b68-104">This page is under development.</span></span>

## <a name="export-all-products"></a><span data-ttu-id="00b68-105">Експорт усіх продуктів</span><span class="sxs-lookup"><span data-stu-id="00b68-105">Export all products</span></span>
<span data-ttu-id="00b68-106">Експортувати дані життєвого циклу для всіх продуктів, клацнувши нижче:</span><span class="sxs-lookup"><span data-stu-id="00b68-106">Export lifecycle data for all products by clicking below:</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="00b68-107">Експорт усіх продуктів</span><span class="sxs-lookup"><span data-stu-id="00b68-107">Export All Products</span></span>](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a><span data-ttu-id="00b68-108">Експорт продуктів за допомогою родини та груп</span><span class="sxs-lookup"><span data-stu-id="00b68-108">Export products by Family and Group</span></span>
<span data-ttu-id="00b68-109">Виберіть родину, а потім – групу, яку потрібно експортувати.</span><span class="sxs-lookup"><span data-stu-id="00b68-109">Select a Family and then a Group to export.</span></span> <span data-ttu-id="00b68-110">Примітка: експорт почнеться, коли вибрано значення групування.</span><span class="sxs-lookup"><span data-stu-id="00b68-110">Note: Export will begin when Group value is selected.</span></span> 

> [!div class="op_multi_selector" title1="Сім'ї" title2="Група"]
> - [(.NET | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET')
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET'%20and%20parent/parent/name%20eq%20'.NET')
> - [(Azure | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure')
> - [(Azure | Ай](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'AI')
> - [(Azure | Azure](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Azure')
> - [(Azure | Баз даних](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Databases')
> - [(Azure | Інші](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Other')
> - [(Динаміка | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics')
> - [(Динаміка | Динаміки](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics')
> - [(Динаміка | Dynamics 365)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20365')
> - [(Динаміка | Dynamics AX)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20AX')
> - [(Динаміка | Динаміка C5)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20C5')
> - [(Динаміка | Dynamics CRM)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20CRM')
> - [(Динаміка | Динаміка ГП)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20GP')
> - [(Динаміка | Динаміка ПЕРЕХОДІВ)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20NAV')
> - [(Динаміка | Динаміка POS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20POS')
> - [(Динаміка | Динаміка RMS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20RMS')
> - [(Динаміка | Динаміка SL)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20SL')
> - [(Динаміка | Інші](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Other')
> - [(Вираз | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression')
> - [(Вираз | Вираз](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression'%20and%20parent/parent/name%20eq%20'Expression')
> - [(Microsoft 365 | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365')
> - [(Microsoft 365 | Корпоративна мобільність + безпека)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Enterprise%20Mobility%20%2B%20Security')
> - [(Microsoft 365 | Керування посвідченнями)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Identity%20Management')
> - [(Структура підключених служб Microsoft | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework')
> - [(Структура підключених служб Microsoft | Система підключених служб)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework'%20and%20parent/parent/name%20eq%20'Connected%20Services%20Framework')
> - [(Microsoft Care Framework для клієнтів | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework')
> - [(Microsoft Care Framework для клієнтів | Основи обслуговування клієнтів)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework'%20and%20parent/parent/name%20eq%20'Customer%20Care%20Framework')
> - [(Microsoft EDGE | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge')
> - [(Microsoft EDGE | EDGE](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge'%20and%20parent/parent/name%20eq%20'Edge')
> - [(Microsoft Internet Explorer | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer')
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer'%20and%20parent/parent/name%20eq%20'Internet%20Explorer')
> - [(Microsoft Office | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office')
> - [(Microsoft Office | Клієнта](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Client')
> - [(Microsoft Office | Безпеки](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Security')
> - [(Microsoft Office | Server](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Server')
> - [(Сервер Microsoft | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers')
> - [(Сервер Microsoft | Сервер BizTalk)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'BizTalk%20Server')
> - [(Сервер Microsoft | Сервер комерції)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Commerce%20Server')
> - [(Сервер Microsoft | Сервер керування вмістом)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Content%20Management%20Server')
> - [(Сервер Microsoft | Хост інтеграції Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Host%20Integration%20Server')
> - [(Сервер Microsoft | Інтелектуальний шлюз програми)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Intelligent%20Application%20Gateway')
> - [(Сервер Microsoft | Безпеки](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Security')
> - [(Microsoft System Center | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center')
> - [(Microsoft System Center | Системний центр)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center'%20and%20parent/parent/name%20eq%20'System%20Center')
> - [(Silverlight | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight')
> - [(Silverlight | Silverlight](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight'%20and%20parent/parent/name%20eq%20'Silverlight')
> - [(SQL Server | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server')
> - [(SQL Server | Power BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'Power%20BI')
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'SQL%20Server')
> - [(Visual Studio | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio')
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio'%20and%20parent/parent/name%20eq%20'Visual%20Studio')
> - [(Windows | Всі](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows')
> - [(Windows | Клієнта](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Client')
> - [(Windows | OT)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'IoT')
> - [(Windows | Мобільного](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Mobile')
> - [(Windows | Безпеки](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Security')
> - [(Windows | Server](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Server')

## <a name="export-products-by-end-of-support-date"></a><span data-ttu-id="00b68-171">Експорт продуктів за кінець дати підтримки</span><span class="sxs-lookup"><span data-stu-id="00b68-171">Export products by end of support date</span></span>
<span data-ttu-id="00b68-172">Виберіть рік, щоб переглянути продукти, які досягнуть кінця підтримки.</span><span class="sxs-lookup"><span data-stu-id="00b68-172">Select a year to see products reaching the end of support.</span></span> <span data-ttu-id="00b68-173">Примітка: експорт почнеться, коли вибрано значення рік.</span><span class="sxs-lookup"><span data-stu-id="00b68-173">Note: Export will begin when Year value is selected.</span></span>

> [!div class="op_single_selector"]
> - [2002](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2002))
> - [2003](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2003))
> - [2004](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2004))
> - [2005](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2005))
> - [2006](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2006))
> - [2007](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2007))
> - [2008](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2008))
> - [2009](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2009))
> - [2010](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2010))
> - [2011](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2011))
> - [2012](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2012))
> - [2013](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2013))
> - [2014](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2014))
> - [2015](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2015))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
