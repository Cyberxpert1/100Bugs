
# 100 Bugs           #Series 101

# Day 1                                      17-01-2025 
![IMG_20250117_111927](https://github.com/user-attachments/assets/ab094a04-2274-41e8-a817-b41a5e32f04f)

# Day 2                                      18-01-2025
![IMG_20250118_213719](https://github.com/user-attachments/assets/4e03d958-cbb6-4a6d-99ba-bbc483f0903e)


# Day 3                                       19-01-2025
![IMG_20250119_212404](https://github.com/user-attachments/assets/6ca92ebc-fa9d-4a0a-b5d9-3a209068c9d5)

# Day 4                                       20-01-2025
![IMG_20250119_212444](https://github.com/user-attachments/assets/3e375835-ade0-4641-a8c5-f043afa21866)


# Day 5                                       21-01-2025    
![IMG_20250121_123954](https://github.com/user-attachments/assets/9567b04d-3dfd-47e6-971e-33176ab45e6d)


# Day 6                                      22-01-2025
![IMG_20250122_181610](https://github.com/user-attachments/assets/bea7763d-5c2b-4df2-8af4-a119cd814878)


# Day 7                                      23-01-2025
![IMG_20250123_234158](https://github.com/user-attachments/assets/68960adc-d62a-4726-bce0-13e29f36416e)

# Day 8                                      24-01-2025
![IMG_20250124_225508](https://github.com/user-attachments/assets/077f8b69-8682-481f-9c4e-589461f02aec)

# Day 9                                       25-01-2025
![IMG_20250126_145027](https://github.com/user-attachments/assets/e6db412a-4332-4913-b342-b5ed9b63e18e)

# Day 10                                      26-01-2025
![IMG_20250126_145113](https://github.com/user-attachments/assets/702a8c94-fe76-4f52-8660-4e8c066760fe)

# Day 11                                      27-01-2025
![photo_2025-01-27_00-29-22 (2)](https://github.com/user-attachments/assets/79b84e9b-5e31-41aa-b511-cf78faf7b780)

# Day 12                                      28-01-2025
![Screenshot 2025-01-29 105944](https://github.com/user-attachments/assets/fe140408-d249-4dc1-929a-49817f6b0213)

# Day 13                                       29-01-2025
Extract all endpoints from a JS File and take your bug 🐞
✅Method one
waybackurls HOSTS | tac | sed "s#\\\/#\/#g" | egrep -o "src['\"]?
15*[=: 1\5*[ '\"]?[^'\"]+.js[^'|"> ]*" | awk -F '/'
'{if(length($2))print "https://"$2}' | sort -fu | xargs -I '%' sh
-c "curl -k -s \"%)" | sed \"s/[;}\)>]/\n/g\" | grep -Po \" (L'1|\"](https?: )?[/1{1,2}[^'||l"> 1{5,3)|(\.
(get|post|ajax|load)\s*\(\5*['||\"](https?:)?[/1{1,2}[^'||\"> ]
{5,})\"" | awk -F "['|"]" '{print $2}' sort -fu
✅Method two
cat JS.txt | grep -aop "(?<=(\"|\'|' ))\/[a-zA-Z0-9?&=\/-#.](?= (\"||'|'))" | sort -u | tee JS.txt

# Day 14                                      30-01-2025

# Day 15                                      31-01-2025       

# Day 16 

# Day 17

# Day 18

# Day 19 

# Day 20







# 100 Bugs 
