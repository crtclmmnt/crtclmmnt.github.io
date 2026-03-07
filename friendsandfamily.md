---
layout: default
permalink: /friendsandfamily/
---

<img src="/images/pano8.JPG" alt="About header" class="hero-image">

<h1 style="font-size: 4rem; margin-bottom: 0px;">Meditation Sits for Friends and Family</h1>

<hr class="short" style="margin: 0.5em 0;">

<p>Congratulations on finding the secret page! If you'd like to be part of the weekly sit I hold for friends and family, book it below to get a calendar invite.</p>

<p>My main reason for having this page look so prim and proper is that I need to test out the digital infrastructure of Cal.com before I start using it for public-facing workshops and instruction. Thank you for helping me learn!</p>

<br>

<hr>

<br>

<!-- Cal inline embed code begins -->
<div style="width:100%;height:100%;overflow:scroll" id="my-cal-inline-friends-and-family-sit"></div>
<script type="text/javascript">
  (function (C, A, L) { let p = function (a, ar) { a.q.push(ar); }; let d = C.document; C.Cal = C.Cal || function () { let cal = C.Cal; let ar = arguments; if (!cal.loaded) { cal.ns = {}; cal.q = cal.q || []; d.head.appendChild(d.createElement("script")).src = A; cal.loaded = true; } if (ar[0] === L) { const api = function () { p(api, arguments); }; const namespace = ar[1]; api.q = api.q || []; if(typeof namespace === "string"){cal.ns[namespace] = cal.ns[namespace] || api;p(cal.ns[namespace], ar);p(cal, ["initNamespace", namespace]);} else p(cal, ar); return;} p(cal, ar); }; })(window, "https://app.cal.com/embed/embed.js", "init");
Cal("init", "friends-and-family-sit", {origin:"https://app.cal.com"});

  Cal.ns["friends-and-family-sit"]("inline", {
    elementOrSelector:"#my-cal-inline-friends-and-family-sit",
    config: {"layout":"month_view","useSlotsViewOnSmallScreen":"true","theme":"light"},
    calLink: "thecriticalmoment/friends-and-family-sit",
  });

  Cal.ns["friends-and-family-sit"]("ui", {"theme":"light","cssVarsPerTheme":{"light":{"cal-brand":"#a23c3f"},"dark":{"cal-brand":"#f1e6c9"}},"hideEventTypeDetails":false,"layout":"month_view"});
  </script>
  <!-- Cal inline embed code ends -->