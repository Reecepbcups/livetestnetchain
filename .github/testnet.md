---
title: New Testnet {{ date | date('dddd MMMM Do') }}
assignees: myusernamehere
labels: enhancement
---
Server IP: {{ env.SERVER_IPV4_ADDR }}
Commit: {{ env.GITHUB_SHA }}
Tag: {{ github.ref_name }}
Local-Interchain API: {{ env.SERVER_IPV4_ADDR }}:{{ env.LOCALIC_AUTH_KEY }}