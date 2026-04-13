# تسليم الخرسانة

### الخرسانة

<figure><img src="../../../.gitbook/assets/Gantt Chart Roadmap Whiteboard in Green Black Purple Sleek Digitalism Style (1).jpg" alt=""><figcaption></figcaption></figure>

<p align="right"><strong>موصفات مكونات المنتج</strong><br>في نظام AccFlex، يتم تحديد مواصفات مكونات المنتج مسبقًا لكل درجة خرسانة، بحيث تحتوي كل درجة على نسب دقيقة من الأسمنت، الرمل، والمكونات الأخرى. عند تقديم العميل لطلب، يقوم النظام تلقائيًا بحساب الكميات المطلوبة من كل صنف استنادًا إلى مواصفات الخلطة والكمية الإجمالية المطلوبة.</p>

<figure><img src="../../../.gitbook/assets/مواصفة مكونات المنتج.gif" alt=""><figcaption><p>موصفات مكونات المنتخ</p></figcaption></figure>

<p align="right"><strong>تسليم الخرسانة</strong><br>تبدأ خطوة تخطيط التسليم بعد إنشاء أمر البيع، مع الإشارة إلى أن تحديد مواصفات مكونات المنتج يُعد خطوة اختيارية. يتم تلقائيًا تعبئة شاشة تسليم الخرسانة بكافة المعلومات المسجلة في أمر البيع، ما يسهل إعداد عملية التوصيل.</p>

<figure><img src="../../../.gitbook/assets/تسليم الخرسانة (لم يبدأ) (1).gif" alt=""><figcaption><p>تسليم الخرسانة (لم يبدأ)</p></figcaption></figure>

<p align="right">في الختام، هناك أربع سيناريوهات لحالات الخلط الجاهز:<br>1.جاري التسليم<br>بالنسبة للخرسانة  تكون في مرحلة الإنتاج تحت التصنيع، يقوم النظام تلقائيًا بإنشاء حركة صرف للبضائع من المخزون.</p>

<figure><img src="../../../.gitbook/assets/تسليم الخرسانة (جاري التسليم).gif" alt=""><figcaption><p>تسليم الخرسانة (جاري التسليم)</p></figcaption></figure>

<p align="right">٢. تم التسليم<br>عندما يقبل العميل الاستلام الخرسانة، ينشئ النظام قيد يومية خاص بعملية الاستلام، وفي تلك المرحلة يمكن إنشاء الفاتورة يدويًا.</p>

<figure><img src="../../../.gitbook/assets/تسليم الخراسنة (تم التسليم) (1).gif" alt=""><figcaption><p>تسليم الخراسنة (تم التسليم)</p></figcaption></figure>

<p align="right">٣. إعادة التوجيه <br>عندما يحتاج الخرسانة إلى إعادة توجيه إلى عميل آخر، يقوم النظام تلقائيًا بإنشاء أمر بيع جديد أو تحديث أمر بيع قائم للعميل البديل.</p>

<figure><img src="../../../.gitbook/assets/تسليم الخراسنة (رفض و توجية لعميل اخر).gif" alt=""><figcaption><p>تسليم الخراسنة (رفض و توجية لعميل اخر)</p></figcaption></figure>

<p align="right">٤. الرفض<br>في الحالات التي يرفض فيها العميل التسليم بسبب مشاكل في الجودة أو توقيت التسليم أو لأسباب أخرى، يتم إنشاء قيد يومية يُسجل الكمية كمخزون تالف (خردة).</p>

<figure><img src="../../../.gitbook/assets/تسليم الخرسانة (رفض و اهلاك) (1).gif" alt=""><figcaption><p>تسليم الخرسانة (رفض و اهلاك)</p></figcaption></figure>

<p align="right">يحرص النظام في كل سيناريو على الحفاظ على قابلية التدقيق، مع مراعاة التأثير المالي في الفترة المحاسبية المناسبة. سواء كان ذلك من خلال تسجيل الإيرادات، أو احتساب الإنتاج تحت التصنيع، أو تعديل أوامر البيع، أو تسجيل الخسائر الناتجة عن الإهلاك أو الرفض، يتم توثيق الأثر المالي بدقة.</p>

<p align="right">يوفر التكامل العميق بين العمليات التشغيلية والمالية في نظام AccFlex ERP رؤية فورية وشاملة لحركة المواد وأثرها المالي، مما يساعد في تحسين اتخاذ القرار، وتعزيز الشفافية، وضمان الالتزام بالمعايير المحاسبية.</p>

{% hint style="info" %}
<p align="right"><br>تلميح: يمكن تقسيم خطة التسليم إلى عدة عمليات تسليم، وقد يحدث ذلك بسبب حدود سعة الشاحنة، أو قيود الجدولة، أو متطلبات العميل. كل عملية تسليم يتم إنشاؤها من الخطة سيكون لها شاحنتها الخاصة، وسائقها، وحالة تسليمها، مع كونها لا تزال مرتبطة بأمر البيع الأصلي.</p>
{% endhint %}

<p align="right">القيود اليومية:</p>

<p align="right">  تم التسليم</p>

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">الشرح</td><td valign="top">مدين</td><td valign="top">دائن</td></tr><tr><td valign="top">تكلفة البضاعة المباعة</td><td valign="top">××</td><td valign="top"> </td></tr><tr><td valign="top">منتج تحت التصنيع</td><td valign="top"> </td><td valign="top">××</td></tr></tbody></table>

<p align="right">جاري التسليم</p>

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">شرح</td><td valign="top">مدين</td><td valign="top">دائن</td></tr><tr><td valign="top">منتج تحت التصنيع</td><td valign="top">××</td><td valign="top"> </td></tr><tr><td valign="top">     مواد الخام</td><td valign="top"> </td><td valign="top">××</td></tr></tbody></table>

<p align="right">تم الرفض</p>

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">شرح</td><td valign="top">مدين</td><td valign="top">دائن</td></tr><tr><td valign="top">مصاريف إهلاك</td><td valign="top">××</td><td valign="top"> </td></tr><tr><td valign="top">منتج تحت التصنيع</td><td valign="top"> </td><td valign="top">××</td></tr></tbody></table>

<p align="right"></p>

<p align="right"><br><br></p>
