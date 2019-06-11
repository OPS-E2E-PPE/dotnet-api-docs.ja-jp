---
ms.openlocfilehash: db5a44ce15b3f9f3081f4ebfb6eea6b9b3ae66d5
ms.sourcegitcommit: f1d16425528e237257ca3b58eb49217a514849ea
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/24/2019
ms.locfileid: "63877017"
---
<span data-ttu-id="c8613-101">変換では、入力文字が既に全角であっても、正規形 C が使われる場合があります。</span><span class="sxs-lookup"><span data-stu-id="c8613-101">The conversion may use Normalization Form C even if an input character is already full-width.</span></span> <span data-ttu-id="c8613-102">たとえば、文字列 "は゛" (既に全角です) は "ば" に正規化されます。</span><span class="sxs-lookup"><span data-stu-id="c8613-102">For example, the string "は゛" (which is already full-width) is normalized to "ば".</span></span> <span data-ttu-id="c8613-103">[Unicode の正規形](https://unicode.org/reports/tr15)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c8613-103">See [Unicode normalization forms](https://unicode.org/reports/tr15).</span></span>
