> ترجمة عربية غير رسمية لملف [docs/做平台要办哪些证.md](../做平台要办哪些证.md). عند وجود أي اختلاف، يُعتد بالأصل الصيني.

# ما التراخيص التي تحتاجها المنصة: جدول مقارنة وجدول قرار لاختيار الخوادم

يقابل هذا القسم 26 من README. تحوي هذه الصفحة جدولين فقط وبضع ملاحظات عن نقاط يسهل الخطأ فيها؛ ونص المداخل والمصادر في README. وكيفية تسجيل شركة وتقديم الضرائب في القسم 12؛ والخطوط الحمراء للتقنيين الموظفين في القسم 11.

## 1. أولا، حدد أي نوع عمل تدير

يقع الموقع الواحد غالبا في عدة فئات من هذه معا. وتتراكم التراخيص؛ وليست تخييرا.

| ما تفعله | فئة العمل المقابلة | ما تحتاجه | الأساس القانوني الأول |
|---|---|---|---|
| مواقع معلومات مجانية ومدونات شخصية ومواقع شركات رسمية | 非经营性互联网信息服务 — non-commercial internet information services | ICP 备案 — ICP filing with MIIT | 互联网信息服务管理办法 — Internet Information Services Administrative Measures, Article 4 |
| عضويات مدفوعة أو خدمات ذات قيمة مضافة أو محتوى مدفوع يدفع له المستخدمون | 经营性互联网信息服务 — commercial internet information services | 增值电信业务经营许可 — value-added telecom business license (information services business) | Same measures, Articles 3, 4, and 7 |
| التوفيق بين البائعين والمشترين ومعالجة المعاملات والطلبات | 在线数据处理与交易处理业务 — online data processing and transaction processing business | 增值电信业务经营许可 — value-added telecom business license (B21) | 电信业务分类目录 — Telecommunications Business Classification Catalogue (2015 edition), B21 |
| بث مباشر بمضيفين أمام الكاميرا وبث الألعاب | 网络表演 — online performance | 网络文化经营许可证 — Network Culture Business License, with online performance included in the business scope | 网络表演经营活动管理办法 — Measures for the Administration of Online Performance Business Activities, Article 4 |
| إنتاج برامج مرئية أو تجميعها، أو تقديم خدمة تتيح للآخرين رفع برامج سمعية بصرية | 互联网视听节目服务 — internet audio-visual program services | 信息网络传播视听节目许可证 — License for the Dissemination of Audio-Visual Programs through Information Networks | 互联网视听节目服务管理规定 — Provisions on the Administration of Internet Audio-Visual Program Services, Articles 7 and 8 |
| بيع السلع أثناء البث المباشر | 网络直播营销 — livestream marketing | إضافة إلى التراخيص أعلاه، أداء التزامات التحقق والاحتفاظ | 网络直播营销管理办法（试行） — Measures for the Administration of Livestream Marketing (Trial), Article 8 |
| تقديم الأخبار والمعلومات | 互联网新闻信息服务 — internet news information services | 互联网新闻信息服务许可证 — Internet News Information Service License | 互联网直播服务管理规定 — Provisions on the Administration of Internet Live-Streaming Services, Article 5 |
| بناء مركز بيانات خاص بك لبيع الاستضافة أو النطاق | 互联网数据中心业务 — internet data center (IDC) business; 互联网接入服务业务 — internet access service (ISP) business | 增值电信业务经营许可 — value-added telecom business license (B11, B14) | 电信业务分类目录 — Telecommunications Business Classification Catalogue (2015 edition), B11, B14 |

يذكر تخطيط التراخيص الثلاثة بأوضح عبارة في الرأي الإرشادي (指导意见) الصادر عام 2021 عن سبع إدارات: A livestream platform carrying out commercial online performance activities must hold the 《网络文化经营许可证》 — Network Culture Business License and complete ICP 备案 — ICP filing with MIIT; a livestream platform carrying out internet audio-visual program services must hold the 《信息网络传播视听节目许可证》 — License for the Dissemination of Audio-Visual Programs through Information Networks (or complete registration in the 全国网络视听平台信息登记管理系统 — National Network Audio-Visual Platform Information Registration Management System) and complete ICP 备案 — ICP filing with MIIT; a livestream platform carrying out internet news information services must hold the 《互联网新闻信息服务许可证》 — Internet News Information Service License.

