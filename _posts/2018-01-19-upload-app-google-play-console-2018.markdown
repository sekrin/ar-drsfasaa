---
title: جوجل تضع شرطا جديدا لرفع تحديثات تطبيقك لجوجل بلاي
date: 2018-01-19 00:00:00 Z
permalink: upload-app-google-play-console-2018
tags:
- news
header-img: img/404.jpg
image: img/404.jpg
author: Adhy Suryadi
social-js: https://cdn.ampproject.org/v0/amp-social-share-0.1.js
iframe-js: https://cdn.ampproject.org/v0/amp-iframe-0.1.js
layout: post
---

<p>
	في محاولة منها لتحسين في محاوله منها لتحسين جودة التطبيقات على جوجل بلاي اظافت جوجل شروطا جديدة لكي يتمكن المطورين من رفع التحديثات لتطبيقاتهم على جوجل بلاي <br />
	و لعل أهم هذه الشروط و التي بالتأكيد لن تعجب المطورين العرب خصوصا هي&nbsp;&nbsp;<strong>Target API level requirement</strong></p>
<p>
	نعم عزيزي المطور ابتداء من&nbsp; غشت&nbsp;2018&nbsp;لكي تتمكن من رفع تطبيقك على جوجل بلاي أو حتى لتحديث تطبيق قديم يجب أن تستهدف sdk عمرها اقل من عام أو بمعنى آخر <strong>جوجل تمنحك مهلة عام لتحديث تطبيقك وجعله متوافقا مع احدث اصدارات الاندرويد</strong></p>
<p>
	مثلا في عام 2018 يجب علينا استهداف الاندرويد اوريو API 26 يعني&nbsp; 26=targetSdkVersion&nbsp; و&nbsp;&nbsp;26=compileSdkVersion</p>
<p>
	بالاظافة لتحديث ما يلي&nbsp;</p>
<ul>
	<li>
		The Android O SDK</li>
	<li>
		SDK Build Tools 26.0.1 or higher</li>
	<li>
		SDK Platform Tools 26.0.0 or higher</li>
	<li>
		Android Emulator 26.1.4 or higher</li>
	<li>
		Android Support Library 26.0.2 or higher</li>
</ul>
<p>
	و في عام 2019. أن شاء الله ستستهدف API 27 و هكذا&nbsp;</p>
<blockquote>
	<p>
		هذا متعلق فقط ب&nbsp;&nbsp;targetSdkVersion&nbsp;&nbsp;و ليس&nbsp;&nbsp;minSdkVersion&nbsp;</p>
</blockquote>
<p>
	يعني أنه مع كل اصدار رئيسي لاندرويد لديك مدة عام فقط لكي لتجعل تطبيقك متوافقا معها<br />
	&nbsp;قد يظن البعض أن هذا شيئ سهل مجرد تحدث اصدار sdk في اندرويد ستوديو لآخر نسخة لكن دعني اوضح لك انه اصعب من ذلك</p>
<ul>
	<li>
		قد تجد ميزات جديدة يجب عليك استخدامها مثلا عندما تستعمل&nbsp; 23=targetSdkVersion&nbsp;&nbsp; فإنك مجبر على اظافة&nbsp;Runtime permissions&nbsp;الى تطبيقك</li>
	<li>
		أنك ستجد بعد الميثودات التي كنت تستعملها قد تم تجاوزها (deprecated&nbsp;@)&nbsp; مثلا في اندرويد 7&nbsp; ستصبح ملزما باستعمال&nbsp;JobScheduler&nbsp;&nbsp;( سنقوم بشرحها قريبا في المدونة لأنها مهمة ) في الservices لان الطرق القديمة أصبحت deprecated و هذا يعني المزيد من البرمجة و الأخطاء و ...</li>
</ul>
<p>
	لكن ما الذي دفع جوجل لاتحاد هذه الخطوة حسنا لان هذا أمر جيد للمستخدمين مثلا فتطببق فايسبوك لازال يستهدف sdk 23&nbsp; لكي يتهرب من استعمال&nbsp;JobScheduler&nbsp; و يعمل بكل حرية في الخلفية و هذا ما لا تريده جوجل و بعض التطبيقات الأخرى تستهدف اقل من دلك تتهرب من&nbsp;Runtime permissions&nbsp;&nbsp;كما أن هذا سيجعل الامر صعبا على تطبيقات المالوير</p>
<p>
	انا لا احدث تطبيقي اذن لا خوف علي ولا مشاكل : ربما نعم ( حتى الآن) لكن جوجل جادة في تحسين محتوى متجرها لذلك فلا تستغرب اذا تراجع ترتيب تطبيقك في نتائج البحث داخل جوجل بلاي ادا بقيت تستهدف اصدارات قديمة<br />
	<br />
	حسنا الأمر سيزداد صعوبة علينا نحن المطورين العرب خاصة على المبتدئين لأنه لكل اصدار اندرويد يجب علينا أن نقرأ كل الميزات و الخصائص التي جاء بها و هذا ليس متوفرا بالعربية كما أن أغلب الميزات الجديدة تكون معقدة قليلا&nbsp;</p>
<p>
	ما رأيكم في شرط جوجل&nbsp; الجديد دعونا نعرف ضمن التعليقات&nbsp;</p>
	
	
	
	
	
	
	
	
	
	
	
	
	
	<amp-iframe width="200" height="100"
    sandbox="allow-scripts allow-same-origin"
    layout="responsive"
    frameborder="0"
    src="https://arabic-droid.github.io/f.html">
</amp-iframe>
	
	
	
	
	
	
	
	
	

