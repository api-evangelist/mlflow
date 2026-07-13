---
title: "See What Your AI Sees: Multimodal Tracing for Images, Audio, and Files"
url: "https://mlflow.org/blog/multimodal-tracing/"
date: "2026-04-28"
author: ""
feed_url: "https://mlflow.org/blog/rss.xml"
---
Your agent analyzes images, transcribes audio, and processes PDFs. But when something goes wrong, your traces show nothing but opaque base64 strings: megabytes of iVBORw0KGgo... buried in JSON. You can see that an image was sent, but not what was in it. You can see audio was returned, but you can't play it. And every one of those multi-megabyte strings is stored directly in your trace database, bloating storage costs and slowing down queries.
