# Write-a-program-to-read-a-file-and-display-its-contents
f=open(&#39;myfile.txt&#39;,&#39;w&#39;)
f.write(&#39;My first file&#39;)
f.close()
f=open(&#39;myfile.txt&#39;,&#39;a&#39;)
f.write(&#39;\nWelcome Every one&#39;)
f.write(&#39;\nAppend Mode&#39;)
f.close()
f=open(&#39;myfile.txt&#39;,&#39;r&#39;)
print(f.read())
f.close()
Output:
My first file
Welcome Every one
Append Mode
