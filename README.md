# github-recon-linkgen
 sed -i '/^\s*$/d' gitrec.txt 
awk '{print "https://github.com/search?q=org:\"example\" " $0}' file.txt
awk '{print "https://github.com/search?q=\"example\" " $0}' file.txt
