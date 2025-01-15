---
title: "Redirecting..."
layout: "redirect"
url: "https://instagram.com/oftenkaran"
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="refresh" content="0; url={{ .Params.url }}">
    <title>{{ .Title }}</title>
</head>
<body>
    <p>If you are not redirected automatically, follow this <a href="{{ .Params.url }}">link</a>.</p>
</body>
</html>
