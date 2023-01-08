# email-varifier-tool
Email varifier tool using Golang 
Here is the Small Example of testing

go run main.go
domain,hasMX,hasSPF,spfRecord,hasDMARC,dmarcRecord

mailchimp.com
mailchimp.com,true,true,v=spf1 include:servers.mcsv.net include:mail.zendesk.com include:_spf.google.com 
include:mailsenders.netsuite.com ip4:199.33.145.1 ip4:199.33.145.32 ip4:35.176.132.251 ip4:52.60.115.116 ~all,true,
v=DMARC1; p=reject; rua=mailto:19ezfriw@ag.dmarcian.com; ruf=mailto:19ezfriw@fr.dmarcian.com

