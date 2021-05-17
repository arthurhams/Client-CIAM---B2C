# Client CIAM - a sample RFI for Azure AD B2C (External Identities)

<h2>Disclaimer</h2>
This document is provided as-is without any warranty. It is intended as inspiration only. 

<h2>Intro</h2>

This overview is the response for a CIAM solution using Azure AD B2C. As our services continue to evolve rapidly, one or more given answers may already be superceded by new features or services. <br />
<br />


<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width=1049
 style='width:787.0pt;border-collapse:collapse'>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border:solid #8EA9DB 1.0pt;
  border-right:none;background:#4472C4;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><b><span
  lang=NL style='color:white'>#</span></b></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border-top:solid #8EA9DB 1.0pt;
  border-left:none;border-bottom:solid #8EA9DB 1.0pt;border-right:none;
  background:#4472C4;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><b><span
  lang=NL style='color:white'>Category</span></b></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border-top:solid #8EA9DB 1.0pt;
  border-left:none;border-bottom:solid #8EA9DB 1.0pt;border-right:none;
  background:#4472C4;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><b><span
  lang=NL style='color:white'>User Story</span></b></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border-top:solid #8EA9DB 1.0pt;
  border-left:none;border-bottom:solid #8EA9DB 1.0pt;border-right:none;
  background:#4472C4;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><b><span
  lang=NL style='color:white'>Response from Vendor</span></b></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:168.8pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:168.8pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>1</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:168.8pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>360� view of customer</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:168.8pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to know as
  much as possible about (analyse) my customers so that I can optimally act on
  developments I see</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:168.8pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As Azure AD B2C is part of the Azure platform,
  it can benefit from the wealth of the products, services and features it is
  surrounded by. Application Insights is an advanced, intelligent logging,
  monitoring and visualisation tool to gain insights in usage, experience,
  performance and other metrics and flows from and to B2C. <br>
  Alternatively one could use one of our outher cloud products, Dynamics 365
  Customer Insights to build a deep understanding of customers by connecting
  customer data from various transactional, behavioral, and observational
  sources to create a 360-degree customer view. Use these insights to drive customer-centric
  experiences and processes.. Unify your data by resolving customer identities
  with recommendations based on AI and machine learning. Build rich customer
  profiles by incorporating audience intelligence from Microsoft Graph.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-custom-guide-eventlogger-appins"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-custom-guide-eventlogger-appins<br>
  https://dynamics.microsoft.com/en-us/ai/customer-insights/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:85.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:85.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>2</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:85.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>360� view of customer</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:85.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to keep track of patterns of customers/companies that are using my services.
  Also when a specific employee of my customer is replaced by someone else</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:85.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As B2C is only the Identity-provider, the full
  track of patterns is a combination of different sources. For end-to-end user
  tracking and intelligence like patterns, <i>Client</i> side libraries like
  Application Insights, but also alternatives like for example Google Analytics
  &amp; Optimize can be used.<br>
  Alternatively, Dynamics 365 Customer Insights can be used</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-activity-logs-azure-monitor"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-activity-logs-azure-monitor<br>
  https://docs.microsoft.com/en-us/dynamics365/ai/customer-insights/overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>3</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Access Management (Claims)</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to manage roles and rights assigned to customer acounts</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Users can be managed via Groups or Claims, as
  Administrators can have roles assigned for delegation.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://devblogs.microsoft.com/premier-developer/using-groups-in-azure-ad-b2c/"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/fun<i>Client</i>tals/active-directory-groups-create-azure-portal<br>
  https://devblogs.microsoft.com/premier-developer/using-groups-in-azure-ad-b2c/<br>
  https://docs.microsoft.com/azure/active-directory-b2c/active-directory-b2c-reference-custom-attr</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>4</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Access Management (Claims)</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to report roles and rights assigned to customer acounts</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C has a built in Overview in the
  Azure Portal of all users and their attributes. To use the information in a
  custom report or automated, one can create a query using the AD Graph API</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-devquickstarts-graph-dotnet?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview<br>
  https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-devquickstarts-graph-dotnet?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>5</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Access Management (Claims)</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to audit roles and rights assigned to customer acounts</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Audit logging is a standard feature in Azure
  AD B2C</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>6</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Access Management (Claims)</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to easily tranfser roles and rights from one person to another</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure B2C is an Identity platform that is
  agnostic of it's users and their claims and/or roles. It will require some
  customization to copy/clone <i>Client</i> specific
  properties/attributes/roles between different users </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/azure/active-directory-b2c/active-directory-b2c-reference-custom-attr"><span
  lang=EN-US>https://docs.microsoft.com/azure/active-directory-b2c/active-directory-b2c-reference-custom-attr</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>7</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Access Management (Claims)</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to assign time limited roles and rights (subscriptions)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>AS B2C is an extensible platform. Time limited
  roles and rights can be accomplished by a Custom Policy and a Custom API
  (that for example grants access and/or refresh tokens with different
  lifetimes)</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>8</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Account Validation</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to validate a customer account when they are created</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This can be accomplished by the use of a
  custome policy. During authentication/registration every attribute can be
  verified and based on that a decission can be made.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-policies"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-policies</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>9</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Account Validation</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to prevent fake/bot
  accounts to be created</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Javascript is supported so this can be
  achieved with techniques like CAPTCHA. We also have Azure AD identity
  protection in preview for B2C</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>10</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to set different authentication requirements depending on the service that is
  used</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Supported in B2C using a custom policy, we can
  redirect a user back based on a specific action and only require to do a
  second factor</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>11</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to set different authentication requirements depending on the location/device
  that is used</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Possible using a custom policy</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>12</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want to integrate my
  existing employe accounts/identities(in Azure AD) to integrate with the CIAM
  solution</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>AAD can be an authentication provider for B2C</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-setup-aad-custom?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-setup-aad-custom?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>13</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require built in support
  for multi-factor authentication (MFA) that includes security questions,
  smartphone soft tokens apps with push capability, or SMS (text message) as
  optional factors, email, WebAuthN, biometrics.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Out of the box: Phone Call + TEXT, App soon.
  Custom policy: WebAuthn and one time code. Q+A gate can be done using
  customer policy but we would never recommend</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-methods"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-methods</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>14</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the ability to
  easily add any web-based app with a login form to the IAM solution, if
  needed, using a simple wizard-based approach.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>We do not do password vaulting type of
  solutions with B2C. SAML, OpenID are required for an app to connect</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>15</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require enhanced password
  policy with ability to configure complexity requirements, password age and
  lockout attempts.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The password complexity policy is configurable</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-password-complexity"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-password-complexity</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>16</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the solution can
  analyze and detect abnormal patterns in� IP addresses, when attempting to
  authenticate</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>B2C Threatmanagement is in place. Further
  capabilities are in testing</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-threat-management"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-threat-management</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>17</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Adaptive Authentication</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the solution
  support passwordless authentication options including email credential links,
  WebAuthN or factor sequencing </span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Requires custom policy, examples can be found
  on our GitHub</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a href="https://github.com/azure-ad-b2c/samples"><span
  lang=EN-US>https://github.com/azure-ad-b2c/samples</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>18</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Architecture</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I most prefer a cloud native
  solution SaaS solution</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C is a full cloud SAAS service
  build from the ground up as a native cloud service.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://azure.microsoft.com/en-us/resources/videos/consumer-identity-and-access-management-in-the-cloud-azure-ad-b2c/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/resources/videos/consumer-identity-and-access-management-in-the-cloud-azure-ad-b2c/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>19</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Architecture</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want a CIAM supplier with
  an agile development process with feature releases on a weekly basis. Service
  is updated without being taken offline.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Microsoft provides redundant and transparent
  updating of this service without downtime</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://azure.microsoft.com/nl-nl/blog/advancing-microsoft-azure-reliability/"><span
  lang=EN-US>https://azure.microsoft.com/nl-nl/blog/advancing-microsoft-azure-reliability/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>20</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Architecture</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> Architecture I want to have a
  high level overview on the CIAMs supported deployment and service
  models(SaaS, PaaS, IaaS, On-prem)?</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>With the enormous use of all Azure Services,
  proper and up-to-date documentation is key for our success, not only for
  Azure AD B2C, but for all Services we provide globally. </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>21</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Architecture</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> Architecture I want to have a
  high level overview on the CIAM technology and application
  architecture(tiering, virtual machines, microservices, connectiity, etc)?</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Although Azure AD B2C has the well documented
  extensiblity and customization options like a Platform, it is hosted as a SaaS
  solution and therefor the underlying architecture is not publicly accessible.
  It there are any specific questions or concerns, plesae let us know.</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>22</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Auditing</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all actions in the
  CIAM solution to be logged with a retention of 1 year</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Audit logs will be kept for 30 days but can be
  exported using the API� (using automation and onto Azure Storage for example)
  and saved as long as required. </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>23</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Auditing</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require detailed audit logs
  of what users do, see, change and delete</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This information is typically captured in the
  Audit Logs</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>24</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Auditing</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all audit logs to
  be in industry standard format</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Export to CSV supported</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-audit-logs?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>25</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Auditing</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all audit logs to
  have timestamps to be in UTC</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is the Standard for all logging in Azure.</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>26</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>B2B2B use case connected vehicles</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to give <i>Client</i> customers access to 3rd party services that <i>Client</i>
  resells</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This can be achieved with Custom policies and
  Group assignment</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview-custom</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>27</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>B2B2B use case connected vehicles</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to give access to the information of the <i>Client</i> customer IOT connected
  vehicles to 3rd party companys of which <i>Client</i> resells services</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>B2C can be used to assign access to external
  API/Applications </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/nl-nl/azure/active-directory-b2c/tutorial-register-applications?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/nl-nl/azure/active-directory-b2c/tutorial-register-applications?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>28</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Brand control customizations</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to customize the look and feel of the customer login screens among all of my
  channels</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The Identity Experience Framework is fully
  customizable using CSS, CORS, javascript etc</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-get-started-custom?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-get-started-custom?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:46.9pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:46.9pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>29</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:46.9pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Brand control customizations</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:46.9pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to conceal/hide/mask/cover the vendor information in the URL of the login
  screens amoung all of my channels</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:46.9pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>B2CLogin.com now supported as 'unbranded
  domain' and Custom domains are also available through a request process</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>https://docs.microsoft.com/en-us/azure/active-directory-b2c/b2clogin
  <br>
  Sample on Custom Domain: https://www.Fifa.com/<br>
  Sample on B2C: https://www.ajax.nl/</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>30</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Brand control customizations</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to personalize the information presented depending on the customer</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Use for example the URL querystring and
  javascript to show or hide specific information on the page</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/nl-nl/azure/active-directory-b2c/javascript-samples"><span
  lang=EN-US>https://docs.microsoft.com/nl-nl/azure/active-directory-b2c/javascript-samples</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>31</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all data in the
  CIAM solution to be exportable in non-prorietary format and without support
  of the supplier</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>There is a lot of documetnation about User
  Migration and/or querying</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-devquickstarts-graph-dotnet?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-devquickstarts-graph-dotnet?tabs=applications
  </span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>32</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require to export all our
  data without additional charge</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Export data using the API is included</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>33</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require a minimum
  availability SLA of 99,9% for the CIAM solution</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is the SLA.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://azure.microsoft.com/en-us/support/legal/sla/active-directory-b2c/v1_0/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/support/legal/sla/active-directory-b2c/v1_0/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>34</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require solution to be
  designed without Single Point of Failures</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As it is hosted on Azure a P/SaaS, each
  instance has geo redundant fault and updates zones by default, comparable to
  Azure AD</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-architecture"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/fun<i>Client</i>tals/active-directory-architecture</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>35</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require solution to have a
  documented backup policy</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The backup policy is documented in our
  Whitepaper</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a href="https://aka.ms/aaddatawhitepaper">https://aka.ms/aaddatawhitepaper</a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>36</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the backup
  retention to be at least 30 days</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The backup retention is documented in our
  Whitepaper</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a href="https://aka.ms/aaddatawhitepaper">https://aka.ms/aaddatawhitepaper</a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>37</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the recovery time
  object of data restores to be maximum 5 days</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The RTO is documented in our Whitepaper</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a href="https://aka.ms/aaddatawhitepaper">https://aka.ms/aaddatawhitepaper</a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>38</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the backup of my
  data to be stored on different infrastructure in a different region from my
  primary data</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>All data will be replicated and synchronized
  to a minimum of 3 datacenters in the same region (Europe)</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-architecture"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/fun<i>Client</i>tals/active-directory-architecture</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>39</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> want to be able to make a
  backup of my data stored at cloud service providers under my own governance</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Use the Graph API to export data and store
  under <i>Client</i>s conditions.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/manage-user-data"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/manage-user-data</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>40</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want to be able to have point-in-time
  and item-level restore capabilities</span></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>After you delete a user, the account remains
  in a suspended state for 30 days. During that 30-day window, the user account
  can be restored, along with all its properties. After that 30-day window
  passes, the user is automatically, and permanently, deleted.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-users-restore"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/fun<i>Client</i>tals/active-directory-users-restore</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>41</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the CIAM solution
  to have a documented disaster recovery policy</span></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please visit our TrustCenter for insights on
  this requirement</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://www.microsoft.com/de-de/trust-center/product-overview"><span
  lang=EN-US>https://www.microsoft.com/de-de/trust-center/product-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>42</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require a disaster recovery
  point objective of maximum 1 hour</span></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please visit our TrustCenter for insights on
  this requirement</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://www.microsoft.com/de-de/trust-center/product-overview"><span
  lang=EN-US>https://www.microsoft.com/de-de/trust-center/product-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>43</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require a disaster recovery
  time objective of 24 hours</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please visit our TrustCenter. <br>
  Please note that our service is build as a high available, distributed native
  cloud system which stores a minimum of 3 copies across 3 datacenter</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://www.microsoft.com/de-de/trust-center/product-overview"><span
  lang=EN-US>https://www.microsoft.com/de-de/trust-center/product-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>44</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the disaster
  recovery test to performed at least annually</span></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please visit our TrustCenter for insights on
  this requirement</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://www.microsoft.com/de-de/trust-center/product-overview"><span
  lang=EN-US>https://www.microsoft.com/de-de/trust-center/product-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>45</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Business Continuity</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require an SLA which does
  not allow for planned downtime for maintenance windows - i.e. &quot;planned
  downtime&quot; is not acceptable.</span></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please visit our TrustCenter for insights on
  this requirement</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://www.microsoft.com/de-de/trust-center/product-overview"><span
  lang=EN-US>https://www.microsoft.com/de-de/trust-center/product-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>46</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Contract</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require a termination
  clause to be in the contract</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C is provided as a Pay-as-you-Go
  (PAYG) service, it is up to <i>Client</i> to use the service or not without
  any obligations</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>47</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Contract</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require a documented exit
  procedure/policy which includes support from the supplier in exiting and
  transitioning from the service</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The service allows for export and Backup of
  Data.<br>
  In case of an exit from AAD B2C, Microsoft can offer commercial Migration
  Services by Microsoft Consulting Services</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/manage-user-data"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/manage-user-data</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>48</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Data/identity storage</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> we want a stable, flexible,
  secure and scalable storage platform/database to store customer related data</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>The underlying Azure Platform caters for this
  in a secure, reliable and scala ble way.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a href="https://aka.ms/aaddatawhitepaper">https://aka.ms/aaddatawhitepaper</a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>49</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to create extra <i>Client</i> accounts for people within my company</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C provides the concept of Local
  Accounts </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>50</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to manage the <i>Client</i> accounts that are used within my company</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This can be achieved with domain filtering</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>51</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to upgrade an account from &quot;basic&quot; to &quot;professional&quot;
  where those two accounts have access to different services</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Custom Claims can be of any type, including
  for example any subscription or membership type.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a href="https://github.com/azure-ad-b2c/samples"><span
  lang=EN-US>https://github.com/azure-ad-b2c/samples</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>52</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to assign roles and rights to the accounts within my company</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C supports custom claims, which can
  be used to add app based roles or via custom policy</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/azure/active-directory-b2c/active-directory-b2c-reference-custom-attr"><span
  lang=EN-US>https://docs.microsoft.com/azure/active-directory-b2c/active-directory-b2c-reference-custom-attr</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>53</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to invite users to create an account</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Standard (or customized) Sign-up flow</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://github.com/azure-ad-b2c/samples/tree/master/policies/invite"><span
  lang=EN-US>https://github.com/azure-ad-b2c/samples/tree/master/policies/invite</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>54</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to register
  one account that can be used by multiple employees</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Although Credential Sharing is highly insecure
  and prone to misuse, B2C can be used this way. Please know that we are happy
  to find alternatives for this scenario</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>55</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Delegated Administration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the ability to
  provide trusted external organizations that only have a directory an IAM
  service, in order to federation to a common portal. This includes independent
  divisions of a large enterprise or business partners and customers.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Segoe UI",sans-serif;
  color:#171717'>For external identities, Azure AD B2C supports federation with
  any OAuth 1.0, OAuth 2.0, OpenID Connect, SAML, and WS-Fed identity provider.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/technical-overview#protocols-and-tokens"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/technical-overview#protocols-and-tokens</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>56</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Device Agnostic</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to sign in to my <i>Client</i> customer account with the same userfriendly
  experience on all my devices</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C has the concept of seamless user
  experiences</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/technical-overview#seamless-user-experiences"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/technical-overview#seamless-user-experiences</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>57</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Device Agnostic</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to sign up for a <i>Client</i> customer account with the same userfriendly
  experience on all my devices</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C has the concept of external
  identity providers</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/technical-overview#external-identity-providers"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/technical-overview#external-identity-providers</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>58</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Device Agnostic</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to sign out for a <i>Client</i> customer account with the same userfriendly
  experience on all my devices</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C has the concept of seamless user
  experiences</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/manage-user-data"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/manage-user-data</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>59</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Digital Identity proofing</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to verify the identity of the customer</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Custom flows supports adding additional
  verification steps</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>60</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Digital Identity proofing</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to use/give access to a 3rd party that verifies the identity of <i>Client</i>
  customers</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>you can use external or generic identity
  provider and add for example MFA as an extra verification step </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-setup-oidc-idp"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-setup-oidc-idp</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>61</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>E-mail</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all emails send to
  customers to be coming from an @<i>Client</i>.com e-mail address</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>this feature is in private preview, using
  custom policies.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-disable-ev"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-disable-ev</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>62</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>E-mail</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all emails send to
  customers to be send through <i>Client</i> managed email infrastructure</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>this feature is in private preview, using
  custom policies. Please contact us for more details</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>63</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>E-mail</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I do not want any reference
  or marketing to the CIAM provider in the emails I send to customers</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>this feature is in private preview, using
  custom policies. Please contact us for more details</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>64</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>End User URL</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want all portals or
  webpages to only be accessible via a URL provided and managed by <i>Client</i>(*.<i>Client</i>.com)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is a produciton-ready feature that
  currently needs to be requested seperately</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:71.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>65</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Integration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require programmatic
  access(APIs) to the IAM to allow the IAM solution to be used as the identity
  layer within a custom-built web application or multi-tenant cloud service.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>For web applications (including .NET, PHP,
  Java, Ruby, Python, and Node.js) that are hosted on a server and accessed
  through a browser, Azure AD B2C supports OpenID Connect for all user
  experiences. In the Azure AD B2C implementation of OpenID Connect, your web
  application initiates user experiences by issuing authentication requests to
  Azure AD.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><u><span
  lang=EN-US style='color:#0563C1'>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-apps</span></u></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>66</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Integration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the CIAM to have
  secure authentication for APIs</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>All Azure services, including those of B2C,
  are exposed under the Azure Role Based Access (RBAC). This allows for
  (extremely) fine grained access with different rights per role on services
  and features </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/role-based-access-control/overview"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/role-based-access-control/overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>67</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Integration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the CIAM to have
  real time monitoring of all integrations</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is part of different Azure Monitoring
  &amp; logging functionalities</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform-logs"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform-logs</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>68</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Integration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require Programmatic
  interface that is exposed as REST API endpoints.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This API is called the Graph API</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/nl-nl/azure/active-directory-b2c/active-directory-b2c-devquickstarts-graph-dotnet?tabs=applications"><span
  lang=EN-US>https://docs.microsoft.com/nl-nl/azure/active-directory-b2c/active-directory-b2c-devquickstarts-graph-dotnet?tabs=applications</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>69</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Integration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the ability for IT
  admins and developers to react to events that are happening within the IAM
  service and notify external systems with a webhook.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure Alerts Framework supports webhooks
  (amongst others). We also have native connectors to common ITSM solutions
  like ServiceNow</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-log-webhook"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-log-webhook</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>70</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>IOT devices</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to register/authenticate IOT devices under my personal emloyee company
  account</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As long as the iot device can be registered as
  an entitiy, this can be done similiar an user account</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>71</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>IOT devices</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to register/authenticate IOT devices under my generic corporate account</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As long as the iot device can be registered as
  an entitiy, this can be done similiar an user account</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>72</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>IOT devices</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to give access to the IOT connected devices to <i>Client</i> customers</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As long as the iot device can be registered as
  an entitiy, this can be done similiar an user account</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>73</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>IOT devices</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to give access to the IOT connected devices to 3rd parties of which I resell
  services</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As long as the iot device can be registered as
  an entitiy, this can be done similiar an user account</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>74</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>IOT devices</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require to support IoT
  devices with Auth2.0 Device Flow </span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is not a standard feature of Azure AD
  B2C, but it is supported by Azure AD out of the box, or could be
  implementated using custom policies and API's. As Azure houses a number of
  advanced IoT Services, we'd love to learn the usecase and explore the
  possibilities. </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-device-code"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-device-code</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>75</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Multichannel support</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want my <i>Client</i>
  customers to login to all my channels</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Map all chanels to B2C Tenant</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>76</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Multichannel support</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to login to
  all <i>Client</i> channels with my <i>Client</i> customer account/identity</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Store all accounts in that Tenant</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>77</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Multilanguage support</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to interact with <i>Client</i> in my own language (login screen in own
  language)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>A large number of languages is supported, they
  are customizable and additional languages can be added if needed </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-language-customization"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-language-customization</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>78</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want
  real-time insight in the actual KPIs like availability and performance of the
  CIAM paltform</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure supports a large number of system
  metrics</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-custom-guide-eventlogger-appins"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-custom-guide-eventlogger-appins</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>79</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want monthly
  reports on KPIs like availability and performance of the CIAM paltform</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>you can use the KPIs to be analyzed in
  external BI Tools, like PowerBI</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://powerbi.microsoft.com/nl-nl/what-is-power-bi/"><span
  lang=EN-US>https://powerbi.microsoft.com/nl-nl/what-is-power-bi/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>80</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want clear
  description of which roles and responsibilities are involved with what
  party(customer, supplier, third parties) to support and maintain the solution</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure services are provided according to our
  Online Services Terms.<br>
  <i>Client</i> is also entitled to Premier Support</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a href="https://azure.microsoft.com/en-us/support/legal/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/support/legal/<br>
  https://www.microsoft.com/en-us/enterprise/services/support</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>81</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want clear
  Incident response and resolution/remediation SLAs</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>All Azure Services that are consumed through
  the Enterprise Agreement are covered by Standard Azure Support</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://azure.microsoft.com/en-us/offers/enterprise-agreement-support/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/offers/enterprise-agreement-support/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>82</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want all
  communication and portals to be available in English</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>English is the default, 17 other languages are
  being supported</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>83</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want a
  24/7/365 available incident reporting channel</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Provided directly in the portal</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://azure.microsoft.com/en-us/support/create-ticket/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/support/create-ticket/ </span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>84</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I want a
  24/7/365 available escaltion direct contact(phone)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is both part of the Azure Standard
  Support plan from the EA and escalation can be handled through the existing
  Premier Support plan</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>85</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I require
  multiple roles for administration in the CIAM solution, including read-only
  access to the configuration, access to the configuration without access to
  data</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Different roles can be assigned using Azure
  RBAC</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><u><span
  lang=EN-US style='color:#0563C1'>https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/directory-assign-admin-roles</span></u></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>86</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I require to
  control access permissions in a granular way supporting least privilege
  principle</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Different roles can be assigned using Azure
  RBAC</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><u><span
  lang=EN-US style='color:#0563C1'>https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/directory-assign-admin-roles</span></u></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>87</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I require
  automation capabilities for maintaining customer digital identities/accounts</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Use Graph API, for example with PowerShell</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://blogs.technet.microsoft.com/paulomarques/2016/03/21/working-with-azure-active-directory-graph-api-from-powershell/"><span
  lang=EN-US>https://blogs.technet.microsoft.com/paulomarques/2016/03/21/working-with-azure-active-directory-graph-api-from-powershell/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:71.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>88</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I need to have
  clear overview of the costs of the solution and to which budget it will be
  charged</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:71.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please see our public Pricing documentation. <i>Client</i>
  is entitled to a discount on Azure pricing as agreed last June. <br>
  All Azure Services can be tagged with custom information, for example cost
  centers. This information will be reflected on the invoice, which allows for
  show and/or charge back to different business units</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://azure.microsoft.com/en-us/pricing/details/active-directory-b2c/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/pricing/details/active-directory-b2c/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>89</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Operations I require
  integration with <i>Client</i> AzureAD for controlling authentication and
  authorizations for my support employees</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C supports integration with Azure
  AD</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview
  </span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>90</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require NO changes to a <i>Client</i>
  firewall for integration to Active Directory.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>All communications use SSL</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>91</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Operational</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require Integration to 3rd
  party SIEM systems for comprehensive company-wide analytics.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Use (export) Log Analytics &amp; audit logs.
  Please know that B2C can be used together with Azure Sentinel</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://techcommunity.microsoft.com/t5/Azure-Sentinel/Azure-Sentinel-Azure-B2C/m-p/360773"><span
  lang=EN-US>https://techcommunity.microsoft.com/t5/Azure-Sentinel/Azure-Sentinel-Azure-B2C/m-p/360773</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:14.25pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>92</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Privacy and Consent management</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want to be compliant with
  national and internatial privacy regulations</span></p>
  </td>
  <td width=586 nowrap style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:14.25pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Please see our documentation</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>93</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Privacy and Consent management</span></p>
  </td>
  <td width=331 nowrap style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to know
  that my personal data is securely protected</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is the case and Externally audited. The
  audit reports are published in the Trust Center</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://servicetrust.microsoft.com/Documents/ComplianceReports"><span
  lang=EN-US>https://servicetrust.microsoft.com/Documents/ComplianceReports</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>94</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Privacy and Consent management</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to give and
  change my consent to <i>Client</i> for using my data</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Supported through Custom Policy</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://justidm.wordpress.com/2018/10/01/add-a-terms-of-use-consent-page-to-azure-ad-b2c-user-journey-with-custom-policies/"><span
  lang=EN-US>https://justidm.wordpress.com/2018/10/01/add-a-terms-of-use-consent-page-to-azure-ad-b2c-user-journey-with-custom-policies/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>95</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Privacy and Consent management</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to delete my account including all personal data</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This can be done directly on the logon page</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-users-restore"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/fun<i>Client</i>tals/active-directory-users-restore</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>96</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Profile Unification</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to automatically match/merge mulitple user logins, social media with email
  addresses etc.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Supported using custom policy</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>97</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Progressive profiling</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want to be able
  to request (actively and automatically) additional information of a user
  after the completion of registering for a <i>Client</i> customer account</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This can be achieved with either out of the
  box functionality or Custom Policies, depending on the desired customer
  journey</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>98</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Project</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want to have a professional
  services team that can help with deployments, customization (if needed), and
  training.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Microsoft has it's own Consultancy Services
  (MCS) organisation and also an extensive Partner ecosystem. Different
  training options, both free and paid is available for all our services.</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a href="https://www.microsoft.com/en-us/enterprise/services"><span
  lang=EN-US>https://www.microsoft.com/en-us/enterprise/services</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>99</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Project</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want the CIAM provider to
  provide an implementation strategy and sample plan.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>There are multiple succesfull implementations
  done by Microsoft and/or it's partners. </span><span lang=NL
  style='color:black'>We can support in choosing the right one.</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>100</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Project</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want the CIAM provider to
  show reference customer case studies, but should also be able to provide a
  customer for specific reference questions</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>for example Real Madrid
  https://www.microsoft.com/inculture/sports/real-madrid/<br>
  and Customer Stories under
  https://azure.microsoft.com/en-us/services/active-directory-b2c/</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>101</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Project</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want a brief explanation of
  the migration processes and strategy used by the vendor</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Please see our documentation</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>102</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Provider Standards Assurance</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require cloud solutions to
  be certified by third party institutions(ISO, SAS, SOC, ISAE, etc)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please visit our TrustCenter for insights on
  this requirement</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a href="https://servicetrust.microsoft.com/">https://servicetrust.microsoft.com/</a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>103</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Purchase</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> IT Purchase I want to have
  clear insight in the licensing / subscription models</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure AD B2C falls under the same contract and
  pricing model as the other Azure Services that <i>Client</i> uses</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://azure.microsoft.com/en-us/pricing/details/active-directory-b2c/"><span
  lang=EN-US>https://azure.microsoft.com/en-us/pricing/details/active-directory-b2c/</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>104</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Purchase</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I should have Sales Engineers
  located in our area for dedicated pre-sales and evaluation support, and
  should also have 24x7 live support options for post-deployment technical
  questions.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Account Team (Pre), Deployment Partner,
  Premier support (Post)</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>105</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want clear security
  Incident response and resolution/remediation SLAs applicable for security
  incidents identified by <i>Client</i>, supplier or third parties</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please check our Online Services Terms</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="http://www.microsoftvolumelicensing.com/Downloader.aspx?documenttype=OST&amp;lang=English"><span
  lang=EN-US>http://www.microsoftvolumelicensing.com/Downloader.aspx?documenttype=OST&amp;lang=English</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>106</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want to be informed of
  security breaches within 2 hours after discovery by supplier</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please check our Online Services Terms, it
  states 72 hours in GDPR Article 33.1</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="http://www.microsoftvolumelicensing.com/Downloader.aspx?documenttype=OST&amp;lang=English"><span
  lang=EN-US>http://www.microsoftvolumelicensing.com/Downloader.aspx?documenttype=OST&amp;lang=English</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>107</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require my instance to be
  disabled after a critical security breach cannot be resolved within the
  agreed SLA</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Please check our Online Services Terms</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="http://www.microsoftvolumelicensing.com/Downloader.aspx?documenttype=OST&amp;lang=English"><span
  lang=EN-US>http://www.microsoftvolumelicensing.com/Downloader.aspx?documenttype=OST&amp;lang=English</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>108</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require all data in rest
  and in transit to be encrypted using industry best practice encryption
  technology</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Encryption Whitepaper in Trust Center</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/information-protection/compliance"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/information-protection/compliance</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>109</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want the CIAM solution to
  be penetration tested by a independent third party at least annually and I
  want to receive a copy of the report of this test</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Certifications and Attestations in Trust
  Center</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://servicetrust.microsoft.com/ViewPage/TrustDocumentsV3?docTab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913_Pen_Test_and_Security_Assessments"><span
  lang=EN-US>https://servicetrust.microsoft.com/ViewPage/TrustDocumentsV3?docTab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913_Pen_Test_and_Security_Assessments</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>110</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I want to be able to perform
  a pentest on the CIAM solution or ask a third party to do this on my behalf</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>External pentest reports are available in
  Trust Center</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/security/fundamentals/pen-testing"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/security/fun<i>Client</i>tals/pen-testing</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>111</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Security</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As <i>Client</i> I require the ability to
  utilize open standards for authentication (e.g. SAML v1.1 and v2.0, WS-Fed,
  WS-Trust, OpenID Connect) as well as proprietary Auth methods (e.g. for
  forms-based auth or basic auth).</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>All is supported except Forms Based and Basic
  Auth</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-methods"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-methods</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>112</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Self-service password management</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to change and reset my password without intervention from <i>Client</i>
  employees and within 30 seconds</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Self Service password reset for 'local'
  accounts supported, social logins dependend of provider</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-sspr"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-sspr</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>113</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Self-service registration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to sign up for a <i>Client</i> customer account without intervention from <i>Client</i>
  employees and within 2 minutes</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>All User Flows are self service by default,
  including Sign-up</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-policies"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-policies</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>114</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Self-service user profile management</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to quickly manage my profile data without intervention of <i>Client</i>
  employees and within 10 seconds</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>All User Flows are self service by default,
  including User Profile Management</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:42.75pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>115</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Service requests</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want 24/7
  support in case of emergency (data issues, wrong billing etc etc) -&gt; self
  service desk idea</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:42.75pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Microsoft has this in place for it's provided
  services. For <i>Client</i>'s end customers, this should be covered by <i>Client</i>,
  where Microsoft can be third line when our provided service is the cause.</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>116</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Service requests</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> employee I want 24/7
  support in case of emergency (data issues, wrong billing etc etc) -&gt; self
  service desk idea</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is both part of the Azure Standard
  Support plan from the EA and escalation can be handled through the existing
  Premier Support plan</span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>117</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Single Sign On (SSO)&#8203;</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to have all
  my services/products in one portal and only authenticate once to access my <i>Client</i>
  services</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>That is the purpose of Azure B2C </span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-token-session-sso"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-token-session-sso</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>118</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Single Sign On (SSO)&#8203;</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want one <i>Client</i>
  account and password to access all my <i>Client</i> services.</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>This is supported by B2C, either through a
  local or social account</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-overview</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:28.5pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>119</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Single Sign On (SSO)&#8203;</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to check a &quot;remember me&quot; to prevent logging in again after I
  restarted my computer</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:28.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Optional in Custom Policy (Super Cookie)</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-kmsi-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-kmsi-custom</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;padding:0cm 3.5pt 0cm 3.5pt;
  height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>120</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Social registration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to sign up for a <i>Client</i> customer account with my social accounts
  (facebook, twitter, linkedin, instagram, google etc..)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure B2C supports the following Social
  Account Providers: <br>
  Amazon, Facebook, GitHub (preview), Google, LinkedIn, Microsoft Account
  (MSA), QQ (preview), Twitter, WeChat (preview), and Weibo (preview)</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-kmsi-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-kmsi-custom</span></a></span></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid;height:57.0pt'>
  <td width=32 nowrap style='width:23.75pt;border-top:none;border-left:solid #8EA9DB 1.0pt;
  border-bottom:solid #8EA9DB 1.0pt;border-right:none;background:#D9E1F2;
  padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>121</span></p>
  </td>
  <td width=100 nowrap style='width:75.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'>Social registration</span></p>
  </td>
  <td width=331 style='width:248.25pt;border:none;border-bottom:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>As a <i>Client</i> customer I want to be able
  to sign in to my <i>Client</i> customer account with my social accounts
  (facebook, twitter, linkedin, instagram, google etc..)</span></p>
  </td>
  <td width=586 style='width:439.75pt;border-top:none;border-left:none;
  border-bottom:solid #8EA9DB 1.0pt;border-right:solid #8EA9DB 1.0pt;
  background:#D9E1F2;padding:0cm 3.5pt 0cm 3.5pt;height:57.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=EN-US style='color:black'>Azure B2C supports the following Social
  Account Providers: <br>
  Amazon, Facebook, GitHub (preview), Google, LinkedIn, Microsoft Account
  (MSA), QQ (preview), Twitter, WeChat (preview), and Weibo (preview)</span></p>
  <p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><span
  lang=NL style='color:black'><a
  href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-kmsi-custom"><span
  lang=EN-US>https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-reference-kmsi-custom</span></a></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span lang=EN-US>&nbsp;</span></p>