### ثلاث نقاط يسهل الخطأ فيها

**الفرد لا يستطيع الحصول على ترخيص اتصالات ذي قيمة مضافة.** شرط الأهلية الأول هو the operator is a company established in accordance with the law؛ ويجب ألا يقل رأس المال المسجل عن 1,000,000 yuan للتشغيل داخل مقاطعة واحدة وعن 10,000,000 yuan للتشغيل عبر المقاطعات، ومدة المراجعة 60 days، والترخيص صالح لمدة 5 years. ولتشغيل عمل مدفوع تحتاج شركة أولا؛ وتلك الخطوة في القسم 12.

**المشغلون الخواص لا يستطيعون عمليا الحصول على ترخيص البرامج السمعية البصرية.** تنص شروط التقديم على possesses legal-person status and is a wholly state-owned or state-controlled entity. فطريق الفيديو الطويل والبرامج الأصلية مغلق أمام المؤسسين الأفراد؛ ويمر البث المباشر بدلا من ذلك عبر مسار 网络文化经营许可证 — Network Culture Business License track.

**لا تنص أي وثيقة رسمية صراحة على أن منصات التجارة الإلكترونية يجب أن تحصل على EDI.** يقول الدليل الخدمي لـMIIT فقط apply for the corresponding telecommunications business license according to the business definition، وأجاب في موضع آخر بأن ride-hailing platforms only need a website filing وأن equity-type and bulk-commodity trading platforms only need a website filing. لذلك يقتبس هذا الكتاب التعريف الأصلي لـB21 فقط ويترك الحكم لك ولإدارة الاتصالات المحلية 通信管理局 — communications administration؛ واسأل إدارة الاتصالات صاحبة الاختصاص على موقعك مرة قبل التقديم.

## 2. التزامات المنصة اليومية نفسها

الحصول على الترخيص يفتح الباب فقط. والبنود أدناه هي ما تفعله كل يوم؛ والغرامات في مداخل القسم 26.

| الالتزام | الشرط الصلب | المصدر |
|---|---|---|
| التحقق من التجار على المنصة وتسجيلهم | التحقق والتحديث مرة على الأقل كل six months | 网络交易监督管理办法 — Measures for the Supervision and Administration of Online Transactions, Article 24 |
| التبليغ بمعلومات الهوية | التبليغ لسلطات تنظيم السوق في January and July each year | Same measures, Article 25 |
| التبليغ بمعلومات الضرائب | التبليغ للسلطات الضريبية خلال الشهر بعد نهاية كل quarter | 互联网平台企业涉税信息报送规定 — Provisions on the Reporting of Tax-Related Information by Internet Platform Enterprises, Article 4 |
| الاحتفاظ بمعلومات المعاملات | مدة لا تقل عن three years من تاريخ إتمام المعاملة | 电子商务法 — E-Commerce Law, Article 31 |
| الاحتفاظ بمحتوى البث المباشر وسجلاته | Sixty days | 互联网直播服务管理规定 — Provisions on the Administration of Internet Live-Streaming Services, Article 16 |
| الاحتفاظ بمقاطع الأداء عبر الإنترنت | مدة لا تقل عن sixty days | 网络表演经营活动管理办法 — Measures for the Administration of Online Performance Business Activities, Article 13 |
| الاحتفاظ بسجلات الشبكة | مدة لا تقل عن six months | 网络安全法 — Cybersecurity Law, Article 23, Item 3 |
| معالجة إشعارات التعدي | إذا لم يحدث شيء خلال fifteen days بعد إحالة البيان، أعد القائمة | 电子商务法 — E-Commerce Law, Article 43 |
| قناة الشكاوى والتبليغات | موضع بارز وسهلة الاستخدام | 网络信息内容生态治理规定 — Provisions on the Governance of the Online Information Content Ecosystem, Article 16 |

مدد الاحتفاظ أربع ساعات مختلفة: three years للمعاملات، وsixty days للبث المباشر، وsix months للسجلات، وthree years لمعلومات هوية التجار على المنصة، محسوبة من مغادرتهم المنصة. فصمم التخزين على أطولها لا أقصرها.

