---
title: New Testnet {{ date | date('dddd MMMM Do') }}
assignees: myusernamehere
labels: enhancement
---
Server IP: {{ env.SERVER_IPV4_ADDR }}
Tag: {{ env.GITHUB_REF_NAME }} / Commit: {{ env.GITHUB_SHA }}
Local-Interchain API: {{ env.SERVER_IPV4_ADDR }}:{{ env.LOCALIC_AUTH_KEY }}