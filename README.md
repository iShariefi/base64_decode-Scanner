# base64_decode-Scanner

base64_decode-Scanner was designed specifically for the eval(base64_decode(‘…’)) hack, and quickly scans all files and subdirectories in its parent folder.  If it doesn’t locate any malicious code, no worries.  But if it does, it quickly sends an email detailing the specific file locations where the malicious, or just downright dangerous code is located.

Special thanks to **Dr. Rochak Chauhan**, as this was based on his idea.

Read the blog post on [iNfernalBlog](https://shuvo.rocks) to understand how to utilize this properly...

https://shuvo.rocks/a-simple-script-to-find-base64_decode
