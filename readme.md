Invoke-WebRequest -UseBasicParsing -Uri "https://www.att.com/msapi/outage/v1/internet/zip" `
-Method "POST" `
-Headers @{
"authority"="www.att.com"
  "method"="POST"
  "path"="/msapi/outage/v1/internet/zip"
  "scheme"="https"
  "accept"="application/json"
  "accept-encoding"="gzip, deflate, br, zstd"
  "accept-language"="en-US,en;q=0.9"
  "access-control-allow-credentials"="undefined"
  "access-control-allow-origin"="*"
  "dnt"="1"
  "origin"="https://www.att.com"
  "priority"="u=1, i"
  "referer"="https://www.att.com/outages/"
  "sec-ch-ua"="`"Google Chrome`";v=`"131`", `"Chromium`";v=`"131`", `"Not_A Brand`";v=`"24`""
  "sec-ch-ua-mobile"="?0"
  "sec-ch-ua-platform"="`"Windows`""
  "sec-fetch-dest"="empty"
  "sec-fetch-mode"="cors"
  "sec-fetch-site"="same-origin"
} `
-ContentType "application/json" `
-Body "{`"zipCode`":`"12345`"}"
