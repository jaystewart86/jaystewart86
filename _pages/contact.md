---
layout: splash
permalink: /contact/
---

## WhatsApp

<a href="https://api.whatsapp.com/send?phone=529581745848" class="btn btn--light-outline btn--large"><i class="fa fa-whatsapp"></i> Contact now</a>

## Introduction

<!-- Cal inline embed code begins -->
<div style="width:100%;height:100%;overflow:scroll" id="my-cal-inline"></div>
<script type="text/javascript">
  (function (C, A, L) { let p = function (a, ar) { a.q.push(ar); }; let d = C.document; C.Cal = C.Cal || function () { let cal = C.Cal; let ar = arguments; if (!cal.loaded) { cal.ns = {}; cal.q = cal.q || []; d.head.appendChild(d.createElement("script")).src = A; cal.loaded = true; } if (ar[0] === L) { const api = function () { p(api, arguments); }; const namespace = ar[1]; api.q = api.q || []; typeof namespace === "string" ? (cal.ns[namespace] = api) && p(api, ar) : p(cal, ar); return; } p(cal, ar); }; })(window, "https://app.cal.com/embed/embed.js", "init");
Cal("init", "15min", {origin:"https://cal.com"});

  Cal.ns["15min"]("inline", {
	elementOrSelector:"#my-cal-inline",
	calLink: "jaystewart/15min",
	layout: "month_view"
  });
  
  Cal.ns["15min"]("ui", {"styles":{"branding":{"brandColor":"#000000"}},"hideEventTypeDetails":false,"layout":"month_view"});
  </script>
  <!-- Cal inline embed code ends -->