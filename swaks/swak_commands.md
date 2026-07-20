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
