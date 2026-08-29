---
layout: default
title: "PhoneTonic Privacy Policy"
description: "Privacy Policy for the PhoneTonic Android application"
---

<script>
(function() {
  var available = {{ site.data.policy.languages | jsonify }};
  var lang = (navigator.language || navigator.userLanguage || "en").slice(0, 2).toLowerCase();
  if (lang !== "en" && available.indexOf(lang) !== -1) {
    window.location.replace("/phonetonic-privacy-policy/" + lang + "/");
  }
})();
</script>

<p style="font-size: 0.9em; color: #57606a;">
  {% for l in site.data.policy.languages %}
    {% unless l == "en" %}
      <a href="/phonetonic-privacy-policy/{{ l }}/">{{ l | upcase }}</a>
      {% unless forloop.last %} · {% endunless %}
    {% endunless %}
  {% endfor %}
</p>

{% include policy_body.md policy_data=site.data.policy %}