## 3. اختيار الخادم: كيف تختار بين المستويات الثلاثة

أجب عن الأسئلة أولا، ثم انظر إلى الأسعار.

| السؤال | إذا كان الجواب | فالنتيجة |
|---|---|---|
| هل تتحمل يوما من التوقف | Yes | يكفي أرخص VPS |
| هل لديك تسجيل مستخدمين أو معاملات أو رفع | Yes | استضافة سحابية من مزود سحابي رئيسي، مع لقطات وتوسع مرن |
| هل لديك شخص مخصص للتشغيل | No | ابتعد عن الاستضافة المشتركة للخوادم المخصصة |
| هل النطاق أو تكاليف الأجهزة نفقتك الرئيسية | Yes, and you have someone for operations | عندها فقط فكر في الاستضافة المشتركة للخوادم المخصصة |

**المزودون الصغار ليسوا غير صالحين؛ ويجب التحقق منهم أولا.** فالاستضافة المشتركة لمراكز البيانات وخدمات الوصول نفسها أعمال اتصالات ذات قيمة مضافة تتطلب ترخيصا. تحقق من المزود مرة باسمه الكامل للشركة على نظام MIIT المسمى 电信业务市场综合管理信息系统 — Telecom Business Market Comprehensive Management Information System على tsm.miit.gov.cn، واستبعد تماما من لا ترخيص له. ومن كان بنصف السعر يحمل عادة مخاطر البيع الزائد واختفاء المشغل وحجب المنبع. وعند وقوع أي من الثلاثة، يمكنك مع مزود مرخص أن تشكو إلى إدارة الاتصالات؛ ومع غير المرخص لا تجد من تتظلم إليه أصلا.

**داخل الصين أم خارجها.** إذا كانت الخوادم داخل الصين وجب إتمام التسجيل (备案)، ولا يجوز لمزودي الوصول تقديم الوصول لمواقع غير مسجلة. والاستضافة في الخارج تتجاوز التسجيل، لكن مستخدميك في الصين ومالك في الصين، فلا يسقط أي من الالتزامات في العناصر 5 through 10 من القسم 26، وتضيف طبقة تكلفة امتثال لنقل البيانات عبر الحدود: فنقل المعلومات الشخصية لمستخدمين داخل الصين إلى آلة خارج الصين هو نقل عبر الحدود، ويجب أن يستوفي أحد الشروط الأربعة في المادة Article 38 من 个人信息保护法 — Personal Information Protection Law وأن يحصل على رضا الفرد المنفصل. وتحسب عتبات الأعداد تراكميا من January 1 of the current year: تحت 100,000 people لا ينطبق أي من المسارات الثلاثة؛ ومن 100,000 to 1,000,000 people يلزم عقد معياري أو شهادة؛ وفوق 1,000,000 people يجب تقديم تقييم أمني.

**النسخ الاحتياطية.** احتفظ بنسخ احتياطية في مكانين على الأقل، ولا تضعها كلها في المنطقة نفسها للمزود نفسه. وهذا لا أساس قانوني خلفه؛ بل خبرة.

## 4. حدود هذه الوثيقة

- لكل النصوص يكون عمود المصدر في القسم 26 من README الكتاب هو الحجة؛ وفيه أرقام الوثائق وأرقام المواد والروابط.
- تتحدث اللوائح بسرعة؛ وتحقق هذا القسم في September 2026. وقبل اقتباس أي شيء افتح الصفحة الأصلية بنفسك مرة أخرى، خاصة 网络安全法 — Cybersecurity Law (article numbers were adjusted starting January 1, 2026) وقواعد القاصرين وإهداء البث المباشر (changed in April 2026 to age-based tiers).
- النقاط القليلة التي تعذر الحصول على نصها الأصلي مدرجة في [verification notes](../核实记录/追加-第26节做平台.md)، ومنها أي صياغة رسمية عن هل يجب على منصات التجارة الإلكترونية الحصول على EDI، وتفسير قضائي يجعل التشغيل غير المرخص لخدمات الثقافة عبر الإنترنت أو الخدمات السمعية البصرية جريمة التشغيل التجاري غير القانوني (非法经营罪).
