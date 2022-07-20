# DETE: Block 2.4

Created: 2022-02-10 18:57:38 +0100

Modified: 2022-02-17 19:24:01 +0100

---

<https://ihateregex.io/expr/ip/>



Todo: Code Snippets erstellen für Log Import



-----



Cat access.log | grep -c GET

Cat access.log | grep -c curl/7.65.3

Wc -s access.log

Wc -s curl/7.65.3

Grep -F -c 10.34.148.59 access.log

Grep -F "curl/7.65.3" access.log | wc -l

Cat access.log | grep "curl" | cut -d "[" -f2 | cut -d "]" -f1 | sort | uniq | wc -l



Get-content .acess.log | Select-string "curl" | Sort-Object | Get-Unique



# erster Eintrag

Cat access.log | grep "10.34.148.59" | cut -d "[" -f2 | cut -d "]" -f1 | sort | head -1

# letzter Eintrag

Cat access.log | grep "10.34.148.59" | cut -d "[" -f2 | cut -d "]" -f1 | sort | tail -1

# erster DoS

Cat access.log | grep "10.34.148.59" | grep "curl" | cut -d "[" -f2 | cut -d "]" -f1 | sort | head -1
