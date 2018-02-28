# tldrsales
Documenting the genesis and evolution of the site tldrsales.com

My name is Steve.  I am a sales and marketing professional who enjoys learning about and tinkering with tech on the side.  I'm building out this site and using GitHub as a project management repository in the hopes that it will help someone else out there on their journey.  You can reach out to me at Steve@tldrsales.com if you have any questions or comments.

2/28/18 06:48 AM - Created and published blank terms of service and privacy policy pages. Used helpful tool at http://www.formswift.com to autogenerate legal terms of service document.

2/28/18 10:43 AM - Created and published privacy policy. Used helpful too at https://www.freeprivacypolicy.com/ to auto-generate the required verbiage.

2/28/2018 2:53 PM - Have been taken down a rabbit hole on getting a SSL certificate.  Part of the questionnaire at the privacy policy generator above asked about whether or not I would be gathering personal information (yes, emails - hopefully). Led me to buying a Comodo SSL certificate from http://www.ssls.com ($3.83) and spending the next couple of hours working to get it issued and then upload the certificate, .ca bundle, and RSA key uploaded via my cPanel. Reached out to hosting provider to install the certificate for a 1 time fee ($10).  Inadvertently requested the certificate be uploaded to the incorrect domain so had to correct for another ($10).  Lesson learned.  Waiting to see next step from hosting provider in the process.

2/28/2018 3:29 PM - Working to verify domain with Amazon SES as a step to get out of the sandbox.  Used cPanel Advanced Zone Editor tool to create .txt domain name verification record and DKIM CNAME record sets.  Used TTL = 3600.

2/28/2018 4:20 PM - Submitted request to SES to move from sandbox to production environment. Needed to review process for handling bounce/complaint process and found documentation in SendyPro describing the process.
