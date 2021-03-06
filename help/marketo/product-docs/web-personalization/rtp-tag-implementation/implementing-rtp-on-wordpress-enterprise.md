---
unique-page-id: 4720215
description: Implementing RTP on Wordpress Enterprise - Marketo Docs - Product Documentation
title: Implementing RTP on Wordpress Enterprise
---

# Implementing RTP on Wordpress Enterprise {#implementing-rtp-on-wordpress-enterprise}

To implement your RTP tag please follow the installation instructions below:

1. Go to** Account Settings.**

    1. If you have already received your JavaScript tag from Support - continue to step 3.  
       ![](assets/image2014-11-30-15-3a19-3a21-3.png)

1. Under Domain, locate the relevant domain and click **Generate Tag**.

   ![](assets/image2014-11-30-15-3a20-3a17-3.png)

1. Copy the RTP JavaScript tag.
1. Login to your WordPress account as Admin User

   1. Under **Appearance**, go to **Custom JavaScript**.
   1. Paste the RTP Javascript tag right after the existing code.  

      ![](assets/image2014-12-3-17-3a51-3a46.png)

   >[!CAUTION]
   >
   >When you paste the code EXCLUDE the following tags:
   >
   >* `<!-- RTP tag -->`
   >* `<script type='text/javascript'>`
   >* `</script>`
   >* `<!-- End of RTP tag -->`
   >    
   >Insert the script itself ONLY.

1. Click **Update**.
