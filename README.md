# EML Attachments

## Inline

```eml
Subject: Test Email With Inline Images
From: Self-Email <bot@hubelbauer.net>
To: Tomas Hubelbauer <tomas@hubelbauer.net>
Content-Type: multipart/alternative;
  boundary=abcdefabcdefabcdefabcdefabcdef

--abcdefabcdefabcdefabcdefabcdef
Content-Type: multipart/related;
  boundary=fedcbafedcbafedcbafedcbafedcba

--fedcbafedcbafedcbafedcbafedcba
Content-Id: <bot+hi.png@hubelbauer.net>
Content-Disposition: inline;filename=\"hi.png\"
Content-Type: image/png; name=\"hi.png\"
Content-Transfer-Encoding: BASE64

…

--fedcbafedcbafedcbafedcbafedcba
Content-Id: <bot+me.png@hubelbauer.net>
Content-Disposition: inline;filename=\"me.png\"
Content-Type: image/png; name=\"me.png\"
Content-Transfer-Encoding: BASE64

…

--fedcbafedcbafedcbafedcbafedcba--

--abcdefabcdefabcdefabcdefabcdef
Content-Type: text/html

This is a test email.
<br />
<img src=\"cid:bot+hi.png@hubelbauer.net\" />
<br />
<img src=\"cid:bot+me.png@hubelbauer.net\" />
<br />
<br />
Thanks
```
