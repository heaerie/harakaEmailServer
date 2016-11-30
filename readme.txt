durai@durai-VirtualBox:/tmp/haraka_demo/config$ swaks -h haraka.test -f durai145@gmail.com -t matt@haraka.test -s localhost -p 2525
=== Trying localhost:2525...
=== Connected to localhost.
<-  220 durai-VirtualBox ESMTP Haraka 2.8.11 ready
 -> EHLO haraka.test
<-  250-durai-VirtualBox Hello Unknown [127.0.0.1], Haraka is at your service.
<-  250-PIPELINING
<-  250-8BITMIME
<-  250 SIZE 0
 -> MAIL FROM:<durai145@gmail.com>
<-  250 sender <durai145@gmail.com> OK
 -> RCPT TO:<matt@haraka.test>
<-  250 recipient <matt@haraka.test> OK
 -> DATA
<-  354 go ahead, make my day
 -> Date: Tue, 29 Nov 2016 23:19:08 -0500
 -> To: matt@haraka.test
 -> From: durai145@gmail.com
 -> Subject: test Tue, 29 Nov 2016 23:19:08 -0500
 -> X-Mailer: swaks v20130209.0 jetmore.org/john/code/swaks/
 -> 
 -> This is a test mailing
 -> 
 -> .
<-  250 Message Queued (EE8D66D9-E976-47DF-A6D7-83BEFD06DD9D.1)
 -> QUIT
<-  221 durai-VirtualBox closing connection. Have a jolly good day.

