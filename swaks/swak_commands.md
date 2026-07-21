swaks \
  --to "support@altovian.net" \
  --from "sajika.gallege@altovian.net" \
  --header "Subject: DMARC spoof-control test (authorized, Phase 7)" \
  --body "Authorized spoofing-control test per the signed assessment plan. Check inbox/spam placement and the SPF/DKIM/DMARC verdict in the received headers." \
  --server mail.altovian.net

  swaks \
  --to "altovian.info@gmail.com" \
  --from "sajika.gallege@altovian.net" \
  --header "Subject: AltoShield P7" \
  --body "Alto test mail" \
  --server gmail-smtp-in.l.google.com

 swaks \
  --to "sajika.gallege@altovian.net" \
  --from "kusal.gautamadasa@altovian.net" \
  --header "Subject: Job status for Swam Rakhas" \
  --body "Please send me a full update on above candidate, as per discussion." \
  --server mail.altovian.net \
  --ehlo altovian.net

  === Trying mail.altovian.net:25...
=== Connected to mail.altovian.net.
<-  220-server343.web-hosting.com ESMTP Exim 4.99.4 #2 Mon, 20 Jul 2026 10:21:04 -0400 
<-  220-We do not authorize the use of this system to transport unsolicited, 
<-  220 and/or bulk e-mail.
 -> EHLO altovian.net
<-  250-server343.web-hosting.com Hello altovian.net [112.134.168.169]
<-  250-SIZE 52428800
<-  250-LIMITS MAILMAX=1000 RCPTMAX=100
<-  250-8BITMIME
<-  250-PIPELINING
<-  250-PIPECONNECT
<-  250-STARTTLS
<-  250 HELP
 -> MAIL FROM:<kusal.gautamadasa@altovian.net>
<-  250 OK
 -> RCPT TO:<sajika.gallege@altovian.net>
<-  250 Accepted
 -> DATA
<-  354 Enter message, ending with "." on a line by itself
 -> Date: Mon, 20 Jul 2026 19:50:40 +0530
 -> To: sajika.gallege@altovian.net
 -> From: kusal.gautamadasa@altovian.net
 -> Subject: Job status for Swam Rakhas
 -> Message-Id: <20260720195040.074062@10.154.245.245>
 -> X-Mailer: swaks v20240103.0 jetmore.org/john/code/swaks/
 -> 
 -> Please send me a full update on above candidate, as per discussion.
 -> 
 -> 
 -> .
<-  250 OK id=1wlos3-00000008qwF-0Tzy
 -> QUIT
<-  221 server343.web-hosting.com closing connection
=== Connection closed with remote host.


swaks \
  --to "supun.samarasinghe@altovian.net" \
  --from "kusal.gautamadasa@altovian.net" \
  --header "Subject: Job status for Swam Rakhas" \
  --body "Please send me a full update on above candidate, as per discussion." \
  --server mail.altovian.net \
  --ehlo altovian.net
