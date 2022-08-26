---
width: expand
header:
  image: pattern.svg
  # background: "rgba(0, 0, 0, 0.5)"
  # color: light
  title: Ready to conduct?
  subtitle:
  # search: true
---

{% include categories.html 
  columns="3" 
  section="muted" 
%}

{% include faqs.html 
  multiple="true" 
  title="Frequently asked questions" 
  category="faq" 
  subtitle="Got a question?" 
  section="muted" 
%}

{% include cta.html 
  title="Didn't find an answer?" 
  button_text="Join the Community" 
  button_url="https://discord.gg/XVSV72Sn" 
  subtitle="Join the Community Discord to get in touch!" 
  section="muted"
%}
